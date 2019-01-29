.. DMSParser

DMSParser部署
====================================   

流程的重心在于具体业务的实现，而业务的组织，特别是大型业务场景的组织，则需要多个流程共同来实现。为了便于用户组织业务场景，数据专家提供DMSParser部署方案。

DMSParser是一个数据专家执行容器，为用户提供一个开放的界面构造、流程执行与展现、软件发布平台；通过DMSParser用户可以发布自已的应用系统。其基本原理是，构造一个内存网页浏览器，用户编写HTML脚本构造界面、组织业务场景，浏览器负责HTML解释与展示、界面参数向流程参数传递、流程运行与运行反馈等功能。

DMSParser原理:

.. figure:: DMSParserImages/DMSParser1.png
    :align: center
    :figwidth: 90% 
    :name: plate
	
DMSParser由HTML页面编写、DMS流程编制、窗口启动配置三个部分构成，其目录组织结构如下:
	
.. figure:: DMSParserImages/DMSParser2.png
    :align: center
    :figwidth: 90% 
    :name: plate

其中：

   # DMSParser.exe为主程序；
   
   # DMSParser.exe.config为窗口启动配置参数；
   
   # DMS为用户内容组织目录。

下面以一个简单的案例来说明这一实现原理。在报告标题、报告描述对话框中输入文字，单击运行，右侧的页面中显示相应的运行报告。

.. figure:: DMSParserImages/DMSParser3.png
    :align: center
    :figwidth: 90% 
    :name: plate


业务流程构造
-----------------------------------

本案例中，业务流程由三个节点构成，功能为用一个报告浏览节点展示缓存表格数据。流程中定义了title与desc两个流程变量，浏览节点将它们作为报告的标题与描述项。

业务流程：

.. figure:: DMSParserImages/DMSParser4.png
    :align: center
    :figwidth: 90% 
    :name: plate

流程变量定义：

.. figure:: DMSParserImages/DMSParser5.png
    :align: center
    :figwidth: 90% 
    :name: plate

流程变量使用：
	
.. figure:: DMSParserImages/DMSParser6.png
    :align: center
    :figwidth: 60% 
    :name: plate

HTML页面编写
-----------------------------------

面对具体的业务场景，用户的需求是多样的，HTML语言具有高灵活、门槛低的特征，因此系统选用了HTML作为DMSParser前端业务场景组织语言。

上述案例中，HTML代码如下::

    <!DOCTYPE html>
    <html>
    <head>
        <style>
            html, body { height: 100%; }    
            html {overflow: hidden;}    
            form.hpform {
                float: left;
                width: 20%;
            }
            iframe {
                float: left;
                height: 98%;
                margin-left: 2%;
                width: 78%;
            }
        </style>
        <script type="text/javascript" src="js\jquery.js"></script>
        <script type="text/javascript">
    
            function Run() {
                //收集界面参数，并换成JSON字符串，其中Object对象的属性名与流程变量名相对应。
                var anObject = new Object();
                anObject.title = $("#title").val();
                anObject.desc = $("#desc").val();
                var obj = JSON.stringify(anObject);
    
                //调用浏览器函数，运行数据专家流程，通过回调函数返回结果。
                RunDMS('Demo.DMS', obj, CallBack);
            }
    
            //回调函数，url为内存网站地址
            function CallBack(url) {
                var el = document.getElementById('ifrm');
                el.src = url;
            }
        </script>
    </head>
    <body>
    
        <!--界面参数-->
        <form method="post" class="hpform">
            <input id="title" type="text" placeholder="报告标题" value="报告标题" style="width: 100%" /><br>
            <textarea id="desc" placeholder="报告描述" style="height: 100px;width: 100%">报告描述</textarea><br>
            <input type="button" onclick="javascript:Run();" value="运行" />
            
            <!--窗口控制命令-->
            <input type="button" value="关闭" onclick="Close();" />
            <input type="button" value="窗口" onclick="NoneBorder(false);" />
            <input type="button" value="正常化" onclick="WindowState('normal');" />
            <input type="button" value="最大化" onclick="WindowState('max');" />
            <br>
        </form>
        
        <!--内容显示-->
        <iframe id="ifrm" Name="ifrm" frameborder="0"></iframe>
    
    </body>
    </html> 


浏览器函数
-----------------------------------

DMSParser本质上是一个网页浏览器，它可以解析并展示HTML脚本；同时，提供了多个内置函数。

RunDMS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

函数体: RunDMS(string FileName,string Pars,function CallBack);

流程执行函数，调用数据专家流程并运行默认输出节点。

其中：

   # FileName为流程文件名称；   
   
   # Pars为Json字符串，Json属性与流程全局变量对应；
   
   # CallBack为回调函数；格式为 FunctionName(URL)，URL为内存网页地址；
 
Close
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

函数体: Close()

关闭系统函数，无参数，运行后退出系统；

NoneBorder
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

函数体: NoneBorder(bool flag)

窗口边框控制函数，控制主界面的边框显示与否；flag为True时，隐藏窗口边框；为False显示边框。

WindowState
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

函数体: WindowState(string state)

窗口状态函数，控制主界面显示状态；state可选值有min、max、normal，分别对应于窗体最小化、最大值与正常显示。
 
窗口启动设置
-----------------------------------

用户可以通过配置DMSParser.exe.config文件，设置主窗体启动时的状态。

启动参数::

    <?xml version="1.0" encoding="utf-8"?>
    <configuration>
        <startup> 
            <supportedRuntime version="v4.0" sku=".NETFramework,Version=v4.6.2"/>
        </startup>
      <appSettings>
        
        <!--设置窗口边框是否显示--> 
        <add key="NoneBorder" value="True"/>
        
        <!--设置窗口开启时状态，可选值有：min,max,normal-->
        <add key="WindowState" value="max"/>
    
        <!--设置主窗体标题-->
        <add key="Title" value="数据专家系统"/>
    
        <!--设置主窗体显示的图标--> 
        <add key="Icon" value="DMSParser.ico"/>
      </appSettings>
    </configuration>

炫酷版示例：
	
.. figure:: DMSParserImages/DMSParser7.gif
    :align: center
    :figwidth: 90% 
    :name: plate

	
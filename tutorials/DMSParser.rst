.. DMSParser

DMSParser部署
====================================   

流程的重心在于具体业务的实现，而业务的组织，特别是大型业务场景的组织，则需要多个流程共同来实现。为了便于用户组织业务场景，数据专家DMSParser部署方案。

DMSParser是一个数据专家执行容器，为用户提供一个开放的界面构造、流程执行与展现、软件发布工具；通过DMSParser用户可以发布自已的应用系统。其基本原理为，提供内存网站浏览器，用户通过编写HTML脚本构造界面、组织业务场景，该浏览器支持HTML解释与展示、HTML界面参数向流程参数传递、流程运行与运行反馈展现等功能。

DMSParser原理:

.. figure:: DMSParserImages/DMSParser1.png
    :align: center
    :figwidth: 90% 
    :name: plate
	
DMSParser使用，由HTML页面编写、DMS流程编制、窗口启动配置三个部分构成，其目录组织结构如下:
	
.. figure:: DMSParserImages/DMSParser2.png
    :align: center
    :figwidth: 90% 
    :name: plate

其中DMSParser.exe为主程序；DMSParser.exe.config为窗口启动配置参数；DMS为用户内容组织目录。

下面以一个简单的案例来说明实现原理。在报告标题、报告描述对话框中输入文字，单击运行，右侧的页面中显示相应的运行报告。

.. figure:: DMSParserImages/DMSParser3.png
    :align: center
    :figwidth: 90% 
    :name: plate


业务流程构造
-----------------------------------

本案例中，业务流程由三个节点构成，功能为用一个报告浏览节点展示缓存表格数据。流程中定义了title与desc两个流程变量，浏览节点使用它们使用为报告的标题与描述项。

业务流程：

.. figure:: DMSParserImages/DMSParser4.png
    :align: center
    :figwidth: 90% 
    :name: plate

流程变量：

.. figure:: DMSParserImages/DMSParser5.png
    :align: center
    :figwidth: 90% 
    :name: plate

流程变量使用：
	
.. figure:: DMSParserImages/DMSParser6.png
    :align: center
    :figwidth: 90% 
    :name: plate

业务流程构造
-----------------------------------





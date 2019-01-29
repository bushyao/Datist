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

	
目录结构
-----------------------------------

主程序为DMSParser.exe，主页面为DMS/Index.html；

.. figure:: DMSParserImages/DMSParser2.png
    :align: center
    :figwidth: 90% 
    :name: plate	
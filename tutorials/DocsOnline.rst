.. DocsOnline


数据钻取管理器
====================================

数据钻取是通过执行外部的流程、DLL对数据专家的浏览器进行扩展功能。目前支持扩展功能的浏览器有：数据浏览器的右键菜单、地理图浏览器的信息钻取功能和报告浏览器的DrillDown命令。

数据钻取的基本原理是从浏览器中获取部分字段的信息，作为参数传递给数据钻取项并执行之。系统提供流程扩展与DLL扩展两种数据钻取项的定义方式。

1）流程扩展项的执行目标是流程。执行时，从浏览器中获取数据，传递给目标流程变量，并执行流程中默认输出节点。如下图所示：

.. figure:: images/DocsOnline01.png
     :align: center
     :figwidth: 90% 
     :name: plate 	 
 

2）DLL扩展项的执行目标是DLL中的静态函数。执行时，从浏览器中获取数据，作为参数传递给DLL的函数并运行函数。可以用它来集成企业里的信息系统，也可用它来快速访问、查看各类文档功能。

.. figure:: images/DocsOnline02.png
     :align: center
     :figwidth: 90% 
     :name: plate 	   

	 
数据钻取项定义
----------------------------------

在主菜单的设置菜单下，数据钻取管理菜单可以开启数据钻取管理器。

1）流程扩展：定义流程扩展项；增加流程扩展项操作步骤如下：
 
步骤一：右键菜单，单击【添加流程】菜单页，在弹出的打开文件对话框中，选取流程； 

.. figure:: images/DocsOnline05.png
     :align: center
     :figwidth: 60% 
     :name: plate 

步骤二：在新增的记录行中，补充菜单名称和表单字段；  
 
.. figure:: images/DocsOnline03.png
     :align: center
     :figwidth: 90% 
     :name: plate 	   

右键菜单说明： 
	
  #. 添加流程：新增流程钻取项；    
  #. 查看流程：在流程编辑区打开流程；
  #. 更新流程参数：从目标流程中读取流程参数列表，并更新流程参数数据项的内容；	
  #. 删除流程：删除选中的流程钻取项；
 
2）DLL扩展：定义DLL扩展项；
 
步骤一：右键菜单，单击【添加DLL】菜单页，在弹出的“设置DLL数据钻取器”对话框中，选取DLL文件及命名空间、函数名称，系统自动反射出函数的参数名称；
  
.. figure:: images/DocsOnline06.png
     :align: center
     :figwidth: 60% 
     :name: plate 	
	 
步骤二：在新增的记录行中，补充菜单名称和表单字段；    
  
.. figure:: images/DocsOnline04.png
     :align: center
     :figwidth: 90% 
     :name: plate 	     

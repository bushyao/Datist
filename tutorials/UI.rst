﻿
UI界面与流程协作
====================================

在实际的生产过程中，流程的复杂度远超越我们的想象；在复杂流程中修改节点的参数，会让人产生恐怕与厌恶；我们希望有一个简单的界面进行交互操作，并获得想要结果。Datist 中提供UI界面功能，可以帮助您解决这一烦恼。

1、需求描述

经典应用场景，在1号位的文本框中输入井号列表，单击2号位的运行按键，立即获得3号位的查询结果；

.. figure:: images/UI1.png
     :align: center
     :figwidth: 90% 
     :name: plate 	
	 
数据浏览结果

.. figure:: images/UI2.png
     :align: center
     :figwidth: 90% 
     :name: plate 	

2、实现原理

   * 第一步：输入井号列表，并传值给流程Ⅰ中节点A（通过流程变量txt实现）；
   * 第二步：规范化井号列表，运行流程Ⅰ，将井号列表进行标准化处理后（本例中输入数据，标准化工作由输入节点自带的功能实现），通过节点B赋值给流程变量（WellList）
   * 第三步：查询并返馈结果，流程Ⅱ中节点C使用流程变量WellList，进行数据查询，并输出查询结果。

.. figure:: images/UI3.png
     :align: center
     :figwidth: 90% 
     :name: plate 	

.. note::

   以上三步由系统自动运行。

	 
流程变量定义：

   * $txt，界面参数传送变量
   * $WellList，流程参数传送变量

.. figure:: images/UI4.png
     :align: center
     :figwidth: 90% 
     :name: plate 	


节点A，输入参数设置

.. figure:: images/UI5.png
     :align: center
     :figwidth: 100% 
     :name: plate 	


节点B，更新变量参数设置

.. figure:: images/UI6.png
     :align: center
     :figwidth: 100% 
     :name: plate 	


节点C，筛选参数设置

.. figure:: images/UI7.png
     :align: center
     :figwidth: 100% 
     :name: plate 	

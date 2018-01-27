.. NodeSpatialProcess 
   
图元交并补
====================================
求多个图元之间的交集、并集、补集以及异或集。


图元运算类型
------------------------

支持五种运算类型：

.. list-table:: 

   * - 操作图示
     - 操作类型
     - 详细描述
	 
   * - .. image:: images/NodeSpatialProcess01.png
     - 并集
     - 返回多个图元之间合并的结果图元。
	
   * - .. image:: images/NodeSpatialProcess02.png
     - 图元A减图元B
     - 返回多个图元之间相差的结果图元。
	
   * - .. image:: images/NodeSpatialProcess03.png
     - 图元B减图元A
     - 返回多个图元之间相差的结果图元。	
	 
   * - .. image:: images/NodeSpatialProcess04.png
     - 交集
     - 返回多个图元之间公共部分的结果图元。	

   * - .. image:: images/NodeSpatialProcess05.png
     - 异或集
     - 返回多个图元之间非公共部分的结果图元。
	 

数据组织
------------------------

支持两种数据组织方式：

   * **图元汇总** ，对一列图元进行操作，类似于汇总节点，支持分组汇总功能；
   * **多图元运算** ，对于一条记录内的两个图元进行操作。
   
图元汇总模式：

.. figure:: images/NodeSpatialProcess06.jpg
     :align: center
     :figwidth: 90% 
     :name: plate 	  
  
     图元汇总模式界面

图元列，指定的待运算的图元数据列；

分组列，指定的分组字段，支持多个，可为空；

	 
多图元运算模式：	 
	 
.. figure:: images/NodeSpatialProcess07.jpg
     :align: center
     :figwidth: 90% 
     :name: plate 	  
  
     多图元运算模式界面	 
	 
图元列A，指定的第一个图元列；

图元列B，指定的第二个图元列。
	 
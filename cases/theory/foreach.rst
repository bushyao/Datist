
批处理工作原理
====================================
在数据分析过程中，会遇到很多同类的问题，它们之间仅在参数上有微小的差异，我们可以每个参数编制一个流程，当然这个方法过于繁琐。

Datist 提供了批处理功能，也可称之为循环运行、列遍运行等，就是让流程根据指定数据列表分别运行一遍。

如何去构造循环结构，需要用到流程变量，通过以下简单的批处理流来进行说明。

假设公司要给员工涨工资了，老板让在原有工资基础上，按1.1、1.5、2.0、2.5等倍率，分别造一个表，拿过来瞅瞅；于是财务部分的小李就制作了以下的流程：

.. figure:: images/foreach1.png
     :align: center
     :figwidth: 100% 
     :name: plate 	
	 
.. figure:: images/foreach4.png
     :align: center
     :figwidth: 100% 
     :name: plate 	
	 
.. figure:: images/foreach2.png
     :align: center
     :figwidth: 100% 
     :name: plate 	
	 

.. figure:: images/foreach3.png
     :align: center
     :figwidth: 100% 
     :name: plate 	
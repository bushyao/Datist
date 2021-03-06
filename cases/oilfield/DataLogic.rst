﻿.. DataLogic

这个数据正确性嘛？
====================================
常见同一实体的相关数据之间相互冲突，如同一编号的样品，在两个不同表中的井号不一致，同一口井的在两个数据库中井状态不一致。

Datist 提供【同值匹配度】分析节点，用于同一实体，多个不同之间的数据逻辑检查。具备有同值比较、条件比对两种模式，支持数据钻取、数据源实体、输出Excel等多项功能。

分析试验数据库数据逻辑检查流程：

.. figure:: images/DataLogic01.png
     :align: center
     :figwidth: 90% 
     :name: plate 
	 
**1、同值模式**

相同样品编号下，井号是否一致？

同值匹配度节点参数设置

.. figure:: images/DataLogic02.png
     :align: center
     :figwidth: 90% 
     :name: plate 	 
  
比对结果
 
.. figure:: images/DataLogic03.png
     :align: center
     :figwidth: 90% 
     :name: plate 	 
	 
**2、表达式模式**

相同样品编号下，井号是否一致？逻辑上，送样日期是否早分析日期？（完钻深度、正钻深度？）

节点参数设置	 
	 
.. figure:: images/DataLogic04.png
     :align: center
     :figwidth: 90% 
     :name: plate 	 
	 	 
比对结果
	 
.. figure:: images/DataLogic05.png
     :align: center
     :figwidth: 90% 
     :name: plate 	 
 
扫描电镜数据表与分析试验主数据表比较，相同编号而井名不一致的样品数据：
 
.. figure:: images/DataLogic06.png
     :align: center
     :figwidth: 90% 
     :name: plate 	 
	 
.. note::

   技术易产生崇拜，特别是跨学科的技术合作过程，然而产品的研发往往受限于开发者的当时当地的思维状态，思维局限性会带来大量的BUG，甚至是系统性的错误。
   
   同一件事，同一个目标，我们需要辩证地去看，在深究技术细节的同时，也要有包容的心态去看待过往的系统。
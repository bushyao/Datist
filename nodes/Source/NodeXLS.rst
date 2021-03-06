﻿智能解析
=====================
最核心功能之一，用于从灵活多变的Excel电子表格中，抽取出目标数据。例如，地质学家可以用它从由不同单位分析的多个物性报告中，抽提出孔隙度、渗透率、饱和度的数据。

数据页设置
-----------------
 
模板操作工作组：
 
  * 加载模板：装载电子表格智能解析模板文件；装载之后流程将不依赖模板文件；

  * 更新模板：当原始模板文件修改之后，单击该按钮对流程中的模块进行更新；

  * 模板设计：打开模板设计对话框，进行模板设计；

  * Save：将模板文件另存到指定的位置；

文档目录：指定待解析的Excel文件存放的目录，点击右侧的省略号按钮，可通过对话框选取；解析过程中，系统将对该目录及其子目录下的所有Excel文件进行解析；

日志文件：指定Excel解析日志存放的位置；日志文件，给您提供一份关于Excel文件解析的完整报告，当然您也可以使用数据专家进行分析，从中提取您关心的内容；

备份文件：勾选，则在Excel解析过程中，将未能解析的Excel文件复制指定的目录中；不勾选，则不进行备份处理；

所有表单：勾选，则在Excel解析过程中，将对所有的表单进行解析；不勾选，当第一个满足模板的表单解析后，将不对后续的表单进行解析；

弹出结果窗口：勾选，在解析结束后，弹出解析报告；
  
测试模板（仅读取5行）：勾选，在解析过程中，只从报告中取5行数据，可用于验证模板的有效性。
 
.. note::  
  更多关于模板文件的创建与使用，请联系 `客服人员 <http://www.datist.cn/>`_。 
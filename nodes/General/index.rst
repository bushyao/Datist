.. _index:

节点总览
======================


.. list-table:: 数据源组
   :widths: 15 10 30
   :header-rows: 1

   * - 节点
     - 名称
     - 描述
	 
   
   * - .. image:: images/NodeDBDirect.jpg 
     - 接入数据库
     - 直连方式（不需驱动），接入DB2、FirebirdClient、MS Access、MySQL、ODBC、OLE DB、Oracle、OracleClient、PostgreSQL、SQL Server、SQLite等数据库。


   * - .. image:: images/NodeSplitString.jpg 
     - 数据录入
     - 提供文本录入框，录入文本作为数据源；支持将文本劈分成多行。


   * - .. image:: images/NodeCache.jpg 
     - 表格数据
     - 内部特殊应用，将特定节点输出的数据作库临时的数据源。


   * - .. image:: images/NodeExcelSheet.jpg 
     - Excel
     - 接入Excel表单数据，支持xls、xlsx两种格式。


   * - .. image:: images/NodeXLS.jpg 
     - 智能解析
     - 从多个Excel报告中，提取需要的数据项；支持报告任意的样式。


   * - .. image:: images/NodeTXTEx.jpg 
     - TXT+
     - 读入多个文本文件，支持分隔符分隔格式和固定列宽格式。


   * - .. image:: images/NodeWordImport.jpg 
     - Word
     - 接入Word中数据表。


   * - .. image:: images/NodePDFSource.jpg 
     - PDF
     - 接入PDF中数据表。


   * - .. image:: images/NodeWIS.jpg 
     - WIS
     - 接入测井数据体(WIS格式)，提取曲线道、表格及流等数据。


   * - .. image:: images/NodePolygonSource.jpg 
     - 空间数据
     - 支持ArcGIS、AutoCAD、DLG、GML、GeoJSON、GeoMap、GSHHS、Google Earth、GPS、LandXML、LiDAR LAS、MapInfo、MicroStation、OpenStreetMap、SDTS、SQL Layer等。


   * - .. image:: images/NodeMapNO.jpg 
     - 接图表
     - 根据指定的坐标范围及比例尺，输出地形图接图数据表。


   * - .. image:: images/NodeScanFiles.jpg 
     - 扫描目录
     - 扫描本地目录，将文件目录信息引入到流程中。


   * - .. image:: images/NodeRedisGetAllkeys.jpg 
     - RedisKeys
     - 获取Redis数据。


   * - .. image:: images/NodeIMacros.jpg 
     - 网页抓取
     - 录制宏，抓取网页内容。


   * - .. image:: images/NodeWFKS.jpg 
     - 网页数据
     - 获取网页数据资源。


   * - .. image:: images/NodeRunStream.jpg 
     - 先导流程
     - 运行指定流程中的所有默认输出节点(本流程变量具有穿透能力),输出流程运行结果。


   * - .. image:: images/NodeStreamAppend.jpg 
     - 流程穿越
     - 某流程的【数据浏览】节点穿越到当前流程中；运行过程中，本流程参数也具有穿越能力。


   * - .. image:: images/NodeExSource.jpg 
     - 数据引擎
     - 用户自定义数据读取引擎，读入数据。


   * - .. image:: images/NodeScript.jpg 
     - 脚本数据
     - 通过自定义C#脚本方式解析文件，实现文件的接入。



.. list-table:: 行列计算组
   :widths: 15 10 30
   :header-rows: 1

   * - 节点
     - 名称
     - 描述
	 
   
   * - .. image:: images/NodeSelect.jpg 
     - 筛选
     - 从数据中，挑选出符合条件的行。


   * - .. image:: images/NodeSample.jpg 
     - 定量筛选
     - 从数据中，挑选出一定数量的行。


   * - .. image:: images/NodeDerive.jpg 
     - 新列
     - 在数据表中新增一列数据。


   * - .. image:: images/NodeDeriveEx.jpg 
     - 多列
     - 在数据表中新增多列数据。


   * - .. image:: images/NodeFiller.jpg 
     - 替换
     - 替换数据表中某列的值。


   * - .. image:: images/NodeFilter.jpg 
     - 过滤
     - 删除或重命名数据表中的列。


   * - .. image:: images/NodeMerge.jpg 
     - 合并
     - 按指定条件，将多个来流程的数据合并成一个数据。


   * - .. image:: images/NodeAppend.jpg 
     - 追加
     - 将多个流程的数据，追加成一个数据。


   * - .. image:: images/NodeSort.jpg 
     - 行序
     - 按指定方式，对数据进行排序。


   * - .. image:: images/NodeFieldSort.jpg 
     - 列序
     - 调整数据表中列的顺序。


   * - .. image:: images/NodeAggregate.jpg 
     - 汇总
     - 按指定条件，对数据进行分组汇总，支持求和、均值、最值、合并字符串等。


   * - .. image:: images/NodeAggregateEx.jpg 
     - 定制汇总
     - 按指定条件，对数据进行分组汇总，用户需要定义汇总条件等。


   * - .. image:: images/NodeDistinct.jpg 
     - 去重
     - 从数据中，删除重复的行。


   * - .. image:: images/NodeFieldOffset.jpg 
     - 值偏离
     - 将邻近行的值，赋值指定的列中。


   * - .. image:: images/NodeRowID.jpg 
     - 字段累加
     - 对某列数据，进行累计计算。


   * - .. image:: images/NodeReplaceValue.jpg 
     - 向上取值
     - 将指定条件的数据项，替换成之前不合符条件的值，一般用于补充空行值。


   * - .. image:: images/NodeSynonym.jpg 
     - 同义词
     - 规范化字段的表达方式。


   * - .. image:: images/NodeWordMarker.jpg 
     - 打标签
     - 给文本打标签。


   * - .. image:: images/NodeBetweenRows.jpg 
     - 记录分组
     - 根据开始条件、结果条件，对记录进行筛选。


   * - .. image:: images/NodeGetStrings.jpg 
     - 提取文本
     - 根据指定的语法，提取文本字符。


   * - .. image:: images/NodeDeriveDy.jpg 
     - 补全列
     - 如果前面指定的列不存在，将创建指定的列。


   * - .. image:: images/NodeSequence.jpg 
     - 补充序列
     - 汇总节点的小跟班，向数据表中添加多条记录，从而保证数列的完整性。


   * - .. image:: images/NodeSet.jpg 
     - 交并补
     - 多个数据表之间的集合运算。


   * - .. image:: images/NodeRow2Col.jpg 
     - 行列转换
     - 行列转换,最多支持255行。


   * - .. image:: images/NodeRecord2Field.jpg 
     - 汇总转列
     - 汇总后，将某列数据项翻转成多个新列。


   * - .. image:: images/NodeFieldSplit.jpg 
     - 列劈成行
     - 将多列数据劈分后，转存到一列。


   * - .. image:: images/NodeRowSplit.jpg 
     - 行数据劈分
     - 按同一规则拆分记录中的数据项。拆分后，每个数据项的第一个拆分结果组成第一条记录；第二个组成二条记录……


   * - .. image:: images/NodeColumnSplit.jpg 
     - 列劈分
     - 将单列劈分成多个列。


   * - .. image:: images/NodeAdjustColumns.jpg 
     - 归位器
     - 对二维表中的值进行归位处理，适用智能解析结果的列值归位。


   * - .. image:: images/NodeZTable.jpg 
     - 数据分栏
     - 对数据进行分栏处理,最多支持5000行。


   * - .. image:: images/NodeZTableAppend.jpg 
     - 分栏合并
     - 合并分栏数据。



.. list-table:: 空间分析组
   :widths: 15 10 30
   :header-rows: 1

   * - 节点
     - 名称
     - 描述
	 
   
   * - .. image:: images/NodeCreatePoint.jpg 
     - 创建点图元
     - 通过数值列创建空间点图元。


   * - .. image:: images/NodePolyBuild.jpg 
     - 创建多边形
     - 通过点图元创建多边形或折线。


   * - .. image:: images/NodeGISProjection.jpg 
     - 投影变换
     - GIS投影系统变换。


   * - .. image:: images/NodeSpatialInfo.jpg 
     - 图元信息
     - 计算图元的面积、周长、中心点等空间信息。


   * - .. image:: images/NodeDistance.jpg 
     - 距离
     - 计算两个图元之间的距离。


   * - .. image:: images/NodeGeneralize.jpg 
     - 简化图元
     - 减少多边形或折线中的端点数。


   * - .. image:: images/NodeSmooth.jpg 
     - 平滑图元
     - 对图元进行平滑。


   * - .. image:: images/NodeBuffer.jpg 
     - 缓冲区
     - 计算图元的缓冲区。


   * - .. image:: images/NodeSpatialProcess.jpg 
     - 图元交并补
     - 求两个图元之间的交集、并集、补集以及异或集。


   * - .. image:: images/NodeSpatialMatch.jpg 
     - 空间匹配
     - 根据空间关系匹配图元，支持相交、接边、包含等。


   * - .. image:: images/NodeNearest.jpg 
     - 最近图元
     - 从多个图元中找出最近的图元。


   * - .. image:: images/NodePolygonSelect.jpg 
     - 区块筛选
     - 计算点坐标所属性区块名称。


   * - .. image:: images/NodePolygonSplit.jpg 
     - 面面劈分
     - 一个面劈分另一个面。


   * - .. image:: images/NodeImpact.jpg 
     - 权重多边形
     - 空间影响因子。


   * - .. image:: images/NodeContour.jpg 
     - 等值线
     - 通过数值列创建空间趋势线。



.. list-table:: 高级计算组
   :widths: 15 10 30
   :header-rows: 1

   * - 节点
     - 名称
     - 描述
	 
   
   * - .. image:: images/NodeFileConvert.jpg 
     - 格式转换
     - 将文件数据体转换为特定的文件格式。


   * - .. image:: images/NodeFileOpt.jpg 
     - 文件操作
     - 剪切、复制文件。


   * - .. image:: images/NodeJsonToken.jpg 
     - 解析Json
     - 解析Json数据体。


   * - .. image:: images/NodeToJsonString.jpg 
     - 生成JSON
     - 将数据转换为JSON数据格式。


   * - .. image:: images/NodeWord.jpg 
     - 词频统计
     - 统计文本中词组的频率。


   * - .. image:: images/NodePreAssociation.jpg 
     - 关联准备
     - 为关联规则分析准备数据。


   * - .. image:: images/NodeIndicatorCheck.jpg 
     - 示功判断
     - 判识油井功图状态。


   * - .. image:: images/NodeSourcePanel.jpg 
     - 数据源面板
     - 将数据字典，预处理接入数据源面板


   * - .. image:: images/NodeChange.jpg 
     - 数据源切换
     - 在多个流程之间进行切换。该节点有多个输入，通过该节点指定一个作为后续节点的数据源。


   * - .. image:: images/NodeExFunction.jpg 
     - 接口函数
     - 调用外部DLL文件中的静态函数，返回运行结果。


   * - .. image:: images/NodeExtestion.jpg 
     - 脚本处理
     - 通过自定义C#脚本方式处理数据。



.. list-table:: 数据库与数据质量组
   :widths: 15 10 30
   :header-rows: 1

   * - 节点
     - 名称
     - 描述
	 
   
   * - .. image:: images/NodeRedisCacheRead.jpg 
     - 读云缓存
     - 从Redis服务器缓存取数据。


   * - .. image:: images/NodeRedisCacheWrite.jpg 
     - 写云缓存
     - 向Redis服务器缓存前节点的数据。


   * - .. image:: images/NodeRedisGetData.jpg 
     - RedisData
     - 获取RedisData。


   * - .. image:: images/NodeDBTableCount.jpg 
     - 数据表计数
     - 计算数据表或视图的记录数。


   * - .. image:: images/NodeDBValues.jpg 
     - 数据库抽样
     - 从多个数据表中，挑选出一定量的行。


   * - .. image:: images/NodeDBFind.jpg 
     - 数据库查找
     - 从多个数据表中，查询整个数据库中某个特定值所在的表和字段。


   * - .. image:: images/NodeDBRun.jpg 
     - 数据库运行
     - 将前节点运行逻辑组织成SQL语句，由数据库执行。


   * - .. image:: images/NodeFieldNameMatch.jpg 
     - 字段名配对
     - 对多个数据表中字段名进行配对分析。


   * - .. image:: images/NodeFieldDesc.jpg 
     - 数据描述
     - 描述数据的统计量，字段的极值、均值、分位数、异常值等信息。


   * - .. image:: images/NodeFieldCompare.jpg 
     - 数据匹配度
     - 检查多个数据表中字段的匹配程度。


   * - .. image:: images/NodeSameField.jpg 
     - 同值匹配度
     - 检查多个数据表中，相同值条件下，字段的匹配程度。


   * - .. image:: images/NodeSummary.jpg 
     - 探索分析
     - 通过计算统计量、绘制相关图件，对数据探索分析。



.. list-table:: 经典算法组
   :widths: 15 10 30
   :header-rows: 1

   * - 节点
     - 名称
     - 描述
	 
   
   * - .. image:: images/NodeEDA.jpg 
     - EDA
     - 试探性数据分析。


   * - .. image:: images/NodeLinearRegression.jpg 
     - 线性回归
     - 用线性回归方程对一个或多个自变量和因变量之间关系进行建模。


   * - .. image:: images/NodeLogisticRegression.jpg 
     - 逻辑回归
     - 用逻辑回归方程对一个或多个自变量和因变量之间关系进行建模。


   * - .. image:: images/NodeRegression.jpg 
     - 广义回归
     - 广义线性模型,包括线性回归、逻辑回归、泊松回归、逆高斯回归、伽马回归等若干种。


   * - .. image:: images/Nodehclust.jpg 
     - 系统聚类
     - 是将个样品分成若干类的方法。


   * - .. image:: images/NodeKCentroidsCluster.jpg 
     - 动态聚类
     - 以空间中k个点为中心进行聚类，对最靠近他们的对象归类。


   * - .. image:: images/NodeETS.jpg 
     - 时间序列
     - 将同一统计指标的数值按其发生的时间先后顺序排列而成的数列。


   * - .. image:: images/NodeKNN.jpg 
     - 邻近算法
     - 如果一个样本在特征空间中的k个最相邻的样本中的大多数属于某一个类别，则该样本也属于这个类别，并具有这个类别上样本的特性。


   * - .. image:: images/NodeAssociationRule.jpg 
     - 关联规则
     - 关联规则挖掘属于无监督学习方法，它描述的是在一个事物中物品间同时出现的规律的知识模式。


   * - .. image:: images/NodeNaiveBayesClassifier.jpg 
     - 朴素贝叶斯
     - 一种基于独立假设贝叶斯定理的简单概率分类器。


   * - .. image:: images/NodeNeuralNetwork.jpg 
     - 神经网络
     - 试图模仿大脑的神经元之间传递，处理信息的模式。


   * - .. image:: images/NodeRandomForest.jpg 
     - 随机森林
     - 利用多棵树对样本进行训练并预测的一种分类器。


   * - .. image:: images/NodeSVM.jpg 
     - SVM
     - 支持向量机SVM(Support Vector Machine）是一个有监督的学习模型，通常用来进行模式识别、分类、以及回归分析。


   * - .. image:: images/NodeDecisionTree.jpg 
     - 决策树
     - 一种树形结构，其中每个内部节点表示一个属性上的测试，每个分支代表一个测试输出，每个叶节点代表一种类别。



.. list-table:: 数据可视化组
   :widths: 15 10 30
   :header-rows: 1

   * - 节点
     - 名称
     - 描述
	 
   
   * - .. image:: images/NodeTatukGIS.jpg 
     - 地理图
     - 绘制条形图、饼图、柱状图、开发现状图等平面专题图件。


   * - .. image:: images/NodeWebMap.jpg 
     - WebMap
     - 在线地图，在百度地图、谷歌影像上展示数据。


   * - .. image:: images/NodeColorMap.jpg 
     - 专题地图
     - 生成颜色渲染的专题地图。


   * - .. image:: images/NodeHeatmapMap.jpg 
     - 地理热力图
     - 热力图与地理图相结合。


   * - .. image:: images/NodeGoogleEarth.jpg 
     - 高清影像
     - 将数据推送Skyline、GoogleEarth软件中进行展示。


   * - .. image:: images/NodeChartP.jpg 
     - 常用统计图
     - 绘制柱状图、条形图、饼图、折线图、散点图、面积图等常用统计图。


   * - .. image:: images/NodeWebChartEx.jpg 
     - 智能统计图
     - 自定义EChart图。


   * - .. image:: images/NodeHistogram.jpg 
     - 直方图
     - 绘制直方图。


   * - .. image:: images/NodeTempletChart.jpg 
     - 地质图版
     - 绘制岩性三角分类图、C-M图、孔渗恢复、压汞曲线、施氏网、吴氏网、童宪章图版等多种地质研究常用的图版。


   * - .. image:: images/NodeIndicator.jpg 
     - 示功图
     - 绘制油井示功图。


   * - .. image:: images/NodeWordCloud.jpg 
     - 词云图
     - 词云图，反映热点词汇。


   * - .. image:: images/NodeHeatmapCartesian.jpg 
     - 热力图
     - 以特殊高亮的形式显示热衷的区域。


   * - .. image:: images/NodeWebChartTest.jpg 
     - JsChart
     - 通过JS脚本定义EChart图形，进行数据可视化。



.. list-table:: 数据发布组
   :widths: 15 10 30
   :header-rows: 1

   * - 节点
     - 名称
     - 描述
	 
   
   * - .. image:: images/NodeTable.jpg 
     - 浏览数据
     - 以二维表的形式输出数据。


   * - .. image:: images/NodePivotgird.jpg 
     - 透视表
     - 以透视表的形式输出数据。


   * - .. image:: images/NodeDBWrite.jpg 
     - 写入数据库
     - 将数据表写入数据库中，支持Oracle、SQL Server、MySql、Access、DB2、Postgresql、Firebird、dBASE、SQLite、FoxPro等数据库。


   * - .. image:: images/NodeDBWriteEx.jpg 
     - 写入MySql
     - 极速，将数据表写入数据库中，目前支持MySql数据库。


   * - .. image:: images/NodeDBBackup.jpg 
     - 数据库备份
     - 备份数据库中的多张数据表


   * - .. image:: images/NodeExport.jpg 
     - 保存为文件
     - 输出数据表，支持Excel、Word、HTML、PDF、XML等多种格式。


   * - .. image:: images/NodeGISExport.jpg 
     - 存空间文件
     - 输出空间数据，支持ArcGIS、AutoCAD、GML、GeoJSON、Google Earth、GPS、MapInfo等多种格式。


   * - .. image:: images/NodeDownload.jpg 
     - 数据项转存
     - 将文本、BLOB、网络地址数据项转存为单个文件。


   * - .. image:: images/NodeZIP.jpg 
     - ZIP压缩
     - 文件收集器的跟班，打包压缩文件流生成ZIP文件，保存到磁盘中或向后流转。


   * - .. image:: images/NodeFTPBrowser.jpg 
     - FTP下载
     - 在线查看、批量下载FTP文件。


   * - .. image:: images/NodeFTPUpload.jpg 
     - FTP上传
     - FTP上传文件。


   * - .. image:: images/NodeScp.jpg 
     - SCP
     - 使用SCP协议，安全拷贝。


   * - .. image:: images/NodeRedisSender.jpg 
     - RedisWrite
     - 向Redis发数据。


   * - .. image:: images/NodeSendEmail.jpg 
     - 发邮件
     - 将数据处理的结果，发送特定的邮箱。


   * - .. image:: images/NodeSMS.jpg 
     - 发短信
     - 将数据处理的结果，发送指定的手机上。


   * - .. image:: images/NodeWeixin.jpg 
     - 发微信
     - 将数据处理的结果，发送指定的微信帐号。


   * - .. image:: images/NodeDict.jpg 
     - 划词字典
     - 生成划词字典。


   * - .. image:: images/NodeThink.jpg 
     - 注释
     - 记载临时想法，不进行任何计算。


   * - .. image:: images/NodeWebLogger.jpg 
     - 消息步骤
     - 向WebService发送一条消息。



.. list-table:: 报告与软件接口组
   :widths: 15 10 30
   :header-rows: 1

   * - 节点
     - 名称
     - 描述
	 
   
   * - .. image:: images/NodeHtmlReport.jpg 
     - 浏览报告
     - 通过MarkDown技术，将数据以报告形式展现。


   * - .. image:: images/NodeHtmlTable.jpg 
     - HTML表格
     - 通过模板生成HTML表格。


   * - .. image:: images/NodeExcelTempleteHelper.jpg 
     - XLS模板
     - Excel模板制作器。


   * - .. image:: images/NodeExportXLS.jpg 
     - Excel
     - 将数据输出Excel中，支持模板，可插入文本、图片等内容。


   * - .. image:: images/NodeExcelCombine.jpg 
     - Excel合并
     - 将前节点输出的Excel表单，合并成一个文件。


   * - .. image:: images/NodeExportDoc.jpg 
     - WordEx
     - 以模板方式，将数据输出Word中，可插入文本、图片、表单、Excel表单等内容。


   * - .. image:: images/NodeDocCombine.jpg 
     - Word合并
     - 将节点输出的Word表单，合并成一个文件。


   * - .. image:: images/NodePPT.jpg 
     - PPT
     - 以模板方式，将数据输出PPT中，可插入文本、图片、表单、Excel表单等内容。


   * - .. image:: images/NodePPTCombine.jpg 
     - PPT合并
     - 将前节点输出的PPT，合并成一个文件。


   * - .. image:: images/NodeSVG.jpg 
     - SVG
     - 使用SVG模板，输出图形。


   * - .. image:: images/NodeSuferFile.jpg 
     - Sufer
     - Sufer软件接口，将数据推送至Sufer中，绘制等值线。


   * - .. image:: images/NodeBas.jpg 
     - Bas
     - 通过自定义Bas脚本方式处理数据。


   * - .. image:: images/NodeBat.jpg 
     - CMD
     - 运行Windows批处理命名，处理数据。


   * - .. image:: images/NodeScriptOutput.jpg 
     - C#
     - 通过自定义C#脚本方式处理数据。


   * - .. image:: images/NodeGMT.jpg 
     - GMT
     - 运行GMT，处理数据。


   * - .. image:: images/NodePython.jpg 
     - Python
     - 通过自定义Python脚本方式处理数据。


   * - .. image:: images/NodeREx.jpg 
     - R
     - 粘入R代码进行调试，输出结果


   * - .. image:: images/NodeSSH.jpg 
     - SSH
     - 使用SSH协议，远程控制计算机并执行命令。


   * - .. image:: images/NodeExOutput.jpg 
     - 通用接口
     - 将数据推送给DLL或指定的流程中，实现外部平台、系统的接入。



.. list-table:: 运行控制组
   :widths: 15 10 30
   :header-rows: 1

   * - 节点
     - 名称
     - 描述
	 
   
   * - .. image:: images/NodeParameter.jpg 
     - 更新变量
     - 将取值字段第一行的值，赋值给流程变量。


   * - .. image:: images/NodeDispatcher.jpg 
     - 流程调度
     - IF/FOR,选择性运行指定流程中的所有默认输出节点。


   * - .. image:: images/NodeStreamCollection.jpg 
     - 文件收集器
     - 将节点输出的文件流，整合入库。


   * - .. image:: images/NodeStreamRunner.jpg 
     - 顺序运行器
     - 运行节点，并向后流转前节点的数据。


   * - .. image:: images/NodeStreamCondRunner.jpg 
     - 条件运行器
     - 根据指定的条件运行节点。



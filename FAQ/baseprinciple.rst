﻿.. _FA:

基本原理
======================
数据专家是什么？
-----------------
假设数据是信息的“水流”，而处理数据过程是一个由管道和阀门组成的巨大水管网络。网络入口是若干管道的开口，网络出口也是若干管道的开口。这个水管网络有许多层，每一层有许多个可以控制水流流向与流量的调节阀。根据不同任务的需要，水管网络的层数、每层调节阀数量可以有不同的变化组合。对复杂任务来说，调节阀的总数可以成百上千甚至更多。水管网络中，每一层的每个调节阀都通过水管与下一层的调节阀连接起来，组成一个从前到后逐层完全连通的水流系统。

数据专家的基本原理就是把数据处理过程中涉及的处理方法抽象成一个个的节点（调节阀），为用户提供一个开放的平台，组建自己的数据处理系统（水流系统），完成特定的数据分析、处理任务。

数据专家有什么意义？
-----------------
数据专家研发的宗旨是“让数据流程化，使科研更智能”，其关键在于让业务人员能够进行软件的开发，用它去解决实际问题。

这与软件开发的规律相吻合，一个科研软件系统中最核心的算法代码量仅占5%，其余部分包括数据加载、清洗、变换、报告编制等工作，这些工作是软件系统工程中最基础的功能，程序开发中这部分的工作视为重复造轮子。数据专家的作用就是将系统建设过程聚集在核心的算法之上。这个5%是最难的，软件开发人员需要花很时间去理解业务，然而这是业务人员最善长的，这就是发挥关键少数的作用。

佛家讲“契理契机”，上契诸佛之理，下契众生之机，我们既要准确地理解业务本身的原理，又要实实在在解决实际问题。数据专家通过可视化的方式把复杂的处理过程可视化，以便于用户进行开发与迭代；同时鼓励用户之间进行流程共享，相互学习，使数据处理思想与方法得以继承与创新。

前后节点之间是什么关系？
-----------------
节点布局和思维导图的布局很相近，它是一层一层的，类似于水流系统。前面节点的输出是后面节点的输入，这是一种串联递进关系。在这个水流系统中，在节点之间流动是二维表格数据。节点的输入是一张或几张二维表，而输出是一张二维表。

维，一般指的是方向，一维就是一个方向，二维就是两个方向。Excel表格就是典型的二维表，二维就是指行与列。

学习数据专家需要具备哪些基础知识？
-----------------
数据专家以追求简化用户操作为已任，然而实战中，数据处理复杂度远超过我们的想象。业务处理越复杂，其相应的数据流程就越复杂，所以我们希望用户具备两个方面的基础知识：

1）C语言，包括数据类型、条件语句和循环语句等基础知识；

2）数据库SQL语句，SQL是数据专家的基础，数据专家底层就是SQL，了解SQL语言，以便于您理解数据专家的运行方式。

语言相对比较抽象，只需要掌握基本原理，数据专家把很多事件都可视化了，每个节点，都能对应至SQL语句中；每个节点，都是在解决一个实际的问题；每个问题可能涉及一个或多个技术要点，把技术要点理清、剖析清楚，就能想明白了。

如何获取数据专家的学习资源？
-----------------
数据专家的学习资源相对有限，您可以在流程商店、常用问题集、节点帮助流程、节点帮助中获取您需要的信息，同时也欢迎您在流程商店中分享自己动成果，供他人学习。最直接且高效的方式是加入QQ、微信群，对群主进行地毯式轰炸。

如何规划流程编写过程？
-----------------
对于复杂的数据处理过程，流程编写之前，规划编写步骤显得非常重要。因具体处理问题不同，其涉及的节点组合也有很大的差异，但流程制作过程可遵循一般的方法论与步骤。CRISP-DM就是一个很好的方法论。一般而言，可将数据处理过程归纳为以下几步骤。

1）业务问题的理解

了解所要解决问题的背景知识，收集必要的文档资料，如数据字典、关键指标等。把待解决的问题归结为数据处理的节点，抽象出数据流步骤。

2）数据预处理

①数据字段名映射，将字段名重命名为具有实际意义的名称是非常必要的，在流程制作过程中，也尽可能地使用具有实际意义的名称作字段名，这会给数据分析与理解带来便捷。

②数据类型变换，把采集来的数据转换为合理的数据类型，通常是把字符型的字段转换为数值型，这会减少大量的数值计算过程的困扰；

③对异常的记录进行筛选，如去空值记录，极值记录；

④去掉一些无用的列，数据量越大，跑得会越慢，去掉一无用的列有助于提升运行效率；

⑤数据分段，数据复杂的原因多种多样，对于数据进行适当的分类，对不同类型的数据分别进行处理，有利于厘清数据处理的逻辑，简化后续数据处理的复杂度。

⑥数据抽样，可以尝试对数据进行抽样，在最开始的数据流程创建过程中，不知道自己想要什么，数据基本特征是什么，最终要输出是什么，有什么细节问题需要处理，无数次的执行与预览是相当耗时的，比如1000万的数据或是1个亿数据，查询一次都需要花费很长的时间。数据抽样在少量的样本数据中制作流程，做试验，再用大数据量数据跑流程，有助于提高流程制编写的效率。

3）数据建模

选择合适的方法建模进行数据分析与可视化。使用经典算法、空间分析、数据可视化、软件接口等节点进行数据分析，使用微信、邮件等节点发布数据。

4）流程优化

优化数据处理过程增强流程的可读性，提升流程的运行效率。

5）部署应用

将流程等部署到服务器上定时运行，或是嵌入到BIS系统中在线应用。

如何编写数据流程的总结报告？
-----------------

报告编写是一个讲故事的过程，写出关于一个流程的前因后果，交待一些背景性的信息，做一件事的意义是什么？与读者共鸣。

1）场景的描述

把所解决问题的现实意义描述清楚，从相对宏观的角度去描述对整个行业的意义是什么？做这件事的必要性是什么？有哪些关键的节点？

2）数据基本特征的描述

是什么样的数据？有什么具体的特征，在数据处理过程中需要注意什么？

3）流程实现的基本思路是什么？难点问题在哪里？如何把业务问题转化为数据处理问题，使用数据专家去实现。

4）实施过程，具体的流程实现有哪些值得分享的细节呢？

5）小结一下

业务角度有意义，描述对输出成果详细解释；或是描述使用数据专家前后的效率上的差异。

什么是数据源节点、中间处理节点与终端节点？
-----------------
数据专家根据运行过程中节点充当的角色将其划分成：数据源节点、中间处理节点、终端节点。

数据源节点：位于工具箱的数据源栏中，将外部数据引入数据专家中，如：数据库节点、数据表格节点、智能解析节点等，它们是整个流程的入口。

中间处理节点：位于行列计算、空间分析、高级计算等工具栏中，它们可实现数据的清洗、转换、筛选工作，如：新列、替换、过滤等节点。

终端节点：主要位于经典算法、数据可视化、报告与软件接口、数据发布等工具栏中，它们是多数为可视化节点，拥有自己独有的数据浏览器，如：报告浏览、地理图形、统计图等。

随着文件收集器节点的出现，它收集终端节点的可视化成果再次引入到流程中，使得终端节点与中间处理节点的界线越来越模糊，使得用户不用严格区别节节点的类型。

流程变量何时起作用？
-----------------
数据专家中提供流程变量的功能，流程变量应用非常广泛，常见于流程中的多个节点之间的参数共享，流程外部调用时的参数传递、批处理等应用场景中。

流程变量的使用包括变量定义、表达式中应用、变量赋值等多个环节；

1）变量定义，在【流程属性】窗口的【流程变量】栏中，新增、编辑流程变量。注，您可以在不同的流程文件之间复制、粘贴流程变量；

2）表达式中应用，在表达式中常会见到‘$’开始的标记，这就是流程变量，它由$符号+流程变量名称构成；流程运行过程中会用流程变量的值替换流程变量。

3）流程变量的赋值操作有多种：

更新变量节点方式：最常用的方式，从流程中取值赋值给流程变量；

批处理方式：批处理运行时，取待执行列表的值赋值给流程变量；

值传递方式：流程外部调用时，流程变量参数的值传递，常见到BS系统、流程调试节点使用过程中。

在批处理运行时，若需求同时更新多个变量进行循环，可将更新变量的节点作为控制器节点的前节点，将其设置为不在流程运行前运行。在控制器节点运行时，调用该更新变量节点对相应用流程变量进行赋值，从而实现多个变量更新与协作。

提示流程变量循环引用怎么办？ 
-----------------
在同一个流程中，不能对一个变量既使用又更新；这种循环引用，就像先有蛋后有鸡，还是先有鸡后有蛋呢？数据专家无以判断。

因此，请检查流程中流程变量的使用情况与赋值情况，清除流程变量的引用；

此外，在系统运行时会自动创建流程变量与节点之间的对应关系（解析节点中的表达式，并建立起与流程变量之间的应用关系），然而这种关系确立与使用通常具有一定的滞后性。若出现循环引用的提示，不妨在【流程属性】窗口中的【流程变量】栏，右键菜单中【清除节点调用关系】。再次运行时，系统将再次建立起节点与流程变量的关系。

控制器是什么？
-----------------
在数据专家的节点中，有一组控制流程执行方式的特殊节点，包括：流程调度、文件收集器、顺序运行器、条件运行器。

1）文件收集器，是将前面节点可视化结果，转化为数据体+元数据（描述）的方式存储，在这里二维表内容发现了变化；

2）顺序运行器和条件运行器是两种运行方式，它们一般有多个前节点，顺序运行根据前节点的顺序依次运行，而条件运行则是需要指定条件，当条件为真时，才会运行对应的前节点，否则不运行；

3）流程调试是实现流程之间的跳转的方法，适用于大型的数据处理项目中，容易引起思维跳跃，一般不建议使用；

如何实现批处理功能？
-----------------
数据流程（Data Stream）通常只完成一件事件。例如输出一个地震观测站的信息；然而省局有几十个观测站，一次输出所有观测站的信息怎么办呢？一种做法是复制出多个流程，分别输出各个观测站的信息，再合成一个报告；显然这种方式不够优雅，也不利于流程的维护。

数据专家提供了另一种方法：“批处理”，类似于循环语句中的FOR EACH语句，其中循环变量为流程变量，而枚举的列表则由“待执行值列表”充当。运行时，系统从“待执行列表”中依次取值赋给流程变量，并执行某段流程，从而获取多次运行的结果，以减少流程中重复分支，使流程更为优雅。由于批处理功能，在逻辑上具有一定的跳跃性，系统中只有文件收集器、顺序运行器、条件运行器才具备如此强悍功能。

数据太乱了怎么办？
-----------------
在实践中，常会把不同类别的数据存储在同一张数据表中，例如，运行日志信息，这就使得同一列中的不同的数据项具有不同的物理意义，使得数据处理过程变得尤其复杂，感觉数据特别的乱。

数据具有实际的意义，它的每一个字段都有特定的含义，在数据分析之前要了解其存储方式，物理意义以及它们之间的相互关系。一个数据项不是孤立的存在，当你发现它自身无法处理的时候，不妨看看其它列有没有可以帮助的信息，以便于您进行数据的处理。

数据不完整怎么办？
-----------------
数据分析不可能尽善尽美，有很多数据由于数据的缺失，在数据处理过程中只能丢弃的，如身份证的位数不够时。

条件表达式和取值表达式有什么区别？
-----------------
数据专家中涉及表达式有两类

1)条件表达式，计算结果为布尔型，只有两种取值：真(true)和假(false)，数据专家内部也支持用1代表真、0代表假； 

2)取值表达式，计算结果为任意类型，可以使用任意类型的函数来构建取值表达式；

例如：替换节点实际是IF（条件）THEN（替换值）的关系，条件为逻辑表达式；替换值为取值表达式。

数值运算结果出不来是怎么回事？
-----------------
系统中数字可这样几种形式存：字符串，整型、浮点型（实数，有小数的数），这三种类型是不通用的。因此，会出现'100'/10为空的现象。

在数据预处理中，一个非常必要的工作就是数据类型变换（过滤节点）。

注：关于数据类型变换有一个简便的方法，在过滤节点编辑器中的右键菜单中使用识别数值字段功能，进行快速判别字段类型，减少人工修改的工作量。

4043/7为啥是577.00而不是577.57呢？
-----------------
数据专家中整数之间相除默认为整除，您若想进行实数相除，请乘以1.0即可，如：4043*1.0/7。或将输入数据类型修改为实数，再进行相关的计算。

字符串不能正确比较怎么办？
-----------------
字符串比较是数据分析中最常见的操作，在字符串的比较过程中，常因字符串内的空格、字母大小写、数据标点全角与半角的差异，使得字符串比较得不到想要的结果。在数据专家进行字符串的比较是区分大小写的，为了方便用户进行比较，数据专家中提供trim、trimL、trimR、Lower、Upper、Proper等函数。同时建议在字符串比较之前，先进行必要的预处理工作，如删除字符串中的空格、换行符等。

如何实现跨行运算？
-----------------
跨行运算上下两行之间的比较、运算，如求两条日志、输出的时间间隔，储层研究中的夹层计算问题等。跨行运算是一个相对棘手的问题，数据专家中提供值偏离、向上取值、记录分组等系列节点，以帮助您进行跨行计算。在实践中，您需要将跨行问题归结为相应的数据处理问题，如记录分组、值偏离、向上取值等。

怎么以百分数的方式显示数值？
-----------------
百分号输出是一种输出格式，其数据类型仍然是实数。常见的输出格式还有货币符号、千分位等。

在数据专家中的两处可以定义输出格式：

1）【流程属性】窗口中【浏览数据】选项卡，定义流程数据浏览查看的默认样式。即流程数据查看的一般样式。

2）浏览数据节点编辑器中，定义当前浏览数据节点输出格式，即当前节点输出的特殊样式。

场景设计图形有什么用？
-----------------
数据专家中提供一组场景设计图形，用于流程修饰，表达作者的想法，以便于用户之间的交流。

场景图形可分为两大类：

1）形状可编辑类，如线条、多边形、星形等。用户可以修改图形上的锚点，编辑形状；

2）形状不可编辑类，此类图形的形状是不可编辑的，如四叶草、数据库、心形等图形。

.. _YouTianZhuanYong:
油田专用
======================

AccToDisplance
~~~~~~~~~~~~~~~~~~
函数体：AccToDisplance(string accArray, double detaT, double ChongCheng, double accelerationConst)

返回值：String

说明：示功图函数，将加速度数据转化为位移。

AppendWellHeaders
~~~~~~~~~~~~~~~~~~
函数体：AppendWellHeaders(String)

返回值：String

说明：补全井头的汉字。按常见字符分隔字符串String，返回补全汉字字头以“.”隔的字符串，如井12，23->井12，井23。其中井头最大汉字数为4。

函数体：AppendWellHeaders(String,MaxLen)

返回值：String

说明：补全井头的汉字。按常见字符分隔字符串String，返回补全汉字字头以“.”隔的字符串，如井12，23->井12，井23。参数MaxLen为井头最大汉字数。

函数体：AppendWellHeaders(String,MaxLen,SplitChars)

返回值：String

说明：补全井头的汉字。按SplitChars指定的字符分隔字符串String，返回补全汉字字头以SplitChar隔的字符串，如井12，23->井12，井23。参数MaxLen为井头最大汉字数。

Create8CWorkGrahp
~~~~~~~~~~~~~~~~~~
函数体：Create8CWorkGrahp(LocationString, LoadString)

返回值：String

说明：示功图函数，创建绘图数据。

GetWellName
~~~~~~~~~~~~~~~~~~
函数体：GetWellName(String)

返回值：String

说明：从字符串中，猜出井名

函数体：GetWellName(String,Headers,MiddleChinese,HeaderMaxLen,MiddleStringMaxLen,MaxIDCount)

返回值：String

说明：从字符串中，猜出井名；Headers指定井头；MiddleChinese指定井号中可出现的汉字，默认为空；HeaderMaxLen指定井字头的长度，默认为2；MiddleStringMaxLen排号中最大字符长度，默认为5；MaxIDCount最大排数，默认为3

RemoveWellHeaders
~~~~~~~~~~~~~~~~~~
函数体：RemoveWellHeaders(String)

返回值：String

说明：删除重复井头的汉字。按常见字符分隔字符串String，返回删除重复井汉字头以“.”隔的字符串，如井12，井23->井12，23。其中井头最大汉字数为4。

函数体：RemoveWellHeaders(String,MaxLen)

返回值：String

说明：删除重复井头的汉字。按常见字符分隔字符串String，返回删除重复井汉字头以“.”隔的字符串，如井12，井23->井12，23。参数MaxLen为井头最大汉字数。

函数体：RemoveWellHeaders(String,MaxLen,SplitChars)

返回值：String

说明：删除重复井头的汉字。按SplitChars指定的字符分隔字符串String，返回删除重复井汉字头以SplitChar隔的字符串，如井12，井23->井12，23。参数MaxLen为井头最大汉字数。

SplitWellHeaders
~~~~~~~~~~~~~~~~~~
函数体：SplitWellHeaders(String)

返回值：String

说明：劈分连续的井头，按常见字符分隔字符串String，如井12井23->井12.井23。其中井头最大汉字数为4。

函数体：SplitWellHeaders(String,MaxLen)

返回值：String

说明：劈分连续的井头，按常见字符分隔字符串String，如井12井23->井12.井23。参数MaxLen为井头最大汉字数。

函数体：SplitWellHeaders(String,MaxLen,SplitChars)

返回值：String

说明：劈分连续的井头，按SplitChars指定的字符分隔字符串String，如井12井23->井12，井23。参数MaxLen为井头最大汉字数。

ToKSHFXY
~~~~~~~~~~~~~~~~~~
函数体：ToKSHFXY(F25,F50,F75,IsX,SqrtSo)

返回值：Double

说明：孔隙度渗透度恢复坐标系转化为平面直角坐标系。F25,F50,F75为粒径φ值。IsX为真，输出平面坐标的横坐标X值，为假，则输出纵坐标Y值；SqrtSo为真，按特拉斯克(Trask)方程求解后开根号，假不开根号。

ToShiXY
~~~~~~~~~~~~~~~~~~
函数体：ToShiXY(N,H,IsX)

返回值：Double

说明：施氏网坐标系转化为平面直角坐标系。平面的产状，倾向为N，倾角为H。IsX为真，输出平面坐标的横坐标X值，为假，则输出纵坐标Y值。

ToTriXY
~~~~~~~~~~~~~~~~~~
函数体：ToTriXY(A,B,C,IsX,Normalize)

返回值：Double

说明：三角坐标系转化为平面直角坐标系。A、B、C为三角坐标。IsX为真，输出平面坐标的横坐标X值，为假，则输出纵坐标Y值；Normalize为真，三角坐标归一化处理，为假则不处理。

ToWuXY
~~~~~~~~~~~~~~~~~~
函数体：ToWuXY(N,H,IsX)

返回值：Double

说明：吴氏网坐标系转化为平面直角坐标系。平面的产状，倾向为N，倾角为H。IsX为真，输出平面坐标的横坐标X值，为假，则输出纵坐标Y值。

YGDn
~~~~~~~~~~~~~~~~~~
函数体：YGDn(JGLArray[],YLArray[],JGL)

返回值：Double

说明：计算压汞曲线上占累积进汞量N％的孔喉半径φ值。JGLArray[]为进汞量数组（X轴），YLArray[]为压力数组（Y轴），JGL为进汞量。注数组以字符串表示，元素间以“, 、;:"”,间隔。

YGJGL
~~~~~~~~~~~~~~~~~~
函数体：YGJGL(JGLArray[],YLArray[],YL)

返回值：Double

说明：计算压汞曲线上指定压力YL对应用的进汞量。JGLArray[]为进汞量数组（X轴），YLArray[]为压力数组（Y轴），YL为压力（Mpa）。注数组以字符串表示，元素间以“, 、;:"”,间隔。

YGPdgd
~~~~~~~~~~~~~~~~~~
函数体：YGPdgd(JGLArray[],YLArray[])

返回值：Double

说明：计算压汞样品的排驱压力（拐点法）。JGLArray[]为进汞量数组（X轴），YLArray[]为压力数组（Y轴）。注数组以字符串表示，元素间以“, 、;:"”,间隔。

YGPdpt
~~~~~~~~~~~~~~~~~~
函数体：YGPdpt(JGLArray[],YLArray[])

返回值：Double

说明：计算压汞样品的排驱压力（平台法）。JGLArray[]为进汞量数组（X轴），YLArray[]为压力数组（Y轴）。注数组以字符串表示，元素间以“, 、;:"”,间隔。

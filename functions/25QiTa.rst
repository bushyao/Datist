.. _QiTa:
其它
======================

@Fields
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：用在“替换节点”的条件中，代表任意字段名。

AccToDisplance(string accArray, double detaT, double ChongCheng, double accelerationConst)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：示功图函数，将加速度数据转化为位移。

AddressLat(string)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：获取地名对应的纬度坐标。

AddressLon(string)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：获取地名对应的经度坐标。

AddressStd(string)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：标准化地名书写。

Create8CWorkGrahp(LocationString, LoadString)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：示功图函数，创建绘图数据。

GetAddressByIdCard(string)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：从居民身份证号码中获取归属地。

GetAddressByIdCard(string,int)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：从居民身份证号码中获取归属地。int为输出内容标识符：1为省名，2为市名，3为县名，4为省名+市名，5为省名+市名+县名，6为省名|市名|县名

GetAddressNumByIdCard(string)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：从居民身份证号码中获取归属地编码。

GetAgeByIdCard(string)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：从居民身份证号码中获取年龄信息。

GetBirthdayByIdCard(string)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：从居民身份证号码中取生日。

GetSexByIdCard(string)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：从居民身份证号码中获取性别信息。

GUIDParse(String)
~~~~~~~~~~~~~~~~~~
返回值：GUID

说明：将文本转换为GUID值。

IsIdCard(string)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判断字符串是否为居民身份证。

NewGUID( )
~~~~~~~~~~~~~~~~~~
返回值：GUID

说明：返回一个随机生成GUID。

NewGUID(String)
~~~~~~~~~~~~~~~~~~
返回值：GUID

说明：根据所提供的格式说明符，返回一个随机生成GUID,参数可以是“N”、“D”、“B”、“P”；其中：N有连续符‘-’，D有连续符，B带大括号，P带小括号。

ToKSHFXY(F25,F50,F75,IsX,SqrtSo)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：孔隙度渗透度恢复坐标系转化为平面直角坐标系。F25,F50,F75为粒径φ值。IsX为真，输出平面坐标的横坐标X值，为假，则输出纵坐标Y值；SqrtSo为真，按特拉斯克(Trask)方程求解后开根号，假不开根号。

ToShiXY(N,H,IsX)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：施氏网坐标系转化为平面直角坐标系。平面的产状，倾向为N，倾角为H。IsX为真，输出平面坐标的横坐标X值，为假，则输出纵坐标Y值。

ToTriXY(A,B,C,IsX,Normalize)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：三角坐标系转化为平面直角坐标系。A、B、C为三角坐标。IsX为真，输出平面坐标的横坐标X值，为假，则输出纵坐标Y值；Normalize为真，三角坐标归一化处理，为假则不处理。

ToWuXY(N,H,IsX)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：吴氏网坐标系转化为平面直角坐标系。平面的产状，倾向为N，倾角为H。IsX为真，输出平面坐标的横坐标X值，为假，则输出纵坐标Y值。

XPath(docString, quertString)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：Will evaluate an XPath expression against text that is assumed to be XML, and will return the results.

YGDn(JGLArray[],YLArray[],JGL)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：计算压汞曲线上占累积进汞量N％的孔喉半径φ值。JGLArray[]为进汞量数组（X轴），YLArray[]为压力数组（Y轴），JGL为进汞量。注数组以字符串表示，元素间以“, 、;:"”,间隔。

YGJGL(JGLArray[],YLArray[],YL)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：计算压汞曲线上指定压力YL对应用的进汞量。JGLArray[]为进汞量数组（X轴），YLArray[]为压力数组（Y轴），YL为压力（Mpa）。注数组以字符串表示，元素间以“, 、;:"”,间隔。

YGPdgd(JGLArray[],YLArray[])
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：计算压汞样品的排驱压力（拐点法）。JGLArray[]为进汞量数组（X轴），YLArray[]为压力数组（Y轴）。注数组以字符串表示，元素间以“, 、;:"”,间隔。

YGPdpt(JGLArray[],YLArray[])
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：计算压汞样品的排驱压力（平台法）。JGLArray[]为进汞量数组（X轴），YLArray[]为压力数组（Y轴）。注数组以字符串表示，元素间以“, 、;:"”,间隔。

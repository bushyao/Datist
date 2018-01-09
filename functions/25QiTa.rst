.. _QiTa:
其它
======================

@Fields
~~~~~~~~~~~~~~~~~~
操作符： **@Fields**
|返回值：Any
|说明：用在“替换节点”的条件中，代表任意字段名。

GetAddressByIdCard
~~~~~~~~~~~~~~~~~~
函数体： **GetAddressByIdCard(string)**
|返回值：String
|说明：从居民身份证号码中获取归属地。

函数体： **GetAddressByIdCard(string,int)**
|返回值：String
|说明：从居民身份证号码中获取归属地。int为输出内容标识符：1为省名，2为市名，3为县名，4为省名+市名，5为省名+市名+县名，6为省名|市名|县名

GetAddressNumByIdCard
~~~~~~~~~~~~~~~~~~
函数体： **GetAddressNumByIdCard(string)**
|返回值：String
|说明：从居民身份证号码中获取归属地编码。

GetAgeByIdCard
~~~~~~~~~~~~~~~~~~
函数体： **GetAgeByIdCard(string)**
|返回值：Integer
|说明：从居民身份证号码中获取年龄信息。

GetBirthdayByIdCard
~~~~~~~~~~~~~~~~~~
函数体： **GetBirthdayByIdCard(string)**
|返回值：DateTime
|说明：从居民身份证号码中取生日。

GetSexByIdCard
~~~~~~~~~~~~~~~~~~
函数体： **GetSexByIdCard(string)**
|返回值：String
|说明：从居民身份证号码中获取性别信息。

GUIDParse
~~~~~~~~~~~~~~~~~~
函数体： **GUIDParse(String)**
|返回值：GUID
|说明：将文本转换为GUID值。

IsIdCard
~~~~~~~~~~~~~~~~~~
函数体： **IsIdCard(string)**
|返回值：Boolean
|说明：判断字符串是否为居民身份证。

NewGUID
~~~~~~~~~~~~~~~~~~
函数体： **NewGUID( )**
|返回值：GUID
|说明：返回一个随机生成GUID。

函数体： **NewGUID(String)**
|返回值：GUID
|说明：根据所提供的格式说明符，返回一个随机生成GUID,参数可以是“N”、“D”、“B”、“P”；其中：N有连续符‘-’，D有连续符，B带大括号，P带小括号。

XPath
~~~~~~~~~~~~~~~~~~
函数体： **XPath(docString, quertString)**
|返回值：String
|说明：Will evaluate an XPath expression against text that is assumed to be XML, and will return the results.

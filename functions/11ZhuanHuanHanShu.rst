.. _ZhuanHuanHanShu:
转换函数
======================

Base642Byte
~~~~~~~~~~~~~~~~~~
函数体：Base642Byte(String)

返回值：Byte[]

说明：将Base64字符串转化为Byte[]。

Base642String
~~~~~~~~~~~~~~~~~~
函数体：Base642String(String)

返回值：String

说明：将Base64格式转化为字符串。

Byte2Base64
~~~~~~~~~~~~~~~~~~
函数体：Byte2Base64(Byte[])

返回值：String

说明：将Byte[]转化为Base64字符串。

Compress
~~~~~~~~~~~~~~~~~~
函数体：Compress(byte[])

返回值：Byte[]

说明：采用ZIP方法，压缩基础流。

Data2Base64
~~~~~~~~~~~~~~~~~~
函数体：Data2Base64(Byte[],streamtype)

返回值：String

说明：将Byte[]文件转化为Base64字符串（Data URI scheme），streamtype为文件扩展名，如data:image/png;base64,iVBORw0K

Decompress
~~~~~~~~~~~~~~~~~~
函数体：Decompress(byte[])

返回值：Byte[]

说明：采用ZIP方法，解压基础流。

Decrypt
~~~~~~~~~~~~~~~~~~
函数体：Decrypt(byte[],byte[])

返回值：Byte[]

说明：解密

Encrypt
~~~~~~~~~~~~~~~~~~
函数体：Encrypt(byte[],byte[])

返回值：Byte[]

说明：加密

F
~~~~~~~~~~~~~~~~~~
函数体：F(FormatString)

返回值：String

说明：Format函数的简化版，用 {变量:格式} 代替原有的{0}占位方式，如：F('{列1:F2} {列2:N1}') 用法可参考C#的$格式化函数

Format
~~~~~~~~~~~~~~~~~~
函数体：Format(FormatString,Item1,Item2...)

返回值：String

说明：将指定Item转换为字符串。如：Format( "{0} 井 {1:yyyy-MM-dd}~{2:MM-dd} 生产曲线" ,Xi33,2013-5-1,2013-7-1)

GetNumber
~~~~~~~~~~~~~~~~~~
函数体：GetNumber(String)

返回值：String

说明：提取字符串中第1个整数或实数。

函数体：GetNumber(String,Index)

返回值：String

说明：提取字符串中的数值，整数或实数。其中Index整数，表示第Index个数值。

函数体：GetNumber(String,Index,NegativeNumber,RealNumber)

返回值：String

说明：提取字符串中的数值，整数或实数。其中其中Index整数，表示第Index个数值；NegativeNumber布尔型，是否支持负数；RealNumber布尔型，是否支持实数。

GetNumbers
~~~~~~~~~~~~~~~~~~
函数体：GetNumbers(String)

返回值：String

说明：提取字符串中的所有数值，整数或实数

函数体：GetNumbers(String,NegativeNumber,RealNumber)

返回值：String

说明：提取字符串中的数值，整数或实数。其中NegativeNumber布尔型，是否支持负数；RealNumber布尔型，是否支持实数。

HexDecode
~~~~~~~~~~~~~~~~~~
函数体：HexDecode( String )

返回值：Byte[]

说明：Decodes a string of hex characters to their underlying binary format

HexEncode
~~~~~~~~~~~~~~~~~~
函数体：HexEncode( byte[] )

返回值：String

说明：Encodes a bit of binary data as a string of hex characters

String2Base64
~~~~~~~~~~~~~~~~~~
函数体：String2Base64(String)

返回值：String

说明：将字符串转化为Base64格式。

ToBool
~~~~~~~~~~~~~~~~~~
函数体：ToBool(Item)

返回值：Boolean

说明：将指定Item转换为布尔型；真值：True、不为零的整数或实数；假值：False、0、0.0。

ToDoublelist
~~~~~~~~~~~~~~~~~~
函数体：ToDoublelist(String)

返回值：List

说明：将字符串转化为实数列表，以, 。、;:"分隔，转换过程中将删除空值组元,同：ToDoublelist(String,true)

函数体：ToDoublelist(String,Boolean)

返回值：List

说明：将字符串转化为实数列表，以, 。、;:"分隔；Boolean指定是否删除空值组元。

函数体：ToDoublelist(String,Boolean,SplitChars)

返回值：List

说明：将字符串转化为实数列表，组元以SplitChars指定的字符分隔；Boolean指定是否删除空值组元。

ToFieldname
~~~~~~~~~~~~~~~~~~
函数体：ToFieldname(Item)

返回值：String

说明：将指定Item标准化为系统支持的字段名称。

ToInteger
~~~~~~~~~~~~~~~~~~
函数体：ToInteger(Item)

返回值：Integer

说明：将指定Item转换为整数。

ToIntegerlist
~~~~~~~~~~~~~~~~~~
函数体：ToIntegerlist(String)

返回值：List

说明：将字符串转化为整数列表，以, 。、;:"分隔，转换过程中将删除空值组元,同：ToIntegerlist(String,true)

函数体：ToIntegerlist(String,Boolean)

返回值：List

说明：将字符串转化为整数列表，以, 。、;:"分隔；Boolean指定是否删除空值组元。

函数体：ToIntegerlist(String,Boolean,SplitChars)

返回值：List

说明：将字符串转化为整数列表，组元以SplitChars指定的字符分隔；Boolean指定是否删除空值组元。

ToList
~~~~~~~~~~~~~~~~~~
函数体：ToList(Itme1,Itme2...)

返回值：List

说明：构造列表

ToReal
~~~~~~~~~~~~~~~~~~
函数体：ToReal(Item)

返回值：Double

说明：将指定Item转换为实数，小数据精度为6位。

ToString
~~~~~~~~~~~~~~~~~~
函数体：ToString(Item)

返回值：String

说明：将指定Item转换为字符串。

函数体：ToString(Item,Integer)

返回值：String

说明：将指定Item转换为字符串,保留Integer位数。

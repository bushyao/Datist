.. _WenJianXiangGuan:
文件相关
======================

Base642String
~~~~~~~~~~~~~~~~~~
函数体：Base642String(String,string Encoding)

返回值：String

说明：将Base64格式转化为字符串，Encoding定义编码，支持：Default，ASCII，BigEndianUnicode，UTF32，UTF7，UTF8,UTF8_NO_BOM和Unicode。

Byte2String
~~~~~~~~~~~~~~~~~~
函数体：Byte2String(Byte[])

返回值：String

说明：将Byte数组转化为字符串，编码为Default

函数体：Byte2String(Byte[],string Encoding)

返回值：String

说明：将Byte数组转化为字符串，Encoding定义编码，支持：Default，ASCII，BigEndianUnicode，UTF32，UTF7，UTF8,UTF8_NO_BOM和Unicode。

CRC32
~~~~~~~~~~~~~~~~~~
函数体：CRC32(byte[])

返回值：String

说明：Works on binary data, will calculate a 32bit CRC

FileStream
~~~~~~~~~~~~~~~~~~
函数体：FileStream(FileName)

返回值：Byte[]

说明：将文件加载到流程中。

GetDirectoryName
~~~~~~~~~~~~~~~~~~
函数体：GetDirectoryName(String FileName)

返回值：String

说明：返回文件路径，FileName为文件的路径。

函数体：GetDirectoryName(String FileName,Int Level)

返回值：String

说明：返回指层级的目录名称，FileName为文件的路径; Level指定返回第几层的目录名称，正值为从前向后，负值为从后向前。

GetExtension
~~~~~~~~~~~~~~~~~~
函数体：GetExtension(FileName)

返回值：String

说明：返回文件的扩展名，FileName为文件的路径。

GetFileEncodeType
~~~~~~~~~~~~~~~~~~
函数体：GetFileEncodeType(File)

返回值：Byte[]

说明：获文件的编码方式，参数File，可为文件数据体，可为文件路径。

GetFileName
~~~~~~~~~~~~~~~~~~
函数体：GetFileName(FileName)

返回值：String

说明：返回文件名，FileName为文件的路径。

GetFileNameWithoutExtension
~~~~~~~~~~~~~~~~~~
函数体：GetFileNameWithoutExtension(FileName)

返回值：String

说明：返回不含扩展名的文件名，FileName为文件的路径。

MD5
~~~~~~~~~~~~~~~~~~
函数体：MD5(byte[])

返回值：String

说明：Creates a MD5 hash on binary data

RemoveInvalidFileNameChars
~~~~~~~~~~~~~~~~~~
函数体：RemoveInvalidFileNameChars(FileName)

返回值：String

说明：删除文件名中，非法字符。

RIPEMD160
~~~~~~~~~~~~~~~~~~
函数体：RIPEMD160(byte[])

返回值：String

说明：Creates a RIPEMD160 hash on binary data

SHA1
~~~~~~~~~~~~~~~~~~
函数体：SHA1(byte[])

返回值：String

说明：Creates a SHA1 hash on binary data

SHA256
~~~~~~~~~~~~~~~~~~
函数体：SHA256(byte[])

返回值：String

说明：Creates a SHA2 hash on binary data

SHA384
~~~~~~~~~~~~~~~~~~
函数体：SHA384(byte[])

返回值：String

说明：Creates a SHA256 hash on binary data

SHA512
~~~~~~~~~~~~~~~~~~
函数体：SHA512(byte[])

返回值：String

说明：Creates a SHA512 hash on binary data

String2Base64
~~~~~~~~~~~~~~~~~~
函数体：String2Base64(String,string Encoding)

返回值：String

说明：将字符串转化为Base64格式，Encoding定义编码，支持：Default，ASCII，BigEndianUnicode，UTF32，UTF7，UTF8,UTF8_NO_BOM和Unicode。

String2Byte
~~~~~~~~~~~~~~~~~~
函数体：String2Byte(String)

返回值：Byte[]

说明：将字符串转化为Byte数组，编码为Default

函数体：String2Byte(String,string Encoding)

返回值：Byte[]

说明：将字符串转化为Byte数组，Encoding定义编码，支持：Default，ASCII，BigEndianUnicode，UTF32，UTF7，UTF8和Unicode。

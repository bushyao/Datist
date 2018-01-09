.. _XinXiHanShu:
信息函数
======================

GetChinese(Item)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：获取字符串中的所有中文。

IsAlpha(Item)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：Item全为字母返回真值。

IsChinese(Item)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：Item全为汉字返回真值。

IsDatetime(Item)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判断文本是否为指定格式的日期与时间。

IsDatetime(Item,DateTimeFormat)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判断文本是否为指定格式的日期与时间，DateTimeFormat为日期格式：(年-月-日 时:分:秒.毫秒) yyyy-MM-dd HH:mm:ss （HH为24小时制，hh为12小时制）。

IsDatetime(Item,DateTimeFormatList,SplitChar)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判断文本是否为指定格式的日期与时间，DateTimeFormatList为日期格式列表：(年-月-日 时:分:秒.毫秒) yyyy-MM-dd HH:mm:ss （HH为24小时制，hh为12小时制）；SplitChar为格式列表的分隔字符。

IsDBNull(Item)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：空值判断，如果表达式Item的值为空，返回真（1），否则返回假（0）。

IsInteger(Item)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：Item为整数返回真值。

IsNOTDBNull(Item)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：非空值判断，如果表达式Item的值为非空值，返回真（1），否则返回假（0）。

IsNotNullOrWhiteSpace(Item)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：非空值和非空格判断，如果表达式Item的值为非空、非空格，返回真（1），否则返回假（0）。

IsNullOrWhiteSpace(Item)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：非空值和非空格判断，如果表达式Item的值为空、空格，返回真（1），否则返回假（0）。

IsNumber(Item)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：Item为数值返回真值。

IsReal(Item)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：Item为实数返回真值。

null
~~~~~~~~~~~~~~~~~~
返回值：null

说明：空。

RemoveChinese(Item)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除字符串中的所有中文。

typeof(ITEM)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回函数参数数据类型的字符串表示形式，如"integer、text、real、null"等。

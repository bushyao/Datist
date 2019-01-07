.. _RiQiYuShiJian:
日期与时间
======================

CENCToDate
~~~~~~~~~~~~~~~~~~
函数体： **CENCToDate(Double)**

返回值：DateTime

说明：将一个地震日期编号转换为日期。

CreateDate
~~~~~~~~~~~~~~~~~~
函数体： **CreateDate(Year,Month,Day)**

返回值：DateTime

说明：返回指定Year，Month和Day的时间值，参数必须为整数。

CreateDatetime
~~~~~~~~~~~~~~~~~~
函数体： **CreateDatetime(Year,Month,Day,Hour,Minute,Second)**

返回值：DateTime

说明：返回指定Year，Month，Day，Hour，Minute和Second 的时间值。

CreateTime
~~~~~~~~~~~~~~~~~~
函数体： **CreateTime(Hour,Minute,Second)**

返回值：DateTime

说明：返回指定Hour，Minute和Second 的时间值。

CreateTimeSpan
~~~~~~~~~~~~~~~~~~
函数体： **CreateTimeSpan(hours,minutes,seconds)**

返回值：TimeSpan

说明：返回指定的时间间隔。

函数体： **CreateTimeSpan(days,hours,minutes,seconds)**

返回值：TimeSpan

说明：返回指定的时间间隔。

函数体： **CreateTimeSpan(days,hours,minutes,seconds,milliseconds)**

返回值：TimeSpan

说明：返回指定的时间间隔。

DateAfter
~~~~~~~~~~~~~~~~~~
函数体： **DateAfter(Datetime,BaseDatetime)**

返回值：Boolean

说明：Datetime 在 BaseDatetime之后，则返回真值，否则，此函数的返回结果为假值；如果Datetime,BaseDatetime非标准的日期格式，返回空。

DateBefore
~~~~~~~~~~~~~~~~~~
函数体： **DateBefore(Datetime,BaseDatetime)**

返回值：Boolean

说明：Datetime在BaseDatetime之前，则返回真值，否则，此函数的返回结果为假值；如果Datetime,BaseDatetime非标准的日期格式，返回空。

DateDiff
~~~~~~~~~~~~~~~~~~
函数体： **DateDiff(interval,startDatetime,endDatetime)**

返回值：double

说明：求两个指定日期间的时间间隔数目。

其中时间startDatetime,endDatetime格式，参见DateTime2函数。

必选参数interval,为字符串表达式，设定时间差的时间的间隔。

参数的设定值为：年，y，季，q，月，m，周，w，天，d，时，h，分，mi，秒，s，毫秒，ms

如：DateDiff('月','2017-10-10','2018-11-30')

DateTime2
~~~~~~~~~~~~~~~~~~
函数体： **DateTime2(datetime, modifier, modifier, …)**

返回值：DateTime

说明：对输入时间datetime，按modifier调整后，输出日期字符串'yyyy-MM-dd HH:mm:ss.fff'。

其中datetime是必须的，modifier为可选项。

datetime的支持格式字符串：

  1.yyyy-MM-dd

  2.yyyy-MM-dd HH:mm

  3.yyyy-MM-dd HH:mm:ss

  4.yyyy-MM-dd HH:mm:ss.fff

  5.yyyy-MM-ddTHH:mm  其中T是日期和时间分割符

  6.yyyy-MM-ddTHH:mm:ss

  7.yyyy-MM-ddTHH:mm:ss.fff

  8.HH:mm

  9.HH:mm:ss

  10.HH:mm:ss.fff

  11.now

修正参数modifier可有可无，如果有多个修正参数，按从左到右原则依次修正，而且后修正参数是基于前修正参数据结果的再次修正。支持修正字符串有两类：

  1.加减时间类，格式：±N m，其中m可为：年，y，月，m，天，d，时，h，分，mi，秒，s，毫秒，ms

  2.取特定时间类，支持：年初，年末，季初，季末，月初，月末，Nth周，周一，周二，周三，周四，周五，周六，周日

    其中Nth周，表示当年的第N周的周一，如Datetime2('2018-11-30','5周')，输出 2018-01-29 00:00:00.000

如：Datetime2('2018-11-30','4d','周一')，输出 2018-12-03 00:00:00.000

DateTime3
~~~~~~~~~~~~~~~~~~
函数体： **DateTime3(format, datetime, modifier, modifier, …)**

返回值：string

说明：对输入时间datetime，按modifier调整后，以format的格式输出，功能与DateTime2函数相近。

其中format和datetime是必须的，modifier为可选项。

参数datetime, modifier格式，参见DateTime2函数。

format定义输出日期的格式。下面列出了可被合并以构造自定义模式的模式，这些模式是区分大小写的：

  gg 时期或纪元。如果要设置格式的日期不具有关联的时期或纪元字符串，则忽略该模式。

  y 不包含纪元的年份。如果不包含纪元的年份小于 10，则显示不具有前导零的年份。

  yy 不包含纪元的年份。如果不包含纪元的年份小于 10，则显示具有前导零的年份。

  yyyy 包括纪元的四位数的年份。

  M 月份数字。一位数的月份没有前导零。

  MM 月份数字。一位数的月份有一个前导零。

  MMM 月份的缩写名称，如：1月、2月、3月、4月、5月、6月、7月、8月、9月、10月、11月、12月。

  MMMM 月份的完整名称，如：一月、二月、三月、四月、五月、六月、七月、八月、九月、十月、十一月、十二月。

  d 月中的某一天。一位数的日期没有前导零。

  dd 月中的某一天。一位数的日期有一个前导零。

  ddd 周中某天的缩写名称，如：周日、周一、周二、周三、周四、周五、周六。

  dddd 周中某天的完整名称，如：星期日、星期一、星期二、星期三、星期四、星期五、星期六。

  h 12 小时制的小时。一位数的小时数没有前导零。

  hh 12 小时制的小时。一位数的小时数有前导零。

  H 24 小时制的小时。一位数的小时数没有前导零。

  HH 24 小时制的小时。一位数的小时数有前导零。

  m 分钟数字。一位数的分钟数没有前导零。

  mm 分钟数字。一位数的分钟数有前导零。

  s 秒数字。一位数的秒数没有前导零。

  ss 秒数字。一位数的秒数有前导零。

  f 毫秒数字。

  j 一年中的第几天，01-366。

  J 儒略日数。

  w 星期数，0-6，0是星期天。

  W 一年中的第几周，00-53。

如：Datetime3('ddd','2018-11-30')，输出 周五

DatetimeEqual
~~~~~~~~~~~~~~~~~~
函数体： **DatetimeEqual(Datetime1,Datetime2)**

返回值：Boolean

说明：两个时间比较，相等为真，不相等为否。

From_UnixTime
~~~~~~~~~~~~~~~~~~
函数体： **From_UnixTime(Int)**

返回值：DateTime

说明：将Unix时间转换为日期。

JulianToDate
~~~~~~~~~~~~~~~~~~
函数体： **JulianToDate(Double)**

返回值：DateTime

说明：将儒略日转换为日期，以1970-01-01 0:0:0.0为基数。

MondayByWeekNo
~~~~~~~~~~~~~~~~~~
函数体： **MondayByWeekNo(Integer year,Integer weekNo)**

返回值：DateTime

说明：获取指定年度第几星期的星期一对应用的日期。

Now
~~~~~~~~~~~~~~~~~~
函数体： **Now()**

返回值：String

说明：取当前系统的年月日时分秒

TimeAfter
~~~~~~~~~~~~~~~~~~
函数体： **TimeAfter(Time,BaseTime)**

返回值：Boolean

说明：Time在BaseTime之后，则返回真值，否则，此函数的返回结果为假值；如果Time,BaseTime非标准的日期格式，返回空。

TimeBefore
~~~~~~~~~~~~~~~~~~
函数体： **TimeBefore(Time,BaseTime)**

返回值：Boolean

说明：Time在BaseTime之前，则返回真值，否则，此函数的返回结果为假值；如果Time,BaseTime非标准的日期格式，返回空。

To_UnixTime
~~~~~~~~~~~~~~~~~~
函数体： **To_UnixTime(DateTime)**

返回值：Integer

说明：将日期转换为Unix时间，从公元1970年1月1日的UTC时间从0时0分0秒算起到现在所经过的秒数。

ToCENCDate
~~~~~~~~~~~~~~~~~~
函数体： **ToCENCDate(DateTime)**

返回值：Double

说明：将一个日期转换为地震日期编号。

ToChineseCalendar
~~~~~~~~~~~~~~~~~~
函数体： **ToChineseCalendar(DateTime,Type)**

返回值：String

说明：将日期转化农历。返回Type指定类型的日期,1:阳历日期;2:农历日期;3:星期;4:时辰;5:属相;6:节气;7:前一个节气;8:下一个节气;9:节日;10:干支;11:星宿;12:星座

ToDatetime
~~~~~~~~~~~~~~~~~~
函数体： **ToDatetime(string)**

返回值：DateTime

说明：将文本转化为日期与时间，支持通用日期与时间格式。

函数体： **ToDatetime(string,DateTimeFormat)**

返回值：DateTime

说明：将文本转化为日期与时间，支持通用日期与时间格式。DateTimeFormat的参考格式：(年-月-日 时:分:秒.毫秒) yyyy-MM-dd HH:mm:ss（HH为24小时制，hh为12小时制）。

函数体： **ToDatetime(string,DateTimeFormatList,SplitChar)**

返回值：DateTime

说明：将文本转化为日期与时间，支持通用日期与时间格式，SplitChar为格式列表的分隔字符。DateTimeFormatList的参考格式列表：(年-月-日 时:分:秒.毫秒) yyyy-MM-dd HH:mm:ss（HH为24小时制，hh为12小时制）。

ToJulianDate
~~~~~~~~~~~~~~~~~~
函数体： **ToJulianDate(DateTime)**

返回值：Double

说明：将一个日期转换为儒略日，以1970-01-01 0:0:0.0为基数。

ToOAdate
~~~~~~~~~~~~~~~~~~
函数体： **ToOAdate(DateTime)**

返回值：Double

说明：将一个日期型的字符串转化(格式为yyyy-MM-dd HH:mm:ss 例如2010-01-01 5:11:33 )为等效的 OLE 自动化日期，返回一个双精度浮点数，它包含与此实例的值等效的 OLE 自动化日期。

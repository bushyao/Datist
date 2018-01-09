.. _RiQiYuShiJian:
日期与时间
======================

AddDays
~~~~~~~~~~~~~~~~~~
函数体：AddDays(Datetime,Real)

返回值：DateTime

说明：将指定的天数加到Datetime上，Integer参数可以是负数也可以是正数。

AddHours
~~~~~~~~~~~~~~~~~~
函数体：AddHours(Datetime,Real)

返回值：DateTime

说明：将指定的小时数加到Datetime上，Integer参数可以是负数也可以是正数。

AddMilliseconds
~~~~~~~~~~~~~~~~~~
函数体：AddMilliseconds(Datetime,Real)

返回值：DateTime

说明：将指定的毫秒数加到Datetime上，Integer参数可以是负数也可以是正数。

AddMinutes
~~~~~~~~~~~~~~~~~~
函数体：AddMinutes(Datetime,Real)

返回值：DateTime

说明：将指定的分钟数加到Datetime上，Integer参数可以是负数也可以是正数。

AddMonths
~~~~~~~~~~~~~~~~~~
函数体：AddMonths(Datetime,Integer)

返回值：DateTime

说明：将指定的月份数加到Datetime上，Integer参数可以是负数也可以是正数。

AddSeconds
~~~~~~~~~~~~~~~~~~
函数体：AddSeconds(Datetime,Real)

返回值：DateTime

说明：将指定的秒数加到Datetime上，Integer参数可以是负数也可以是正数。

AddYears
~~~~~~~~~~~~~~~~~~
函数体：AddYears(Datetime,Integer)

返回值：DateTime

说明：将指定的年份数加到Datetime上，Integer参数可以是负数也可以是正数。

CENCToDate
~~~~~~~~~~~~~~~~~~
函数体：CENCToDate(Double)

返回值：DateTime

说明：将一个地震日期编号转换为日期。

CreateDate
~~~~~~~~~~~~~~~~~~
函数体：CreateDate(Year,Month,Day)

返回值：DateTime

说明：返回指定Year，Month和Day的时间值，参数必须为整数。

CreateDatetime
~~~~~~~~~~~~~~~~~~
函数体：CreateDatetime(Year,Month,Day,Hour,Minute,Second)

返回值：DateTime

说明：返回指定Year，Month，Day，Hour，Minute和Second 的时间值。

CreateTime
~~~~~~~~~~~~~~~~~~
函数体：CreateTime(Hour,Minute,Second)

返回值：DateTime

说明：返回指定Hour，Minute和Second 的时间值。

CreateTimeSpan
~~~~~~~~~~~~~~~~~~
函数体：CreateTimeSpan(days,hours,minutes,seconds)

返回值：TimeSpan

说明：返回指定的时间间隔。

函数体：CreateTimeSpan(days,hours,minutes,seconds,milliseconds)

返回值：TimeSpan

说明：返回指定的时间间隔。

函数体：CreateTimeSpan(hours,minutes,seconds)

返回值：TimeSpan

说明：返回指定的时间间隔。

DateAfter
~~~~~~~~~~~~~~~~~~
函数体：DateAfter(Datetime,BaseDatetime)

返回值：Boolean

说明：Datetime 在 BaseDatetime之后，则返回真值，否则，此函数的返回结果为假值；如果Datetime,BaseDatetime非标准的日期格式，返回空。

DateBefore
~~~~~~~~~~~~~~~~~~
函数体：DateBefore(Datetime,BaseDatetime)

返回值：Boolean

说明：Datetime在BaseDatetime之前，则返回真值，否则，此函数的返回结果为假值；如果Datetime,BaseDatetime非标准的日期格式，返回空。

DatetimeDifference
~~~~~~~~~~~~~~~~~~
函数体：DatetimeDifference(BaseDateTime，Datetime)

返回值：TimeSpan

说明：返回Datetime-BaseDateTime的时间间隔。

DatetimeEqual
~~~~~~~~~~~~~~~~~~
函数体：DatetimeEqual(Datetime1,Datetime2)

返回值：Boolean

说明：两个时间比较，相等为真，不相等为否。

Day
~~~~~~~~~~~~~~~~~~
函数体：Day()

返回值：String

说明：取当前日

函数体：Day(Datetime)

返回值：Integer

说明：返回Datetime的天部分。返回结果为1 到31 之间的整数。

DayOfMonth
~~~~~~~~~~~~~~~~~~
函数体：DayOfMonth(Datetime)

返回值：Integer

说明：获取日期为该月中的第几天。

DayOfWeek
~~~~~~~~~~~~~~~~~~
函数体：DayOfWeek(Datetime)

返回值：Integer

说明：表示的日期是星期几,返回结果为0 到6之间的整数。

DayOfWeek_cn
~~~~~~~~~~~~~~~~~~
函数体：DayOfWeek_cn(Datetime)

返回值：String

说明：表示的日期是星期几,返回结果为星期日,星期一,星期二,星期三,星期四,星期五,星期六。

DayOfWeek_en
~~~~~~~~~~~~~~~~~~
函数体：DayOfWeek_en(Datetime)

返回值：String

说明：表示的日期是星期几,返回结果为Sunday,Monday,Tuesday,Wednesday,Thursday,Friday,Saturday。

DayOfWeek_en_short
~~~~~~~~~~~~~~~~~~
函数体：DayOfWeek_en_short(Datetime)

返回值：String

说明：表示的日期是星期几,返回结果为Sun, Mon, Tue, Wed, Thu, Fri, Sat。

DayOfYear
~~~~~~~~~~~~~~~~~~
函数体：DayOfYear(Datetime)

返回值：Integer

说明：获取指定日期是该年中的第几天。

DaysDifference
~~~~~~~~~~~~~~~~~~
函数体：DaysDifference(BaseDateTime，Datetime)

返回值：Double

说明：以小数的形式返回从日期BaseDateTime到日期Datetime的天数。如果Datetime在BaseDateTime之前，则该函数返回负值。

FirstDayOfMonth
~~~~~~~~~~~~~~~~~~
函数体：FirstDayOfMonth(Datetime)

返回值：DateTime

说明：获取指定日期所在月份第一天。

FirstDayOfNextMonth
~~~~~~~~~~~~~~~~~~
函数体：FirstDayOfNextMonth(Datetime)

返回值：DateTime

说明：获取指定日期的下个月第一天。

FirstDayOfNextQuarter
~~~~~~~~~~~~~~~~~~
函数体：FirstDayOfNextQuarter(Datetime)

返回值：DateTime

说明：获取指定日期的下一季度第一天。

FirstDayOfNextYear
~~~~~~~~~~~~~~~~~~
函数体：FirstDayOfNextYear(Datetime)

返回值：DateTime

说明：获取指定日期的下一年第一天。

FirstDayOfPreviousMonth
~~~~~~~~~~~~~~~~~~
函数体：FirstDayOfPreviousMonth(Datetime)

返回值：DateTime

说明：获取指定日期的上个月第一天。

FirstDayOfPreviousQuarter
~~~~~~~~~~~~~~~~~~
函数体：FirstDayOfPreviousQuarter(Datetime)

返回值：DateTime

说明：获取指定日期的上一季度第一天。

FirstDayOfPreviousYear
~~~~~~~~~~~~~~~~~~
函数体：FirstDayOfPreviousYear(Datetime)

返回值：DateTime

说明：获取指定日期的上一年第一天。

FirstDayOfQuarter
~~~~~~~~~~~~~~~~~~
函数体：FirstDayOfQuarter(Datetime)

返回值：DateTime

说明：获取指定日期所在季度份第一天。

FirstDayOfYear
~~~~~~~~~~~~~~~~~~
函数体：FirstDayOfYear(Datetime)

返回值：DateTime

说明：获取指定日期所在年份第一天。

format_DateTime
~~~~~~~~~~~~~~~~~~
函数体：format_DateTime(DateTime,DateTimeFormat)

返回值：String

说明：将日期与时间转化为指定格式的文本，DateTimeFormat为日期格式：(年-月-日 时:分:秒.毫秒) yyyy-MM-dd HH:mm:ss（HH为24小时制，hh为12小时制）。

Format_TimeSpan
~~~~~~~~~~~~~~~~~~
函数体：Format_TimeSpan(TimeSpan)

返回值：String

说明：将时间间隔转化为指定格式的文本。

函数体：Format_TimeSpan(TimeSpan,TimeSpanFormat)

返回值：String

说明：将时间间隔转化为指定格式的文本，TimeSpanFormat为格式：dd\天hh\时mm\分ss\秒，注意反斜杠。

FridayOfNextWeek
~~~~~~~~~~~~~~~~~~
函数体：FridayOfNextWeek(DateTime)

返回值：DateTime

说明：计算指定日期下周的星期五对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

FridayOfPreviousWeek
~~~~~~~~~~~~~~~~~~
函数体：FridayOfPreviousWeek(DateTime)

返回值：DateTime

说明：计算指定日期上周的星期五对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

FridayOfWeek
~~~~~~~~~~~~~~~~~~
函数体：FridayOfWeek(DateTime)

返回值：DateTime

说明：计算指定日期本周的星期五对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

From_UnixTime
~~~~~~~~~~~~~~~~~~
函数体：From_UnixTime(Int)

返回值：DateTime

说明：将Unix时间转换为日期。

Hour
~~~~~~~~~~~~~~~~~~
函数体：Hour()

返回值：String

说明：取当前时

函数体：Hour(Datetime)

返回值：Integer

说明：返回Datetime的小时部分。返回结果为0 至23 之间的整数。

HoursDifference
~~~~~~~~~~~~~~~~~~
函数体：HoursDifference(BasedDatetime,Datetime)

返回值：Double

说明：以小数的形式返回从日期BasedDatetime到日期Datetime的小时数。如果Datetime在BasedDatetime之前，则该函数返回负值。

JulianToDate
~~~~~~~~~~~~~~~~~~
函数体：JulianToDate(Double)

返回值：DateTime

说明：将儒略日转换为日期，以1970-01-01 0:0:0.0为基数。

LastDayOfMonth
~~~~~~~~~~~~~~~~~~
函数体：LastDayOfMonth(Datetime)

返回值：DateTime

说明：获取指定日期所在月份最后一天。

LastDayOfNextMonth
~~~~~~~~~~~~~~~~~~
函数体：LastDayOfNextMonth(Datetime)

返回值：DateTime

说明：获取指定日期的下个月的最后一天。

LastDayOfNextQuarter
~~~~~~~~~~~~~~~~~~
函数体：LastDayOfNextQuarter(Datetime)

返回值：DateTime

说明：获取指定日期的下一季度的最后一天。

LastDayOfNextYear
~~~~~~~~~~~~~~~~~~
函数体：LastDayOfNextYear(Datetime)

返回值：DateTime

说明：获取指定日期的下一年的最后一天。

LastDayOfPrdviousMonth
~~~~~~~~~~~~~~~~~~
函数体：LastDayOfPrdviousMonth(Datetime)

返回值：DateTime

说明：获取指定日期的上个月的最后一天。

LastDayOfPrdviousQuarter
~~~~~~~~~~~~~~~~~~
函数体：LastDayOfPrdviousQuarter(Datetime)

返回值：DateTime

说明：获取指定日期的上一季度的最后一天。

LastDayOfPrdviousYear
~~~~~~~~~~~~~~~~~~
函数体：LastDayOfPrdviousYear(Datetime)

返回值：DateTime

说明：获取指定日期的上一年的最后一天。

LastDayOfQuarter
~~~~~~~~~~~~~~~~~~
函数体：LastDayOfQuarter(Datetime)

返回值：DateTime

说明：获取指定日期所在季度份最后一天。

LastDayOfYear
~~~~~~~~~~~~~~~~~~
函数体：LastDayOfYear(Datetime)

返回值：DateTime

说明：获取指定日期所在年份最后一天。

Millisecond
~~~~~~~~~~~~~~~~~~
函数体：Millisecond()

返回值：String

说明：取当前毫秒

Milliseconds
~~~~~~~~~~~~~~~~~~
函数体：Milliseconds(Datetime)

返回值：Integer

说明：返回Datetime的毫秒钟部分。返回结果为0到999之间的整数。

MillisecondsDifference
~~~~~~~~~~~~~~~~~~
函数体：MillisecondsDifference(BaseDatetime,Datetime)

返回值：Double

说明：以小数的形式返回从日期BaseDatetime到日期Datetime的毫秒数。如果Datetime在BaseDatetime之前，则该函数返回负值。

Minute
~~~~~~~~~~~~~~~~~~
函数体：Minute()

返回值：String

说明：取当前分

函数体：Minute(Datetime)

返回值：Integer

说明：返回Datetime的分钟部分。返回结果为0 到59 之间的整数。

MinutesDifference
~~~~~~~~~~~~~~~~~~
函数体：MinutesDifference(BaseDatetime,Datetime)

返回值：Double

说明：以小数的形式返回从日期BaseDatetime到日期Datetime的分钟数。如果Datetime在BaseDatetime之前，则该函数返回负值。

MondayByWeekNo
~~~~~~~~~~~~~~~~~~
函数体：MondayByWeekNo(Integer year,Integer weekNo)

返回值：DateTime

说明：获取指定年度第几星期的星期一对应用的日期。

MondayOfNextWeek
~~~~~~~~~~~~~~~~~~
函数体：MondayOfNextWeek(DateTime)

返回值：DateTime

说明：计算指定日期下周的星期一对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

MondayOfPreviousWeek
~~~~~~~~~~~~~~~~~~
函数体：MondayOfPreviousWeek(DateTime)

返回值：DateTime

说明：计算指定日期上周的星期一对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

MondayOfWeek
~~~~~~~~~~~~~~~~~~
函数体：MondayOfWeek(DateTime)

返回值：DateTime

说明：计算指定日期本周的星期一对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

Month
~~~~~~~~~~~~~~~~~~
函数体：Month()

返回值：String

说明：取当前月

函数体：Month(Datetime)

返回值：Integer

说明：返回Datetime的月份部分。返回结果为1 到12 之间的整数。

Month_cn
~~~~~~~~~~~~~~~~~~
函数体：Month_cn(Datetime)

返回值：String

说明：返回Datetime的月份部分。返回结果为一月、二月、三月、四月、五月、六月、七月、八月、九月、十月、十一月、十二月。

Month_en
~~~~~~~~~~~~~~~~~~
函数体：Month_en(Datetime)

返回值：String

说明：返回Datetime的月份部分。返回结果为January,February,March,April,May,June,July,August,September,October,November,December。

Month_en_short
~~~~~~~~~~~~~~~~~~
函数体：Month_en_short(Datetime)

返回值：String

说明：返回Datetime的月份部分。返回结果为Jan,Feb,Mar,Apr,May,Jun,Jul,Aug,Sep,Oct,Nov,Dec。

MonthsDifference
~~~~~~~~~~~~~~~~~~
函数体：MonthsDifference(BaseDatetime,Datetime)

返回值：Double

说明：以小数的形式返回从BaseDatetime到Datetime月数。这是基于每月30.0 天的近似数字。如果Datetime在BaseDatetime之前，则该函数返回负值。

Now
~~~~~~~~~~~~~~~~~~
函数体：Now()

返回值：String

说明：取当前系统的年月日时分秒

SaturdayOfNextWeek
~~~~~~~~~~~~~~~~~~
函数体：SaturdayOfNextWeek(DateTime)

返回值：DateTime

说明：计算指定日期下周的星期六对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

SaturdayOfPreviousWeek
~~~~~~~~~~~~~~~~~~
函数体：SaturdayOfPreviousWeek(DateTime)

返回值：DateTime

说明：计算指定日期上周的星期六对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

SaturdayOfWeek
~~~~~~~~~~~~~~~~~~
函数体：SaturdayOfWeek(DateTime)

返回值：DateTime

说明：计算指定日期本周的星期六对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

Second
~~~~~~~~~~~~~~~~~~
函数体：Second()

返回值：String

说明：取当前秒

函数体：Second(Datetime)

返回值：Integer

说明：返回Datetime的秒钟部分。返回结果为0 到59 之间的整数。

SecondsDifference
~~~~~~~~~~~~~~~~~~
函数体：SecondsDifference(BaseDatetime,Datetime)

返回值：Double

说明：以小数的形式返回从日期BaseDatetime到日期Datetime的秒数。如果Datetime在BaseDatetime之前，则该函数返回负值。

SundayOfNextWeek
~~~~~~~~~~~~~~~~~~
函数体：SundayOfNextWeek(DateTime)

返回值：DateTime

说明：计算指定日期下周的星期日对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

SundayOfPreviousWeek
~~~~~~~~~~~~~~~~~~
函数体：SundayOfPreviousWeek(DateTime)

返回值：DateTime

说明：计算指定日期上周的星期日对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

SundayOfWeek
~~~~~~~~~~~~~~~~~~
函数体：SundayOfWeek(DateTime)

返回值：DateTime

说明：计算指定日期本周的星期日对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

ThursdayOfNextWeek
~~~~~~~~~~~~~~~~~~
函数体：ThursdayOfNextWeek(DateTime)

返回值：DateTime

说明：计算指定日期下周的星期四对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

ThursdayOfPreviousWeek
~~~~~~~~~~~~~~~~~~
函数体：ThursdayOfPreviousWeek(DateTime)

返回值：DateTime

说明：计算指定日期上周的星期四对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

ThursdayOfWeek
~~~~~~~~~~~~~~~~~~
函数体：ThursdayOfWeek(DateTime)

返回值：DateTime

说明：计算指定日期本周的星期四对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

TimeAfter
~~~~~~~~~~~~~~~~~~
函数体：TimeAfter(Time,BaseTime)

返回值：Boolean

说明：Time在BaseTime之后，则返回真值，否则，此函数的返回结果为假值；如果Time,BaseTime非标准的日期格式，返回空。

TimeBefore
~~~~~~~~~~~~~~~~~~
函数体：TimeBefore(Time,BaseTime)

返回值：Boolean

说明：Time在BaseTime之前，则返回真值，否则，此函数的返回结果为假值；如果Time,BaseTime非标准的日期格式，返回空。

TimeHoursDifference
~~~~~~~~~~~~~~~~~~
函数体：TimeHoursDifference(BaseTime,Time)

返回值：Double

说明：以整数的形式返回从日期BaseTime到日期Time的小时数。如果Time在BaseTime之前，则该函数返回负值。

TimeMillisecondsDifference
~~~~~~~~~~~~~~~~~~
函数体：TimeMillisecondsDifference(BaseTime,Time)

返回值：Double

说明：以整数的形式返回从日期BaseTime到日期Time的毫秒数。如果Time在BaseTime之前，则该函数返回负值。

TimeMinutesDifference
~~~~~~~~~~~~~~~~~~
函数体：TimeMinutesDifference(BaseTime,Time)

返回值：Double

说明：以整数的形式返回从日期BaseTime到日期Time的分钟数。如果Time在BaseTime之前，则该函数返回负值。

TimeSecondsDifference
~~~~~~~~~~~~~~~~~~
函数体：TimeSecondsDifference(BaseTime,Time)

返回值：Double

说明：以整数的形式返回从日期BaseTime到日期Time的秒数。如果Time在BaseTime之前，则该函数返回负值。

TimeSpan2HM
~~~~~~~~~~~~~~~~~~
函数体：TimeSpan2HM(TimeSpan)

返回值：String

说明：将时间间隔转换为，总小时数：分钟，如25：50表示25小时50分钟。

To_UnixTime
~~~~~~~~~~~~~~~~~~
函数体：To_UnixTime(DateTime)

返回值：Integer

说明：将日期转换为Unix时间，从公元1970年1月1日的UTC时间从0时0分0秒算起到现在所经过的秒数。

ToCENCDate
~~~~~~~~~~~~~~~~~~
函数体：ToCENCDate(DateTime)

返回值：Double

说明：将一个日期转换为地震日期编号。

ToChineseCalendar
~~~~~~~~~~~~~~~~~~
函数体：ToChineseCalendar(DateTime,Type)

返回值：String

说明：将日期转化农历。返回Type指定类型的日期,1:阳历日期;2:农历日期;3:星期;4:时辰;5:属相;6:节气;7:前一个节气;8:下一个节气;9:节日;10:干支;11:星宿;12:星座

ToDatetime
~~~~~~~~~~~~~~~~~~
函数体：ToDatetime(string)

返回值：DateTime

说明：将文本转化为日期与时间，支持通用日期与时间格式。

函数体：ToDatetime(string,DateTimeFormat)

返回值：DateTime

说明：将文本转化为日期与时间，支持通用日期与时间格式。DateTimeFormat的参考格式：(年-月-日 时:分:秒.毫秒) yyyy-MM-dd HH:mm:ss（HH为24小时制，hh为12小时制）。

函数体：ToDatetime(string,DateTimeFormatList,SplitChar)

返回值：DateTime

说明：将文本转化为日期与时间，支持通用日期与时间格式，SplitChar为格式列表的分隔字符。DateTimeFormatList的参考格式列表：(年-月-日 时:分:秒.毫秒) yyyy-MM-dd HH:mm:ss（HH为24小时制，hh为12小时制）。

ToJulianDate
~~~~~~~~~~~~~~~~~~
函数体：ToJulianDate(DateTime)

返回值：Double

说明：将一个日期转换为儒略日，以1970-01-01 0:0:0.0为基数。

ToOAdate
~~~~~~~~~~~~~~~~~~
函数体：ToOAdate(DateTime)

返回值：Double

说明：将一个日期型的字符串转化(格式为yyyy-MM-dd HH:mm:ss 例如2010-01-01 5:11:33 )为等效的 OLE 自动化日期，返回一个双精度浮点数，它包含与此实例的值等效的 OLE 自动化日期。

toShortDate
~~~~~~~~~~~~~~~~~~
函数体：toShortDate(DateTime)

返回值：String

说明：将日期时间(可为字符串格式)转化为短日期格式,支持常见的日期格式，如2005-11-5 13:47:04，输出2005-11-5。

toShortTime
~~~~~~~~~~~~~~~~~~
函数体：toShortTime(DateTime)

返回值：String

说明：将日期时间(可为字符串格式)转化为短时间格式,支持常见的日期格式，如2005-11-5 13:47:04，输出13:47:04。

TuesdayOfNextWeek
~~~~~~~~~~~~~~~~~~
函数体：TuesdayOfNextWeek(DateTime)

返回值：DateTime

说明：计算指定日期下周的星期二对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

TuesdayOfPreviousWeek
~~~~~~~~~~~~~~~~~~
函数体：TuesdayOfPreviousWeek(DateTime)

返回值：DateTime

说明：计算指定日期上周的星期二对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

TuesdayOfWeek
~~~~~~~~~~~~~~~~~~
函数体：TuesdayOfWeek(DateTime)

返回值：DateTime

说明：计算指定日期本周的星期二对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

WednesdayOfNextWeek
~~~~~~~~~~~~~~~~~~
函数体：WednesdayOfNextWeek(DateTime)

返回值：DateTime

说明：计算指定日期下周的星期三对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

WednesdayOfPreviousWeek
~~~~~~~~~~~~~~~~~~
函数体：WednesdayOfPreviousWeek(DateTime)

返回值：DateTime

说明：计算指定日期上周的星期三对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

WednesdayOfWeek
~~~~~~~~~~~~~~~~~~
函数体：WednesdayOfWeek(DateTime)

返回值：DateTime

说明：计算指定日期本周的星期三对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

WeekNoOfYear
~~~~~~~~~~~~~~~~~~
函数体：WeekNoOfYear(Datetime)

返回值：Integer

说明：获取指定日期所在星期是该年中的第几星期。

WeeksDifference
~~~~~~~~~~~~~~~~~~
函数体：WeeksDifference(BaseDatetime,Datetime)

返回值：Double

说明：以小数的形式返回从日期BaseDatetime至日期Datetime的周数。这基于每周7.0 天。如果Datetime在BaseDatetime之前，则该函数返回负值。

Year
~~~~~~~~~~~~~~~~~~
函数体：Year()

返回值：String

说明：取当前系统的年

函数体：Year(Datetime)

返回值：Integer

说明：返回Datetime的年份部分。返回结果为整数，如2002。

YearsDifference
~~~~~~~~~~~~~~~~~~
函数体：YearsDifference(BasedDatetime,Datetime)

返回值：Double

说明：以小数的形式返回从日期BasedDatetime至日期Datetime的年数。这是基于每年365.0 天的近似数字。如果Datetime在BasedDatetime之前，则该函数返回负值。

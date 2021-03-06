.. _ShuZhiHanShu:
数值函数
======================

%
~~~~~~~~~~~~~~~~~~
操作符： **%**

返回值：Number

说明：余数，双目运算符，输出其左边的数除以右面数后的余数，注：左右两个参数必须为整数。

/
~~~~~~~~~~~~~~~~~~
操作符： **/**

返回值：Number

说明：除法运算，双目运算符。

\*
~~~~~~~~~~~~~~~~~~
操作符： **\***

返回值：Number

说明：乘法运算，双目运算符，它将两个字符串连接到一起。

\+
~~~~~~~~~~~~~~~~~~
操作符： **\+**

返回值：Number

说明：加法运算，双目运算符，置于两个数值之间：NUM1+NUM2（NUM1加上NUM2）。

\-
~~~~~~~~~~~~~~~~~~
操作符： **\-**

返回值：Number

说明：减法运算，置于两个数值之间：NUM1-NUM2（NUM1减去NUM2）；或置于一个数值之间：-NUM（NUM的负数）。

abs
~~~~~~~~~~~~~~~~~~
函数体： **abs(NUM)**

返回值：Double

说明：绝对值，返回数值参数NUM的绝对值，如果NUM为NULL，则返回NULL，如果NUM为不能转换成数值的字符串，则返回0，如果NUM值超出Integer的上限，则抛出"Integer Overflow"的异常。

ceil
~~~~~~~~~~~~~~~~~~
函数体： **ceil(NUM)**

返回值：Integer

说明：向上取整,返回大于或者等于指定表达式的最小整数。

exp
~~~~~~~~~~~~~~~~~~
函数体： **exp(NUM)**

返回值：Double

说明：自然数指数，返回e的n次方，e是一个常数为2.71828182845905（自然数)。

floor
~~~~~~~~~~~~~~~~~~
函数体： **floor(NUM)**

返回值：Integer

说明：向下取整,返回小于或者等于指定表达式的最小整数。

fracof
~~~~~~~~~~~~~~~~~~
函数体： **fracof(Number)**

返回值：Double

说明：返回Number 的小数部分，定义为Number–intof(Number)。

IEEERemainder
~~~~~~~~~~~~~~~~~~
函数体： **IEEERemainder(Number,Divisor)**

返回值：Double

说明：返回Number除Divisor的余数。

intof
~~~~~~~~~~~~~~~~~~
函数体： **intof(Number)**

返回值：Integer

说明：将其参数截为整数,返回与NUM 符号相同的整数。

Log
~~~~~~~~~~~~~~~~~~
函数体： **Log(NUM,BASE)**

返回值：Double

说明：对数，以BASE底数，返回NUM的对数。

log
~~~~~~~~~~~~~~~~~~
函数体： **log(NUM)**

返回值：Double

说明：对数，返回以e为底NUM的对数，e是一个常数为2.71828182845905（自然数)。

log10
~~~~~~~~~~~~~~~~~~
函数体： **log10(NUM)**

返回值：Double

说明：对数，返回以 10 为底 NUM 的对数。

Mean
~~~~~~~~~~~~~~~~~~
函数体： **Mean(Number,...)**

返回值：Any

说明：返回函数参数中的平均值，如果有任何一个参数为NULL，则返回NULL。

mean_n
~~~~~~~~~~~~~~~~~~
函数体： **mean_n(List)**

返回值：Number

说明：返回数值列表所有组元值的平均值，如果所有组元均为空，则返回0。

power
~~~~~~~~~~~~~~~~~~
函数体： **power(NUM, POWER)**

返回值：Double

说明：幂函数，返回 NUM 的 POWER 次方。

Round
~~~~~~~~~~~~~~~~~~
函数体： **Round(NUM)**

返回值：Integer

说明：四舍五入，返回与参数最接近的整数值。

函数体： **Round(NUM,Integer)**

返回值：Double

说明：四舍五入，返回按指定位数(Integer)进行四舍五入的数值。

sdev_n
~~~~~~~~~~~~~~~~~~
函数体： **sdev_n(List)**

返回值：Number

说明：返回数值列表所有组元值的标准差，如果所有组元均为空，则返回0。

sign
~~~~~~~~~~~~~~~~~~
函数体： **sign(NUM)**

返回值：Integer

说明：返回数字的符号。当数字为正数时返回 1，为零时返回 0，为负数时返回 -1。

sqrt
~~~~~~~~~~~~~~~~~~
函数体： **sqrt(NUM)**

返回值：Double

说明：返回数字的平方根。

square
~~~~~~~~~~~~~~~~~~
函数体： **square(NUM)**

返回值：Double

说明：返回数字的平方。

sum_n
~~~~~~~~~~~~~~~~~~
函数体： **sum_n(List)**

返回值：Number

说明：返回数值列表所有组元值的和，如果所有组元均为空，则返回0。

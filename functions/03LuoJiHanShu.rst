.. _LuoJiHanShu:
逻辑函数
======================

and
~~~~~~~~~~~~~~~~~~
操作符： **Cond1 and Cond2**
|返回值：Boolean
|说明：并且，双目逻辑运算符。当Cond1 与Cond2同时为真时返回真值。如果Cond1为假，则不求Cond2的值。

between  and
~~~~~~~~~~~~~~~~~~
操作符： **Item1 between Item2 and Item3**
|返回值：Boolean
|说明：界于之间，三目逻辑运算符。例："x BETWEEN y AND z"等同于"x  >=y AND x< =z"。

CASE  WHEN  THEN  WHEN  THEN  ELSE  END
~~~~~~~~~~~~~~~~~~
操作符： **CASE Item1 WHEN Item2 THEN Item3 WHEN Item4 THEN Item5 ELSE Item6 END**
|返回值：Any
|说明：条件语句。例：CASE x WHEN w1 THEN r1 WHEN w2 THEN r2 ELSE r3 END

CASE WHEN  THEN  WHEN  THEN  ELSE  END
~~~~~~~~~~~~~~~~~~
操作符： **CASE WHEN Item1 THEN Item2 WHEN Item3 THEN Item4 ELSE Item5 END**
|返回值：Any
|说明：条件语句。例：CASE WHEN x=w1 THEN r1 WHEN x=w2 THEN r2 ELSE r3 END

decode
~~~~~~~~~~~~~~~~~~
函数体： **decode(value, if1, then1, if2,then2, if3,then3, … else )**
|返回值：Any
|说明：逻辑处理函数。类似于If-Then-Else进行逻辑判断。Value 代表某个表的任何类型的任意列或一个通过计算所得的任何结果。当每个value值被测试，如果value的值为if1，Decode 函数的结果是then1；如果value等于if2，Decode函数结果是then2；等等。

false
~~~~~~~~~~~~~~~~~~
操作符： **false**
|返回值：Boolean
|说明：表示逻辑假值。

iif
~~~~~~~~~~~~~~~~~~
函数体： **iif(Cond,TrueItem,FalseItem)**
|返回值：Any
|说明：条件函数。如果条件Cond满足(为真)，返回表达式TrueItem的值，否则表达式FalseItem的值。

not
~~~~~~~~~~~~~~~~~~
函数体： **not( Cond )**
|返回值：Boolean
|说明：非，单目逻辑运算符。如果Cond为假，则返回真。否则，此运算将返回值0。

NullIf
~~~~~~~~~~~~~~~~~~
函数体： **NullIf(expr1, expr2)**
|返回值：Any
|说明：如果两个表达式相等，NullIf返回空值NULL,否则返回expr1的值。

nvl
~~~~~~~~~~~~~~~~~~
函数体： **nvl(expr1, expr2)**
|返回值：Any
|说明：如果expr1不为NULL，则返回expr1的值；expr1为NULL，返回expr2的值。注：expr1和expr2必须为同一数据类型。

nvl2
~~~~~~~~~~~~~~~~~~
函数体： **nvl2(Expression, IsNotNullItem, IsNullItem)**
|返回值：Any
|说明：如果Expression不为NULL，则返回IsNotNullItem；expr1为NULL，返回IsNullItem。

or
~~~~~~~~~~~~~~~~~~
操作符： **Cond1 or Cond2**
|返回值：Boolean
|说明：或，双目逻辑运算符。当Cond1或Cond2为真或这两者同时为真时，返回真值。如果Cond1为真，则不求Cond2的值。

true
~~~~~~~~~~~~~~~~~~
操作符： **true**
|返回值：Boolean
|说明：表示逻辑真值。

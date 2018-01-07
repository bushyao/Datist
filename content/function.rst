.. _FA:

函数帮助
======================
数值函数
-----------------

%
~~~~~~~~~~~~~~~~~~
返回值：Number

说明：余数，双目运算符，输出其左边的数除以右面数后的余数，注：左右两个参数必须为整数。

\*
~~~~~~~~~~~~~~~~~~
返回值：Number

说明：乘法运算，双目运算符，它将两个字符串连接到一起。

\+
~~~~~~~~~~~~~~~~~~
返回值：Number

说明：加法运算，双目运算符，置于两个数值之间：NUM1+NUM2（NUM1加上NUM2）。

\-
~~~~~~~~~~~~~~~~~~
返回值：Number

说明：减法运算，置于两个数值之间：NUM1-NUM2（NUM1减去NUM2）；或置于一个数值之间：-NUM（NUM的负数）。

/
~~~~~~~~~~~~~~~~~~
返回值：Number

说明：除法运算，双目运算符。

IEEERemainder(Number,Divisor)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回Number除Divisor的余数。

Log(NUM,BASE)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：对数，以BASE底数，返回NUM的对数。

Mean(Number,...)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：返回函数参数中的平均值，如果有任何一个参数为NULL，则返回NULL。

Round(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：四舍五入，返回与参数最接近的整数值。

Round(NUM,Integer)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：四舍五入，返回按指定位数(Integer)进行四舍五入的数值。

abs(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：绝对值，返回数值参数NUM的绝对值，如果NUM为NULL，则返回NULL，如果NUM为不能转换成数值的字符串，则返回0，如果NUM值超出Integer的上限，则抛出"Integer Overflow"的异常。

ceil(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：向上取整,返回大于或者等于指定表达式的最小整数。

exp(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：自然数指数，返回e的n次方，e是一个常数为2.71828182845905（自然数)。

floor(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：向下取整,返回小于或者等于指定表达式的最小整数。

fracof(Number)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回Number 的小数部分，定义为Number–intof(Number)。

intof(Number)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：将其参数截为整数,返回与NUM 符号相同的整数。

log(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：对数，返回以e为底NUM的对数，e是一个常数为2.71828182845905（自然数)。

log10(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：对数，返回以 10 为底 NUM 的对数。

mean_n(List)
~~~~~~~~~~~~~~~~~~
返回值：Number

说明：返回数值列表所有组元值的平均值，如果所有组元均为空，则返回0。

power(NUM, POWER)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：幂函数，返回 NUM 的 POWER 次方。

sdev_n(List)
~~~~~~~~~~~~~~~~~~
返回值：Number

说明：返回数值列表所有组元值的标准差，如果所有组元均为空，则返回0。

sign(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回数字的符号。当数字为正数时返回 1，为零时返回 0，为负数时返回 -1。

sqrt(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回数字的平方根。

square(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回数字的平方。

sum_n(List)
~~~~~~~~~~~~~~~~~~
返回值：Number

说明：返回数值列表所有组元值的和，如果所有组元均为空，则返回0。

三角函数
-----------------

acos(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：反余弦函数，NUM必须介于 -1 到 1 之间。返回以弧度表示的角，若要用度表示，请再乘以 180/PI( ) 或用 DEGREES 函数表示。

acosh(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：反双曲余弦函数,NUM必须大于或等于 1。返回以弧度表示的角，若要用度表示，请再乘以 180/PI( ) 或用 DEGREES 函数表示。

asin(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：反正弦函数，NUM必须介于 -1 到 1 之间。返回以弧度表示的角，若要用度表示，请再乘以 180/PI( ) 或用 DEGREES 函数表示。

asinh(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：反双曲正弦函数。返回以弧度表示的角，若要用度表示，请再乘以 180/PI( ) 或用 DEGREES 函数表示。

atan(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：反正切函数，返回以弧度表示的角，若要用度表示，请再乘以 180/PI( ) 或用 DEGREES 函数表示。

atan2(NUM_X,NUM_Y)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：求角度，与atn2(NUM_X,NUM_Y)相同，返回指定点(NUM_X,NUM_Y)和原点 (0, 0) 连线与 X 轴的夹角大小(弧度值)。若要用度表示，请再乘以 180/PI( ) 或用 DEGREES 函数表示。

atanh(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：反双曲正切函数,NUM必须介于 -1 到 1 之间(不包括-1和1)。返回以弧度表示的角，若要用度表示，请再乘以 180/PI( ) 或用 DEGREES 函数表示。

atn2(NUM_X,NUM_Y)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：求角度，与atan2(NUM_X,NUM_Y)相同，返回指定点(NUM_X,NUM_Y)和原点 (0, 0) 连线与 X 轴的夹角大小(弧度值)。若要用度表示，请再乘以 180/PI( ) 或用 DEGREES 函数表示。

cos(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：余弦函数。

cosh(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：双曲余弦函数。

cot(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：余切函数。

coth(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：双曲余切函数。

degrees(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：弧度转角度。返回以弧度表示的角，若要用度表示，请再乘以 180/PI( ) 或用 DEGREES 函数表示。

pi()
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：常数圆周率∏,pi为3.14159265358979323846

radians(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：角度转弧度。返回以弧度表示的角，若要用度表示，请再乘以 180/PI( ) 或用 DEGREES 函数表示。

sin(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：正弦函数。

sinh(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：双曲正弦函数。

tan(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：正切函数。

tanh(NUM)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：双曲正切函数。

字符串函数
-----------------

AllButFirst(STRING,LEN)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回STRING的子字符串，除去字符串STRING开始的LEN个字符。

AllButLast(STRING,LEN)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回STRING的子字符串，除去字符串STRING结尾的LEN个字符。

AlphaBefore(String,BaseString)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：用于检查字符串的数字字母顺序。如果STRING在BaseString之前，则返回真值。

CharCommon(STRING1,STRING2)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：对比两个字符串，返回共公的字符数。

CharCommon(STRING1,STRING2,Bool Step)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：对比两个字符串，返回共公的字符数；Step为真时，按位比较。

Count_SubString(STRING,N,SUBSTRING)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：返回字符串中指定字符串出现的次数。N为搜索起始位置,其中N从0开始计数。

Count_SubString(STRING,SUBSTRING)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：返回字符串中指定字符串出现的次数。例如，count_substring("foooo.txt", "oo") 返回3。

DefaultToUTF8(String Text)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：字符串编码转换,默认编码转换为UTF8。

EndString(STRING,LEN)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回STRING的子字符串，包括字符串STRING的最后的LEN个字符。与RightStr(STRING,LEN)相同。

EndsWith(STRING,SUBSTRING)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：如果STRING以SUBSTRING结束，返回真(1)，否则返回假(0)。

HasChars(STRING,CHARS)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：检查字符串STRING中是否包含CHARS定义的字符，包含CHARS中任意字符返回真（1）。

HasEndString(STRING,SUBSTRING)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：如果STRING以SUBSTRING结束，返回真(1)，否则返回假(0)。

HasMidString(STRING,SUBSTRING)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：如果STRING中包含SUBSTRING，且SUBSTRING不以SUBSTRING开始或结束，返回真(1)，否则返回假(0)。

HasStartString(STRING,SUBSTRING)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：如果STRING以SUBSTRING开始，返回真(1)，否则返回假(0)。

HasSubString(STRING,N,SUBSTRING)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：如果STRING中包含SUBSTRING，返回真(1)，否则返回假(0)，N为搜索起始位置,其中N从0开始计数。

HasSubString(STRING,SUBSTRING)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：如果STRING中包含SUBSTRING，返回真(1)，否则返回假(0)。

HasSubStringsAND(STRING,SUBSTRING1,SUBSTRING2,…)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：如果STRING中包含SUBSTRING1并且包括SUBSTRING2并且…，返回真(1)，否则返回假(0)。

HasSubStringsOR(STRING,SUBSTRING1,SUBSTRING2,…)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：如果STRING中包含SUBSTRING1或者包括SUBSTRING2或者…，返回真(1)，否则返回假(0)。

IndexOf(STRING,N,SUBSTRING)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：字符串定位,返回SUBSTRING在STRING中位置N之后的第一个匹配位置(第一个字符位置为1)。如果两个字符串不匹配返回0。

IndexOf(STRING,SUBSTRING)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：字符串定位,返回SUBSTRING在STRING中第一个匹配的位置(第一个字符位置为1)。如果两个字符串不匹配返回0。

InsertString(String,Id,InsertString)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：向字符串插入指定的字符串。

IsMatch(String, RegexString)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：如果正则表达式匹配，返回真(1)，否则返回假(0)。

IsMatch(String, RegexString, RegexOptions)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：如果正则表达式匹配，返回真(1)，否则返回假(0)。RegexOptions用于设置正则表达式选项的枚举值。例如：IsMatch("ASDV","^[a-z]+$","Compiled | IgnoreCase")选项值有：None,Compiled,CultureInvariant,ECMAScript,ExplicitCapture,IgnoreCase,IgnorePatternWhitespace,Multiline,RightToLeft,Singleline。

Item1 || Item2
~~~~~~~~~~~~~~~~~~
返回值：String

说明：连接符，双目运算符，连接两个字段的值，并返回结果字符串Item1Item2。

JoinItems(SplitChar,item1,Item2,……)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将多个字段内容合并成一个字符串。

JsonListItemValues(String JsonText,String KeyName)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：从简单Json列表中，取指定的属性值列表，元素之间以;分隔。

JsonObjectValue(String JsonText,String PathName)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：从Json对象中取指定的属性值，PathName支持路径，如：routes[0].legs[0].distance.text。

JsonValue(String JsonText,String KeyName)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：从Json对象中取指定的属性值，KeyName为关键字名称。

JsonValue(String JsonText,String KeyName,String SplitChars)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：从Json对象中取指定的属性值，KeyName为关键字名称，SplitChars为输出分隔符。

LCS(STRING1,STRING2)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：LCS (Longest Common Subsequence) 算法用于找出两个字符串最长公共子串。

LastIndexOf(STRING,N,SUBSTRING)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回子字符串的位置,从后向前匹配SUBSTRING在STRING中位置（N为从后向前计数的位置）。如果两个字符串不匹配返回0。

LastIndexOf(STRING,SUBSTRING)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回子字符串的位置,从后向前匹配SUBSTRING在STRING中位置。如果两个字符串不匹配返回0。

LeftStr(STRING,LEN)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回STRING的左边N个字符串。

Length(STRING)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：如果参数STRING为字符串，则返回字符的数量，如果为数值，则返回该参数的字符串表示形式的长度，如果为NULL，则返回NULL。

LengthB(string str)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回文本的字节长度，中文为两个字节，字母为一个字节。

Lower(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回函数参数X的小写形式，缺省情况下，该函数只能应用于ASCII字符。

Match(String, RegexString, RegexOptions)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：正则表达式匹配，返回第一个匹配结果。RegexOptions用于设置正则表达式选项的枚举值。例如：Match("ASDV","[a-z]+","Compiled | IgnoreCase")选项值有：None,Compiled,CultureInvariant,ECMAScript,ExplicitCapture,IgnoreCase,IgnorePatternWhitespace,Multiline,RightToLeft,Singleline。

Match(String,RegexString)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：正则表达式匹配，返回第一个匹配结果。

MatchDate(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：通过正则表达式匹配从文本中抽取日期。支持格式：2000-1-1、2000年1月1日、2000/1/1

MatchGroup(String, RegexString, GroupName, RegexOptions)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：分组正则表达式匹配，返回第一个匹配结果。RegexOptions用于设置正则表达式选项的枚举值。例如：MatchGroup("关井油压5.7MPa,套压8.2MPa。", "油压(?<GN>[0-9]+(\.[0-9]+){0,1})" ,"GN","Compiled | IgnoreCase")选项值有：None,Compiled,CultureInvariant,ECMAScript,ExplicitCapture,IgnoreCase,IgnorePatternWhitespace,Multiline,RightToLeft,Singleline。

MatchGroup(String,RegexString,GroupName)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：分组正则表达式匹配，返回第一个匹配结果。

MatchGroup(String,RegexString,GroupName)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：分组正则表达式匹配，返回字符串列表。

MatchGroups(String, RegexString, GroupName, RegexOptions)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：分组正则表达式匹配，返回字符串列表。RegexOptions用于设置正则表达式选项的枚举值。例如：MatchGroup("关井油压5.7MPa,套压8.2MPa。", "油压(?<GN>[0-9]+(\.[0-9]+){0,1})" ,"GN","Compiled | IgnoreCase")选项值有：None,Compiled,CultureInvariant,ECMAScript,ExplicitCapture,IgnoreCase,IgnorePatternWhitespace,Multiline,RightToLeft,Singleline。

MatchTime(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：通过正则表达式匹配从文本中抽取时间。支持格式：20:30:30、20：30

Matches(String, RegexString, RegexOptions)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：正则表达式匹配，返回字符串列表。RegexOptions用于设置正则表达式选项的枚举值。例如：Matches("$ASDV@ad","[a-z]+","Compiled | IgnoreCase")选项值有：None,Compiled,CultureInvariant,ECMAScript,ExplicitCapture,IgnoreCase,IgnorePatternWhitespace,Multiline,RightToLeft,Singleline。

Matches(String,RegexString)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：正则表达式匹配，返回字符串列表。

NewLine()
~~~~~~~~~~~~~~~~~~
返回值：String

说明：回车字符。

Padc(STRING,LEN)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：字符串两端补全，返回一个长度为LEN的字符串，在STRING两端增加多个空格，使其长度为LEN。当原有字符串的长度大于LEN时，返回原有STRING。

Padl(STRING,LEN)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：左边字符串补全，返回一个长度为LEN的字符串，在STRING左边增加多个空格，使其长度为LEN。当原有字符串的长度大于LEN时，返回原有STRING。

Padl(STRING,LEN,Char)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：左边字符串补全，返回一个长度为LEN的字符串，在STRING左边增加多个Char，使其长度为LEN。当原有字符串的长度大于LEN时，返回原有STRING。

Padr(STRING,LEN)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：右边字符串补全，返回一个长度为LEN的字符串，在STRING右边增加多个空格，使其长度为LEN。当原有字符串的长度大于LEN时，返回原有STRING。

Padr(STRING,LEN,Char)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：右边字符串补全，返回一个长度为LEN的字符串，在STRING右边增加多个Char，使其长度为LEN。当原有字符串的长度大于LEN时，返回原有STRING。

Proper(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：首字母大写，将文本字符串STRING的首字母转换成大写，将其余的字母转换成小写。

RemoveBetweenS(STRING,StartSubString,EndSubString)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除STRING中StartSubString-EndSubString之间的字符。

RemoveBreakAndSpace(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除字符串中的回车、中英文空格、制表符。

RemoveChars(STRING,Chars)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：从字符串STRING中，删除所有Chars字符。

RemoveHiddenCharacters(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除文本中所有不可见字符。

RemoveLineBreak(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除文本中所有的换行符。

RemoveMinLine(String,Length)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除文本中的长度小于Length的行。

RemoveRedundantSpace(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将字符串中的多个空格替换成一个空格。

RemoveRept(STRING,CHAR)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除重复字符。

RemoveStrings(STRING,STRING1,STRING2,…)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：从字符串STRING中，删除字符串STRING1,STRING2,…。

Replace(String, OLD_STRING1, NEW_STRING1, OLD_STRING2, NEW_STRING2...)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：字符串替换，用NEW_STRING1替换OLD_STRING1,用NEW_STRING2替换OLD_STRING2...

ReplaceBetweenS(STRING,StartSubString,EndSubString,ReplaceString)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：用ReplaceString替换STRING中StartSubString-EndSubString之间的字符。

ReplaceLineBreak(STRING,RepString)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：用RepString替换文本中所有的换行符。

ReplaceReg(String, RegexString, RepString)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：根据正则表达式，替换指定的匹配内容。

ReplaceReg(String, RegexString, RepString, RegexOptions)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：根据正则表达式，替换指定的匹配内容。RegexOptions用于设置正则表达式选项的枚举值。例如：ReplaceReg("$ASDV@","[a-z]+","dsdfs","Compiled | IgnoreCase")选项值有：None,Compiled,CultureInvariant,ECMAScript,ExplicitCapture,IgnoreCase,IgnorePatternWhitespace,Multiline,RightToLeft,Singleline。

Rept(STRING,N)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：复制字符串，返回一个包括N个STRING的字符串。

Reverse(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：字符串反序，返回与STRING字符顺序相反的字符串。

RightStr(STRING,LEN)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回STRING的右边N个字符串。

SimpleString(STRING,LEN)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回STRING的子字符串，包括字符串STRING开始的LEN个字符，与StartString相似，未端有...标记。

SpaceNormal(String Text)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将任何空白字符转换为空格，例如空格符、制表符和进纸符等。注：效率较慢。

SplitString(String,SplitChars)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：用SplitChars分隔String中的每个字符。

SplitText(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：对文本进行中文划词,采用双向最大匹配法。

SplitText(String,DictID)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：对文本进行中文划词,采用双向最大匹配法,DictID为字典的ID。

SplitText(String,DictID,OnlyInDict)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：对文本进行中文划词,采用双向最大匹配法,DictID为字典的ID,OnlyInDict布尔型，为真输出字典中的值。

SplitText(String,DictID,OnlyInDict,LengthAsc)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：对文本进行中文划词,采用双向最大匹配法,DictID为字典的ID,OnlyInDict布尔型，为真输出字典中的值；LengthDsc输出结果按长度排序，True为正序，False为倒序。

StartString(STRING,LEN)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回STRING的子字符串，包括字符串STRING开始的LEN个字符。与LeftStr(STRING,LEN)相同。

StartsWith(STRING,SUBSTRING)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：如果STRING以SUBSTRING开始，返回真(1)，否则返回假(0)。

StartsWithOR(STRING,SUBSTRING1,SUBSTRING2,…)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：如果STRING以SUBSTRING1或者SUBSTRING2或者…开始，返回真(1)，否则返回假(0)。

StrFilter(String,SubString)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：字符串过滤，在String中过滤出所有SubString，删除String中所有不等于SubString的字符串。

StringCompare(STRING,STRING)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：两个字符串比较。

SubStr(STRING,N)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回函数参数STRING的子字符串，从第N位开始(STRING中的第一个字符位置为1)后面的所有字符。如果N值为负数，则从STRING字符串的尾部开始计数到第abs(N)的位置开始，后面的所有字符。

SubStr(STRING,N,LEN)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回函数参数STRING的子字符串，从第N位开始(第一个字符位置为1)截取LEN长度的字符。如果LEN的值为负数，则从第N位开始，向左截取abs(LEN)个字符。如果N值为负数，则从STRING字符串的尾部开始计数到第abs(N)的位置开始。

SubStrB(STRING,N)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：与SubStr类似，该函数以字节数字计算字符长度，中文长度为2，字母长度为1；返回函数参数STRING的子字符串，从第N位开始后面的所有字符。如果N值为负数，则从STRING字符串的尾部开始计数到第abs(N)的位置开始，后面的所有字符。

SubStrB(STRING,N,LEN)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：与SubStr类似，该函数以字节数字计算字符长度，中文长度为2，字母长度为1；返回函数参数STRING的子字符串，从第N位开始截取LEN长度的字符。如果LEN的值为负数，则从第N位开始，向左截取abs(LEN)个字符。如果N值为负数，则从STRING字符串的尾部开始计数到第abs(N)的位置开始。

SubStrBetween(STRING,N,M)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回STRING中N-M之间的子字符串。

SubStrBetweenL(STRING,List1,List2,ID,Char)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回STRING中List1-List2之间的子字符串,ID可选，第N个匹配项，0为所有（默认），1第1个，2第二个...;Char可选，输出连接间隔符。如：SubStrBetweenL( 内容 , ['供稿:'] , ['审稿','审核','编审', '
' ])

SubStrBetweenS(STRING,StartSubString,EndSubString)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回STRING中StartSubString-EndSubString之间的子字符串；若StartSubString为空，取EndSubString之前的所有字符串；若EndSubString为空，取StartSubString之后的所有字符串。

SubStrBetweenS(STRING,StartSubString,EndSubString,ID [,Char])
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回STRING中StartSubString-EndSubString之间的子字符串;ID可选，第N个匹配项, 0为所有（默认），1第1个，2第二个...，负数从后向前-1为最后一个，-2倒数第二个;Char可选，输出连接间隔符。

ToChineseMoney(Real)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将数字转为人民币汉字大写表示。

ToDBC(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将字符串STRING转化全角字符串。(Double Byte Characters，简称DBC)

ToPinyin(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将汉字转化为拼音。

ToPinyinFirstLetter(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将汉字转换为拼音首字母。

ToSBC(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将字符串STRING转化半角字符串。(Single Byte Characters，简称SBC)

Upper(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回函数参数X的大写形式，缺省情况下，该函数只能应用于ASCII字符。

UrlDecode(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：URL解码,如“%e7%a7%91%e6%8a%80%e5%88%9b%e6%96%b0”转化为“科技创新”

UrlEncode(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：URL编码,如“科技创新”转化为“%e7%a7%91%e6%8a%80%e5%88%9b%e6%96%b0”

WordDF(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回文本中出现频率最高的前10个词组,采用双向最大匹配法。

WordDF(String,DictID)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回文本中出现频率最高的前10个词组,采用双向最大匹配法,DictID为字典的ID。

WordDF(String,DictID,OnlyInDict)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回文本中出现频率最高的前10个词组,采用双向最大匹配法,DictID为字典的ID,OnlyInDict布尔型,为真输出字典中的值。

WordDF(String,DictID,OnlyInDict,SplitChar)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回文本中出现频率最高的前10个词组,采用双向最大匹配法,DictID为字典的ID,OnlyInDict布尔型,为真输出字典中的值,输出结果以SplitChar指定的字符分隔。

WordDF(String,DictID,OnlyInDict,SplitChar,MaxCount)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回文本中出现频率最高的前MaxCount个词组,采用双向最大匹配法,DictID为字典的ID,OnlyInDict布尔型,为真输出字典中的值,输出结果以SplitChar指定的字符分隔。

like
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：相似模式匹配比较，不区分大小写。它左边包含被匹配的字符串，右边是一个匹配模式。在匹配模式中，%匹配字符串中任意0个或多个字符,_仅匹配一个任意的字符。

like escape
~~~~~~~~~~~~~~~~~~
返回值：String

说明：使用escape，定义转义字符，转义字符后面的%或_就不作为通配符了。例如：username like '%xiao\_%' escape '\'，字符\为转义字符。

ltrim(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除STRING左边所有空格。

ltrim(String,Chars)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除String左边所有空格及Chars。

not like
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：不相似模式匹配比较，不区分大小写。它左边包含被匹配的字符串，右边是一个匹配模式。在匹配模式中，%匹配字符串中任意0个或多个字符,_仅匹配一个任意的字符。

rtrim(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除STRING右边所有空格。

rtrim(String,Chars)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除String右边所有空格及Chars。

sscanf(String,Format)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：读取指定格式的数据。其中Format可以是%[*][width]type，加*表示跳过此数据不读；width表示读取宽度；type表示类型c为一个字符，d为整数，f为实数,s为多个任意字符；例如%s,%*3s等。

sscanf(String,Format,SplitChar)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：读取指定格式的数据。其中Format可以是%[*][width]type，加*表示跳过此数据不读；width表示读取宽度；type表示类型c为一个字符，d为整数，f为实数,s为多个任意字符。SplitChar为输出联接字符。

trim(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除字符串两端的空格。

trim(String,Chars)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除String两端所有空格及Chars。

日期与时间
-----------------

AddDays(Datetime,Real)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：将指定的天数加到Datetime上，Integer参数可以是负数也可以是正数。

AddHours(Datetime,Real)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：将指定的小时数加到Datetime上，Integer参数可以是负数也可以是正数。

AddMilliseconds(Datetime,Real)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：将指定的毫秒数加到Datetime上，Integer参数可以是负数也可以是正数。

AddMinutes(Datetime,Real)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：将指定的分钟数加到Datetime上，Integer参数可以是负数也可以是正数。

AddMonths(Datetime,Integer)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：将指定的月份数加到Datetime上，Integer参数可以是负数也可以是正数。

AddSeconds(Datetime,Real)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：将指定的秒数加到Datetime上，Integer参数可以是负数也可以是正数。

AddYears(Datetime,Integer)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：将指定的年份数加到Datetime上，Integer参数可以是负数也可以是正数。

CENCToDate(Double)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：将一个地震日期编号转换为日期。

CreateDate(Year,Month,Day)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：返回指定Year，Month和Day的时间值，参数必须为整数。

CreateDatetime(Year,Month,Day,Hour,Minute,Second)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：返回指定Year，Month，Day，Hour，Minute和Second 的时间值。

CreateTime(Hour,Minute,Second)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：返回指定Hour，Minute和Second 的时间值。

CreateTimeSpan(days,hours,minutes,seconds)
~~~~~~~~~~~~~~~~~~
返回值：TimeSpan

说明：返回指定的时间间隔。

CreateTimeSpan(days,hours,minutes,seconds,milliseconds)
~~~~~~~~~~~~~~~~~~
返回值：TimeSpan

说明：返回指定的时间间隔。

CreateTimeSpan(hours,minutes,seconds)
~~~~~~~~~~~~~~~~~~
返回值：TimeSpan

说明：返回指定的时间间隔。

DateAfter(Datetime,BaseDatetime)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：Datetime 在 BaseDatetime之后，则返回真值，否则，此函数的返回结果为假值；如果Datetime,BaseDatetime非标准的日期格式，返回空。

DateBefore(Datetime,BaseDatetime)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：Datetime在BaseDatetime之前，则返回真值，否则，此函数的返回结果为假值；如果Datetime,BaseDatetime非标准的日期格式，返回空。

DatetimeDifference(BaseDateTime，Datetime)
~~~~~~~~~~~~~~~~~~
返回值：TimeSpan

说明：返回Datetime-BaseDateTime的时间间隔。

DatetimeEqual(Datetime1,Datetime2)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：两个时间比较，相等为真，不相等为否。

Day()
~~~~~~~~~~~~~~~~~~
返回值：String

说明：取当前日

Day(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回Datetime的天部分。返回结果为1 到31 之间的整数。

DayOfMonth(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：获取日期为该月中的第几天。

DayOfWeek(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：表示的日期是星期几,返回结果为0 到6之间的整数。

DayOfWeek_cn(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：表示的日期是星期几,返回结果为星期日,星期一,星期二,星期三,星期四,星期五,星期六。

DayOfWeek_en(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：表示的日期是星期几,返回结果为Sunday,Monday,Tuesday,Wednesday,Thursday,Friday,Saturday。

DayOfWeek_en_short(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：表示的日期是星期几,返回结果为Sun, Mon, Tue, Wed, Thu, Fri, Sat。

DayOfYear(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：获取指定日期是该年中的第几天。

DaysDifference(BaseDateTime，Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：以小数的形式返回从日期BaseDateTime到日期Datetime的天数。如果Datetime在BaseDateTime之前，则该函数返回负值。

FirstDayOfMonth(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期所在月份第一天。

FirstDayOfNextMonth(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期的下个月第一天。

FirstDayOfNextQuarter(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期的下一季度第一天。

FirstDayOfNextYear(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期的下一年第一天。

FirstDayOfPreviousMonth(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期的上个月第一天。

FirstDayOfPreviousQuarter(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期的上一季度第一天。

FirstDayOfPreviousYear(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期的上一年第一天。

FirstDayOfQuarter(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期所在季度份第一天。

FirstDayOfYear(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期所在年份第一天。

Format_TimeSpan(TimeSpan)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将时间间隔转化为指定格式的文本。

Format_TimeSpan(TimeSpan,TimeSpanFormat)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将时间间隔转化为指定格式的文本，TimeSpanFormat为格式：dd\天hh\时mm\分ss\秒，注意反斜杠。

FridayOfNextWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期下周的星期五对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

FridayOfPreviousWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期上周的星期五对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

FridayOfWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期本周的星期五对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

From_UnixTime(Int)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：将Unix时间转换为日期。

Hour()
~~~~~~~~~~~~~~~~~~
返回值：String

说明：取当前时

Hour(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回Datetime的小时部分。返回结果为0 至23 之间的整数。

HoursDifference(BasedDatetime,Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：以小数的形式返回从日期BasedDatetime到日期Datetime的小时数。如果Datetime在BasedDatetime之前，则该函数返回负值。

JulianToDate(Double)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：将儒略日转换为日期，以1970-01-01 0:0:0.0为基数。

LastDayOfMonth(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期所在月份最后一天。

LastDayOfNextMonth(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期的下个月的最后一天。

LastDayOfNextQuarter(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期的下一季度的最后一天。

LastDayOfNextYear(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期的下一年的最后一天。

LastDayOfPrdviousMonth(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期的上个月的最后一天。

LastDayOfPrdviousQuarter(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期的上一季度的最后一天。

LastDayOfPrdviousYear(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期的上一年的最后一天。

LastDayOfQuarter(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期所在季度份最后一天。

LastDayOfYear(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定日期所在年份最后一天。

Millisecond()
~~~~~~~~~~~~~~~~~~
返回值：String

说明：取当前毫秒

Milliseconds(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回Datetime的毫秒钟部分。返回结果为0到999之间的整数。

MillisecondsDifference(BaseDatetime,Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：以小数的形式返回从日期BaseDatetime到日期Datetime的毫秒数。如果Datetime在BaseDatetime之前，则该函数返回负值。

Minute()
~~~~~~~~~~~~~~~~~~
返回值：String

说明：取当前分

Minute(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回Datetime的分钟部分。返回结果为0 到59 之间的整数。

MinutesDifference(BaseDatetime,Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：以小数的形式返回从日期BaseDatetime到日期Datetime的分钟数。如果Datetime在BaseDatetime之前，则该函数返回负值。

MondayByWeekNo(Integer year,Integer weekNo)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：获取指定年度第几星期的星期一对应用的日期。

MondayOfNextWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期下周的星期一对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

MondayOfPreviousWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期上周的星期一对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

MondayOfWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期本周的星期一对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

Month()
~~~~~~~~~~~~~~~~~~
返回值：String

说明：取当前月

Month(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回Datetime的月份部分。返回结果为1 到12 之间的整数。

Month_cn(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回Datetime的月份部分。返回结果为一月、二月、三月、四月、五月、六月、七月、八月、九月、十月、十一月、十二月。

Month_en(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回Datetime的月份部分。返回结果为January,February,March,April,May,June,July,August,September,October,November,December。

Month_en_short(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回Datetime的月份部分。返回结果为Jan,Feb,Mar,Apr,May,Jun,Jul,Aug,Sep,Oct,Nov,Dec。

MonthsDifference(BaseDatetime,Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：以小数的形式返回从BaseDatetime到Datetime月数。这是基于每月30.0 天的近似数字。如果Datetime在BaseDatetime之前，则该函数返回负值。

Now()
~~~~~~~~~~~~~~~~~~
返回值：String

说明：取当前系统的年月日时分秒

SaturdayOfNextWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期下周的星期六对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

SaturdayOfPreviousWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期上周的星期六对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

SaturdayOfWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期本周的星期六对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

Second()
~~~~~~~~~~~~~~~~~~
返回值：String

说明：取当前秒

Second(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回Datetime的秒钟部分。返回结果为0 到59 之间的整数。

SecondsDifference(BaseDatetime,Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：以小数的形式返回从日期BaseDatetime到日期Datetime的秒数。如果Datetime在BaseDatetime之前，则该函数返回负值。

SundayOfNextWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期下周的星期日对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

SundayOfPreviousWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期上周的星期日对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

SundayOfWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期本周的星期日对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

ThursdayOfNextWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期下周的星期四对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

ThursdayOfPreviousWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期上周的星期四对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

ThursdayOfWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期本周的星期四对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

TimeAfter(Time,BaseTime)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：Time在BaseTime之后，则返回真值，否则，此函数的返回结果为假值；如果Time,BaseTime非标准的日期格式，返回空。

TimeBefore(Time,BaseTime)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：Time在BaseTime之前，则返回真值，否则，此函数的返回结果为假值；如果Time,BaseTime非标准的日期格式，返回空。

TimeHoursDifference(BaseTime,Time)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：以整数的形式返回从日期BaseTime到日期Time的小时数。如果Time在BaseTime之前，则该函数返回负值。

TimeMillisecondsDifference(BaseTime,Time)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：以整数的形式返回从日期BaseTime到日期Time的毫秒数。如果Time在BaseTime之前，则该函数返回负值。

TimeMinutesDifference(BaseTime,Time)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：以整数的形式返回从日期BaseTime到日期Time的分钟数。如果Time在BaseTime之前，则该函数返回负值。

TimeSecondsDifference(BaseTime,Time)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：以整数的形式返回从日期BaseTime到日期Time的秒数。如果Time在BaseTime之前，则该函数返回负值。

TimeSpan2HM(TimeSpan)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将时间间隔转换为，总小时数：分钟，如25：50表示25小时50分钟。

ToCENCDate(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将一个日期转换为地震日期编号。

ToChineseCalendar(DateTime,Type)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将日期转化农历。返回Type指定类型的日期,1:阳历日期;2:农历日期;3:星期;4:时辰;5:属相;6:节气;7:前一个节气;8:下一个节气;9:节日;10:干支;11:星宿;12:星座

ToDatetime(string)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：将文本转化为日期与时间，支持通用日期与时间格式。

ToDatetime(string,DateTimeFormat)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：将文本转化为日期与时间，支持通用日期与时间格式。DateTimeFormat的参考格式：(年-月-日 时:分:秒.毫秒) yyyy-MM-dd HH:mm:ss（HH为24小时制，hh为12小时制）。

ToDatetime(string,DateTimeFormatList,SplitChar)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：将文本转化为日期与时间，支持通用日期与时间格式，SplitChar为格式列表的分隔字符。DateTimeFormatList的参考格式列表：(年-月-日 时:分:秒.毫秒) yyyy-MM-dd HH:mm:ss（HH为24小时制，hh为12小时制）。

ToJulianDate(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将一个日期转换为儒略日，以1970-01-01 0:0:0.0为基数。

ToOAdate(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将一个日期型的字符串转化(格式为yyyy-MM-dd HH:mm:ss 例如2010-01-01 5:11:33 )为等效的 OLE 自动化日期，返回一个双精度浮点数，它包含与此实例的值等效的 OLE 自动化日期。

To_UnixTime(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：将日期转换为Unix时间，从公元1970年1月1日的UTC时间从0时0分0秒算起到现在所经过的秒数。

TuesdayOfNextWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期下周的星期二对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

TuesdayOfPreviousWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期上周的星期二对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

TuesdayOfWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期本周的星期二对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

WednesdayOfNextWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期下周的星期三对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

WednesdayOfPreviousWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期上周的星期三对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

WednesdayOfWeek(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：DateTime

说明：计算指定日期本周的星期三对应的日期。国际标准ISO 8601将星期一定为一星期的第一天。

WeekNoOfYear(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：获取指定日期所在星期是该年中的第几星期。

WeeksDifference(BaseDatetime,Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：以小数的形式返回从日期BaseDatetime至日期Datetime的周数。这基于每周7.0 天。如果Datetime在BaseDatetime之前，则该函数返回负值。

Year()
~~~~~~~~~~~~~~~~~~
返回值：String

说明：取当前系统的年

Year(Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回Datetime的年份部分。返回结果为整数，如2002。

YearsDifference(BasedDatetime,Datetime)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：以小数的形式返回从日期BasedDatetime至日期Datetime的年数。这是基于每年365.0 天的近似数字。如果Datetime在BasedDatetime之前，则该函数返回负值。

format_DateTime(DateTime,DateTimeFormat)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将日期与时间转化为指定格式的文本，DateTimeFormat为日期格式：(年-月-日 时:分:秒.毫秒) yyyy-MM-dd HH:mm:ss（HH为24小时制，hh为12小时制）。

toShortDate(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将日期时间(可为字符串格式)转化为短日期格式,支持常见的日期格式，如2005-11-5 13:47:04，输出2005-11-5。

toShortTime(DateTime)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将日期时间(可为字符串格式)转化为短时间格式,支持常见的日期格式，如2005-11-5 13:47:04，输出13:47:04。

地理信息
-----------------

Area(Points)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回多边形的面积；式中Points为多边形边界，数据格式：x1 y1,x2 y2,x3 y3。

Area(Points,EPSG)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回多边形的面积；式中Points为多边形边界，数据格式：x1 y1,x2 y2,x3 y3；EPSG为投影带号。

Beijing54ToXian80(Real X,Real Y,Bool IsY)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将北京54坐标转换为西安80，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

Beijing54_3To6(Real X,Real Y,Bool IsY)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将北京54的三度带坐标转换为六度带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

Beijing54_6To3(Real X,Real Y,Bool IsY)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将北京54的六度带坐标转换为三度带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

Beijing54toLL(Real X,Real Y,Bool IsLongitude)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将北京54坐标转换为经纬度坐标（只适应于鄂尔多斯盆地）。式中北京54坐标（X,Y）,X为横坐标(东方向)，Y为纵坐标(北方向)；如IsLongitude为True或1，返回经度值；否则返回纬度值。

Bmap2Gmap(string coord)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将百度坐标转换为gooleMap坐标（间接方法）,coord为'lng,lat'。

Bmap2Gmap(string coord,bool toshape)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将百度坐标转换为gooleMap坐标（间接方法）,toshape为真，返回点图元。

Bmap2GmapOnline(string coord)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：通过百度地图API，将百度坐标转换为gooleMap坐标（间接方法）,coord为'lng,lat'。

Bmap2GmapOnline(string coord,bool toshape)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：通过百度地图API，将百度坐标转换为gooleMap坐标（间接方法）,toshape为真，返回点图元。

Buffer(Shape,Double dist)
~~~~~~~~~~~~~~~~~~
返回值：Polygon

说明：计算图元的缓冲区,dist为距离（单位:米）

Centroid(Shape)
~~~~~~~~~~~~~~~~~~
返回值：Point

说明：返回图元Shape的中心坐标；Shape为图元坐标。

CentroidDistance(Shape1,Shape2)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：两个图元的中心距离；式中Shape1,Shape2为图元坐标,坐标系为西安80经纬度，返回距离单位为米。

CombineTypeDifference(Shape,SubShape)
~~~~~~~~~~~~~~~~~~
返回值：Shape

说明：两个图元的差集，Shape中不包含SubShape的部分。

CombineTypeIntersection(Shape1,Shape2)
~~~~~~~~~~~~~~~~~~
返回值：Shape

说明：求两个图元的交集，Shape1、Shape2的公共部分。

CombineTypeSymmetricalDifference(Shape1,Shape2)
~~~~~~~~~~~~~~~~~~
返回值：Shape

说明：两个图元的异或集，Shape1和Shape2之间非公共部分。

CombineTypeUnion(Shape1,Shape2)
~~~~~~~~~~~~~~~~~~
返回值：Shape

说明：求两个图元的并集，新的图元包含Shape1、Shape2。

DegreesToDigital(String)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将度分秒格式的经纬度转化为数字，例如：108°54′36″转为 108.91 或是 108 54 36转为108.91。

DigitalToDegrees(Double)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将数字经纬度转为度分秒格式,如：108.91 转为 108°54′36″。

DigitalToDegrees(Double,DecimalPlace)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将数字经纬度转为度分秒格式,如：108.91 转为 108°54′36″。 DecimalPlace其中DecimalPlace定义秒的小数位，默认为6位

DistanceByDegree(Shape1,Shape2)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：计算两个图元的距离，图元坐标为经纬度，距离单位为度。

DistanceByMeter(Shape1,Shape2)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：计算两个图元的距离，图元坐标为经纬度，距离单位为米。

EndPoint(Shape)
~~~~~~~~~~~~~~~~~~
返回值：Point

说明：返回图元Shape的最后一个端点；Shape为折线或多边形图元。

Extent2Polygon(String)
~~~~~~~~~~~~~~~~~~
返回值：Polygon

说明：返回边界矩形；式中String“XMin，XMax，YMin，YMax”为边界的最值(X-long,Y-Lat)。

Extent2Polygon(XMin,XMax,YMin,YMax)
~~~~~~~~~~~~~~~~~~
返回值：Polygon

说明：返回边界矩形；式中“XMin，XMax，YMin，YMax”为边界的最值(X-long,Y-Lat)。

Extent2Polyline(XMin,XMax,YMin,YMax)
~~~~~~~~~~~~~~~~~~
返回值：Polyline

说明：返回边界矩形线；式中“XMin，XMax，YMin，YMax”为边界的最值(X-long,Y-Lat)。

FeatureInPolygon(Feature,Polygon)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判断图元Feature是否在图元Polygon之内。

FirstPoint(Shape)
~~~~~~~~~~~~~~~~~~
返回值：Point

说明：返回图元Shape的第一个端点；Shape为折线或多边形图元。

Generalize(Shape,Double Threshold)
~~~~~~~~~~~~~~~~~~
返回值：Polygon

说明：减少多边形或折线中的端点数,dist为阈值（单位:米）

GetAddress(string lng,string lat)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：逆地理编码，即逆地址解析，由百度经纬度信息得到结构化地址信息。

GetAddress(string lng,string lat,bool hasdesc)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：逆地理编码，即逆地址解析，由百度经纬度信息得到结构化地址信息；hasdesc为真返回详细信息。

GetCoordinate(string address)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：地理编码：地址解析，由详细到街道的结构化地址得到百度经纬度信息。

GetCoordinate(string address,bool toshape)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：地理编码：地址解析，由详细到街道的结构化地址得到百度经纬度信息； toshape为真，返回点图元。

HDGIS2Polygon(String)
~~~~~~~~~~~~~~~~~~
返回值：Polygon

说明：将HDGIS明码多边形转为Polygon。

LLToBeijing54_3(Real Longitude ,Real Latitude ,Bool IsY)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将经纬度坐标转换为北京54的3度分带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

LLToBeijing54_6(Real Longitude ,Real Latitude ,Bool IsY)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将经纬度坐标转换为北京54的6度分带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

LLToXian80_3(Real Longitude ,Real Latitude ,Bool IsY)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将经纬度坐标转换为西安80的3度分带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

LLToXian80_6(Real Longitude ,Real Latitude ,Bool IsY)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将经纬度坐标转换为西安80的6度分带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

MapIdNew(Double Longitude,Double Latitude,String Scale)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回坐标对应的新图幅号。Longitude为经度，Latitude为纬度，Scale为例尺S100W, S50W, S25W, S10W, S5W, S2_5W, S1W, S5K。

MapIdNew2Old(String MapIdNew)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回新图幅号对应的旧图幅号。

MapIdOld(Double Longitude,Double Latitude,String Scale)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回坐标对应的旧图幅号。Longitude为经度，Latitude为纬度，Scale为例尺S100W, S50W, S25W, S10W, S5W, S2_5W, S1W, S5K。

MapIdOld2New(String MapIdOld)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回旧图幅号对应的新图幅号。

PointInPolygon(Polygon,X,Y)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判断点是否在多边形内，X为点横坐标（经度），Y为点纵坐标（纬度）。点在多边形内返回真（1），否则返回值假（0）。

PointInPolygon2(PolygonWKB,X,Y)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判断点是否在多边形内，式中WKB为多边形边界(WKB格式)，X为点横坐标（经度），Y为点纵坐标（纬度）。点在多边形内返回真（1），否则返回值假（0）。

PointX(Point)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回点图元的X坐标。

PointY(Point)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回点图元的Y坐标。

PolygonArea(Polygon)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回多边形的面积。

PolygonArea(Polygon,EPSG)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回多边形的面积；EPSG为坐标系编号，WGS 84为4326；北京为4214；西安80为4610。

ProjectionTransformation(Real X,Real Y,Int sourceEpsg, Int targetEpsg,Bool IsY)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：坐标投影变换，坐标(X,Y)如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

ShapeContain(ShapeA,ShapeB)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判断图元ShapeA是否包含图元ShapeB。

ShapeDisjoint(ShapeA,ShapeB)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判断图元ShapeA是否与图元ShapeB相离。

ShapeExtent(Shape)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回多边形的边界；返回值“XMin，XMax，YMin，YMax”(X-long,Y-Lat)。

ShapeExtent(Shape,Type)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回多边形的边界；Type为边界值类型：0为XMin，1为XMax，2为YMin，3为YMax。

ShapeIntersect(ShapeA,ShapeB)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判断图元ShapeA与图元ShapeB是否相交。

ShapeLength(Poly)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回多边形或折线的周长；坐标系为西安80。

ShapeLength(Poly,EPSG)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回多边形或折线的周长；EPSG为坐标系编号，WGS 84为4326；北京为4214；西安80为4610。

ShapeNumParts(Shape)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回图元的组成部分数；Shape为折线或多边形图元。

ShapeOverlap(ShapeA,ShapeB)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判断图元ShapeA是否与图元ShapeB重叠。

ShapePointCount(Shape)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回图元的端点数；Shape为折线或多边形图元。

ShapeTouch(ShapeA,ShapeB)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判断图元ShapeA是否与图元ShapeB接触。

ShapeType(Shape)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回图元的类型；Shape为图元。

ShapeWithIn(ShapeA,ShapeB)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判断图元ShapeB是否包含图元ShapeA。

Smooth(Shape,Integer factor)
~~~~~~~~~~~~~~~~~~
返回值：Polygon

说明：图元平滑Shape为多边形或折线，Factor为平滑因子（单位:米）

ToLine(Point1，Point2...)
~~~~~~~~~~~~~~~~~~
返回值：Polyline

说明：将点图元连成线图元。

ToLine2(Points)
~~~~~~~~~~~~~~~~~~
返回值：Polyline

说明：将点图元连成线图元。参数Points是逗号分隔的点图元集（字符串）。

ToPoint(lon,lat)
~~~~~~~~~~~~~~~~~~
返回值：Point

说明：将经纬度坐标转化点图元。

WGS84ToBmap(string coord)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将gooleMap坐标转换为百度坐标，coord为'lng,lat'。

WGS84ToBmap(string coord,bool toshape)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将gooleMap坐标转换为百度坐标，toshape为真，返回点图元。

WGS84ToBmapOnline(string coord)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：通过百度地图API，将gooleMap坐标转换为百度坐标，coord为'lng,lat'。

WGS84ToBmapOnline(string coord,bool toshape)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：通过百度地图API，将gooleMap坐标转换为百度坐标，toshape为真，返回点图元。

Xian80ToBeijing54(Real X,Real Y,Bool IsY)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将西安80坐标转换为北京54，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

Xian80toLL(Real X,Real Y,Bool IsLongitude)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将西安80坐标转换为经纬度坐标（只适应于鄂尔多斯盆地）。式中西安80坐标（X,Y）,X为横坐标(东方向)，Y为纵坐标(北方向)；如IsLongitude为True或1，返回经度值；否则返回纬度值。

Xian8_3To6(Real X,Real Y,Bool IsY)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将西安80的三度带坐标转换为六度带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

Xian8_6To3(Real X,Real Y,Bool IsY)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将西安80的六度带坐标转换为三度带坐标，如IsY为True或1，返回横坐标Y；否则返回纵坐标X。

列表函数
-----------------

CountEqual(Item,List)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回字段列表中等于Item的值的个数；如果Item为空，则返回空值。

CountGreaterThan(Item,List)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回字段列表中大于Item的值的个数；如果Item为空，则返回空值。

CountLessThan(Item,List)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回字段列表中小于Item的值的个数；如果Item为空，则返回空值。

CountNotEqual(Item,List)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回字段列表中不等于Item的值的个数；如果Item为空，则返回空值。

CountNulls(List)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回列表中空值的个数。

FirstGreaterThan(Item,List)
~~~~~~~~~~~~~~~~~~
返回值：Number

说明：返回列表中第一个大于Item的元素

FirstIndex(Item,List)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回字段列表中包含Item 的第一个字段的索引，如果找不到该值，则返回-1。

FirstLessThan(Item,List)
~~~~~~~~~~~~~~~~~~
返回值：Number

说明：返回列表中第一个小于Number的元素

FirstNonNull(List)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：返回所提供字段列表中的第一个非空值。支持所有存储类型。

FirstNonNullIndex(List)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回字段列表中包含非空值的第一个字段的索引，如果所有值都为空值，则返回-1。

FirstOne(List)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：返回列表中第一个元素

ItemsCountBetween(List,CountMin,CountMax)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回子列表，其元素的个数界于CountMin与CountMax之间。

ItemsCountBetween(List,CountMin,CountMax,IsPercent)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回子列表，其元素的个数界于CountMin与CountMax之间；IsPercent布尔型，为真CountMin、CountMax为百分比。

ItemsCountGreaterThan(List,CountMin)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回子列表，其元素的个数大于等于CountMin。

ItemsCountGreaterThan(List,CountMin,IsPercent)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回子列表，其元素的个数大于等于CountMin；IsPercent布尔型，为真CountMin为百分比。

ItemsCountLessThan(List,CountMax)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回子列表，其元素的个数小于等于CountMax。

ItemsCountLessThan(List,CountMax,IsPercent)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回子列表，其元素的个数小于等于CountMax；IsPercent布尔型，为真CountMax为百分比。

LastGreaterThan(Item,List)
~~~~~~~~~~~~~~~~~~
返回值：Number

说明：返回列表中最后一个大于Number的元素

LastIndex(Item,List)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回字段列表中包含Item 的最后一个字段的索引，如果找不到该值，则返回-1。

LastLessThan(Item,List)
~~~~~~~~~~~~~~~~~~
返回值：Number

说明：返回列表中最后一个小于Number的元素

LastNonNull(List)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：返回所提供字段列表中的最后一个非空值。支持所有存储类型。

LastNonNullIndex(List)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回指定字段列表中包含非空值的最后一个字段的索引，如果所有值都为空值，则返回-1。支持所有存储类型。

LastOne(List)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：返回列表中最后一个元素

ListCount(List)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回列表长度。

ListDistinct(List)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：剔除列表重复组元

ListDistinct(List,Desc)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：剔除列表重复组元,Desc根据字符串出现的次数进行排序，真为逆序，假为正序。

ListExcept(List,SubList)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：返回由列表List中不在列表SubList中的组元集合（差集）。

ListIntersect(List1,List2)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：返回由列表List1和列表List2的共公子集合（交集）。

ListItemsCount(List)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回列表每个元素的个数。

ListItemsCount(List,IsPercent)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回列表每个元素的个数或比例,IsPercent布尔型，为真输出元素占元素总数的百分比。

ListJoinToString(List,GroupCount,GroupSpliter,Spliter)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将列表以分组形式，合并成字符串；GroupCount，指定组内元素数；GroupSpliter，组间字符间隔；Spliter，组内字符间隔。

ListJoinToString(List,String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将列表合并成字符串，以String指定的字符分隔。

ListSort(List)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：列表排序，正序

ListUnion(List1,List2)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：将列表List1和列表List2合并成一个列表（并集）。

RemoveMembers(List,IndexList)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：从List列表删除IndexList列表指定位置的元素。

StringListSimplify(List,Count)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将字符串列表，以简化方式显示，如List中有A、B、C、D个元素，Count为2，输出结果为A、B等4个。

StringListSimplify(List,Count,stringAppend)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将字符串列表，以简化方式显示，如List中有A、B、C、D个元素,stringAppend为条，Count为2，输出结果为A、B等4条。若stringAppend为空，则不返出总数值。

SubList(List,N)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：截取子列表，返回从N开始的所有子元素组成的列表,N从1开始计数。

SubList(List,N,LEN)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：截取子列表，返回从N开始的LEN个子元素组成的列表,N从1开始计数。

SubListIndexs(List,SubList)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：返回List列表中SubList列表子元素的位置列表。

ToStringlist(String)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：将字符串转化为字符串列表，以, 。、;:"分隔，转换过程中将删除空值组元,同：ToStringlist(String,true)

ToStringlist(String,Boolean)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：将字符串转化为字符串列表，以, 。、;:"分隔；Boolean指定是否删除空值组元。

ToStringlist(String,Boolean,SplitChars)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：将字符串转化为字符串列表，组元以SplitChars指定的字符分隔；Boolean指定是否删除空值组元。

ToStringlistFixedWidth(String,string)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：根据列宽，将字符串转化为字符串列表。

ValueAt(Integer,List)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：返回列表中Integer处的值；如果偏移超出了有效值的范围（即小于0或大于所列字段的个数），则返回空值。

max_index(List)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回列表中最大元素的位置

max_n(List)
~~~~~~~~~~~~~~~~~~
返回值：Number

说明：返回列表中最大元素

maxlength_n(List)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回列表中最长元素

member(Item,List)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：如果Item 为指定List 的成员，则返回真值。否则返回假值

min_index(List)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回列表中最小元素的位置

min_n(List)
~~~~~~~~~~~~~~~~~~
返回值：Number

说明：返回列表中最小元素

minlength_n(List)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回列表中短元素

统计
-----------------

@AutoCorrelation( FieldA , FieldB )
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：自相关系数。可用于判断两道曲线的相似程度。如果用方差 σ2 进行归一化处理，那么自协方差就变成了自相关系数 R(k)。在信息分析中，通常将自相关函数称之为自协方差方程。 用来描述信息在不同时间τ的，信息函数值的相关性。

@CountIF( Expression )
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：统计符合指定条件的值个数。

@CovarianceP( FieldA , FieldB )
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回总体协方差，即两个数据集中每对数据点的偏差乘积的平均数。

@CovarianceS( FieldA , FieldB )
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回样本协方差，即两个数据集中每对数据点的偏差乘积的平均值。

@First( Field )
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：返回第一个数据值

@InformationEntropy( Field )
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：求一组数据的信息熵。

@Kurtosis( Field )
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：峰度系数，峰度是用来反映频数分布曲线顶端尖峭或扁平程度的指标

@Last( Field )
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：返回最后一个数据值

@ListAgg( Field , Char )
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将字段内容连接成一个字符串

@MaxIF( Field , Expression )
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：对字段中符合指定条件的最大值。

@MaxIFByNumber( Field , Expression )
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：对字段中符合指定条件的最大值。

@MinIF( Field , Expression )
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：对字段中符合指定条件的最小值。

@MinIFByNumber( Field , Expression )
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：对字段中符合指定条件的最小值。

@Quartile( Field , Percent )
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：第Percent百分位数，将Field的数据从小到大排序，处于Percent位置的值，0<=Percent<=100。

@Skew( Field )
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：Skew

@SkewP( Field )
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：SkewPop

@StdDevP( Field )
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：StdDevPop

@StdDevS( Field )
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：StdDevSamp

@SumIF( Field , Expression )
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：对字段中符合指定条件的值求和。

@VarP( Field )
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：VariancePop

@VarS( Field )
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：VarianceSamp

@avg(FIELD)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：平均值，与@mean函数相同，返回字段的平均值，忽略空值记录。如果字段中没有非空数值，返回NULL。

@count(FIELD)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：计数，返回字段的记录数，忽略空值记录。

@group_concat(FIELD)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：连接字符串，用字符“,”连接字段中所有数据项，忽略空值记录。

@group_concat(FIELD,STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：连接字符串，用字符“STRING”连接字段中所有数据项，忽略空值记录。

@lower_quartile(FIELD)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：第一个四分位数（第 25 个百分点值）。统计学中，把从小到大排列好的数值看作四等分时的三个分割点称为四分位数。

@max(FIELD)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：最大值，返回字段中最大数值，忽略空值记录。如果字段中没有非空数值，返回NULL。

@mean(FIELD)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：平均值，与@avg函数相同，返回字段的平均值，忽略空值记录。如果字段中没有非空数值，返回NULL。

@median(FIELD)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：中位数，返回在字段中居于中间的数值；在字段中，一半数字的值大于中位数,一半数字的值小于中位数。

@min(FIELD)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：最小值，返回字段中最小数值，忽略空值记录。如果字段中没有非空数值，返回NULL。

@mode(FIELD)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：众数，返回字段中出现频率最多的数值。

@stdev(FIELD)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：标准偏差，又称均方差，一般用σ表示。反映数值相对于平均值(mean) 的离散程度。标准偏差越小，这些值偏离平均值就越少，反之亦然。

@sum(FIELD)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：求和，返回字段中非空数值和。如果字段中没有非空数值，返回NULL。

@total(FIELD)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：求和，返回字段中非空数值和，始终返回浮点数。如果字段中没有非空数值，返回0.0

@upper_quartile(FIELD)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：第三个四分位数（第 75 个百分点值）。统计学中，把从小到大排列好的数值看作四等分时的三个分割点称为四分位数。

@variance(FIELD)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：方差，返回各个数值与其算术平均数的离差平方和的平均数，通常以σ2表示。

HTML函数
-----------------

GetHtmlCellValue(String HtmlTable,Int ColumnID,Int RowID)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回HTML表格中单元格的值。

GetHtmlColumnID(String HtmlTable,String SubString)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：检索HTML表格第一行中，返回第一个包含subString的列号。

GetHtmlColumnID(String HtmlTable,String SubString,Int RowID)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：检索HTML表格第RowID行中，返回第一个包含subString的列号,编号从1开始。

GetHtmlColumnID(String HtmlTable,String SubString,Int RowID,Int BeginColumnID)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：检索HTML表格第RowID行中，返回第一个包含subString的列号,编号从1开始；BeginRowID为起始行。

GetHtmlRowID(String HtmlTable,String SubString)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：检索HTML表格第一列中，返回第一个包含subString的行号。

GetHtmlRowID(String HtmlTable,String SubString,Int ColumnID)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：检索HTML表格第ColumnID列中，返回第一个包含subString的行号,编号从1开始。

GetHtmlRowID(String HtmlTable,String SubString,Int ColumnID,Int BeginRowID)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：检索HTML表格第ColumnID列中，返回第一个包含subString的行号,编号从1开始；BeginRowID为起始行。

HtmlA(Text,URl)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：生成Html超链接标记。注：GoogleEarth不支持本地文件

HtmlBr()
~~~~~~~~~~~~~~~~~~
返回值：String

说明：生成Html插入换行符标记。

HtmlContentCompress(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：网页内容压缩工具。

HtmlContentCompressEx(Byte[])
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：网页内容压缩工具。

HtmlContext(URL,WebEncoding Text)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：下载网址的内容。URL为网页地址;WebEncoding为网页编码,支持gb2312，UTF8,默认UTF8。从网上获取数据，超慢，建议缓存。

HtmlContext(URL,WebEncoding Text,int second)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：下载网址的内容。URL为网页地址;WebEncoding为网页编码,支持gb2312，UTF8,默认UTF8；second为下载间隔秒数。从网上获取数据，超慢，建议缓存。

HtmlDecode(STRING)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将编码的汉字转换成可读的汉字,如“&#36827;&#20837;”转化为“进入”

HtmlDownload(URL)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：下载URL到指的文件,以byte[]方式存储在字段中。

HtmlDownload(URL,int second)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：下载URL到指的文件,以byte[]方式存储在字段中，second为下载间隔秒数。

HtmlExtract(String HtmlText)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：从HTML文本中，抽取文本。

HtmlExtract(String HtmlText,String TagPath)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：从HTML文本中，抽取文本，其中参数TagPath,指定标签的路径。例如LI[1].A[3][href];末端标记中：无、[]、[0]代表所有；非末端标记中：无、[]、[0]代表1；属性如href，仅对末端标记起作用。

HtmlExtract(String HtmlText,String TagPath,Bool IsHtml)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：从HTML文本中，抽取文本，其中参数TagPath,指定标签的路径。例如LI[1].A[3][href];末端标记中：无、[]、[0]代表所有；非末端标记中：无、[]、[0]代表1；属性如href，仅对末端标记起作用。

HtmlImg(URl)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：生成Html图像标记。

HtmlImg(URl,Width,Height)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：生成Html图像标记。

HtmlImgBase64(URl)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：生成Html嵌入式图像标记。

HtmlImgBase64(URl,Width)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：生成Html嵌入式图像标记。

HtmlImgBase64(URl,Width,Height)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：生成Html嵌入式图像标记。

HtmlSpace(count)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：生成Html插入空格符标记;其中Count代表返回的空格数。

HtmlTagsCount(String HtmlText,String TagPath)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：获取HTML源码中标签组的数量。格式为LI[1].A[3][href];末端标记中：无、[]、[0]代表所有；非末端标记中：无、[]、[0]代表1；属性如href，仅对末端标记起作用。

HttpGet(URL,postDataStr)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：模拟http发送Get请求，获取网页

HttpPost(URL,postDataStr)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：模拟http发送post请求，获取网页

URLCapture(String URL)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：将URL地址的内容转换为图片（PNG）。

URLCapture(String URL,Int width)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：将URL地址的内容转换为图片（PNG）,width指定截取窗体的宽度。

URLCapture(String URL,Int width,Int height)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：将URL地址的内容转换为图片（PNG）,width指定截取窗体的宽度,height指定截取窗体的高度。

转换函数
-----------------

Base642Byte(String)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：将Base64字符串转化为Byte[]。

Base642String(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将Base64格式转化为字符串。

Byte2Base64(Byte[])
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将Byte[]转化为Base64字符串。

Compress(byte[])
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：采用ZIP方法，压缩基础流。

Data2Base64(Byte[],streamtype)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将Byte[]文件转化为Base64字符串（Data URI scheme），streamtype为文件扩展名，如data:image/png;base64,iVBORw0K

Decompress(byte[])
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：采用ZIP方法，解压基础流。

Decrypt(byte[],byte[])
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：解密

Encrypt(byte[],byte[])
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：加密

F(FormatString)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：Format函数的简化版，用 {变量:格式} 代替原有的{0}占位方式，如：F('{列1:F2} {列2:N1}') 用法可参考C#的$格式化函数

Format(FormatString,Item1,Item2...)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将指定Item转换为字符串。如：Format( "{0} 井 {1:yyyy-MM-dd}~{2:MM-dd} 生产曲线" ,Xi33,2013-5-1,2013-7-1)

GetNumber(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：提取字符串中第1个整数或实数。

GetNumber(String,Index)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：提取字符串中的数值，整数或实数。其中Index整数，表示第Index个数值。

GetNumber(String,Index,NegativeNumber,RealNumber)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：提取字符串中的数值，整数或实数。其中其中Index整数，表示第Index个数值；NegativeNumber布尔型，是否支持负数；RealNumber布尔型，是否支持实数。

GetNumbers(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：提取字符串中的所有数值，整数或实数

GetNumbers(String,NegativeNumber,RealNumber)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：提取字符串中的数值，整数或实数。其中NegativeNumber布尔型，是否支持负数；RealNumber布尔型，是否支持实数。

HexDecode( String )
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：Decodes a string of hex characters to their underlying binary format

HexEncode( byte[] )
~~~~~~~~~~~~~~~~~~
返回值：String

说明：Encodes a bit of binary data as a string of hex characters

String2Base64(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将字符串转化为Base64格式。

ToBool(Item)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：将指定Item转换为布尔型；真值：True、不为零的整数或实数；假值：False、0、0.0。

ToDoublelist(String)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：将字符串转化为实数列表，以, 。、;:"分隔，转换过程中将删除空值组元,同：ToDoublelist(String,true)

ToDoublelist(String,Boolean)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：将字符串转化为实数列表，以, 。、;:"分隔；Boolean指定是否删除空值组元。

ToDoublelist(String,Boolean,SplitChars)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：将字符串转化为实数列表，组元以SplitChars指定的字符分隔；Boolean指定是否删除空值组元。

ToFieldname(Item)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将指定Item标准化为系统支持的字段名称。

ToInteger(Item)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：将指定Item转换为整数。

ToIntegerlist(String)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：将字符串转化为整数列表，以, 。、;:"分隔，转换过程中将删除空值组元,同：ToIntegerlist(String,true)

ToIntegerlist(String,Boolean)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：将字符串转化为整数列表，以, 。、;:"分隔；Boolean指定是否删除空值组元。

ToIntegerlist(String,Boolean,SplitChars)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：将字符串转化为整数列表，组元以SplitChars指定的字符分隔；Boolean指定是否删除空值组元。

ToList(Itme1,Itme2...)
~~~~~~~~~~~~~~~~~~
返回值：List

说明：构造列表

ToReal(Item)
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：将指定Item转换为实数，小数据精度为6位。

ToString(Item)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将指定Item转换为字符串。

ToString(Item,Integer)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将指定Item转换为字符串,保留Integer位数。

文件相关
-----------------

Base642String(String,string Encoding)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将Base64格式转化为字符串，Encoding定义编码，支持：Default，ASCII，BigEndianUnicode，UTF32，UTF7，UTF8,UTF8_NO_BOM和Unicode。

Byte2String(Byte[])
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将Byte数组转化为字符串，编码为Default

Byte2String(Byte[],string Encoding)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将Byte数组转化为字符串，Encoding定义编码，支持：Default，ASCII，BigEndianUnicode，UTF32，UTF7，UTF8,UTF8_NO_BOM和Unicode。

CRC32(byte[])
~~~~~~~~~~~~~~~~~~
返回值：String

说明：Works on binary data, will calculate a 32bit CRC

FileStream(FileName)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：将文件加载到流程中。

GetDirectoryName(String FileName)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回文件路径，FileName为文件的路径。

GetDirectoryName(String FileName,Int Level)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回指层级的目录名称，FileName为文件的路径; Level指定返回第几层的目录名称，正值为从前向后，负值为从后向前。

GetExtension(FileName)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回文件的扩展名，FileName为文件的路径。

GetFileEncodeType(File)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：获文件的编码方式，参数File，可为文件数据体，可为文件路径。

GetFileName(FileName)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回文件名，FileName为文件的路径。

GetFileNameWithoutExtension(FileName)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回不含扩展名的文件名，FileName为文件的路径。

MD5(byte[])
~~~~~~~~~~~~~~~~~~
返回值：String

说明：Creates a MD5 hash on binary data

RIPEMD160(byte[])
~~~~~~~~~~~~~~~~~~
返回值：String

说明：Creates a RIPEMD160 hash on binary data

RemoveInvalidFileNameChars(FileName)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除文件名中，非法字符。

SHA1(byte[])
~~~~~~~~~~~~~~~~~~
返回值：String

说明：Creates a SHA1 hash on binary data

SHA256(byte[])
~~~~~~~~~~~~~~~~~~
返回值：String

说明：Creates a SHA2 hash on binary data

SHA384(byte[])
~~~~~~~~~~~~~~~~~~
返回值：String

说明：Creates a SHA256 hash on binary data

SHA512(byte[])
~~~~~~~~~~~~~~~~~~
返回值：String

说明：Creates a SHA512 hash on binary data

String2Base64(String,string Encoding)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将字符串转化为Base64格式，Encoding定义编码，支持：Default，ASCII，BigEndianUnicode，UTF32，UTF7，UTF8,UTF8_NO_BOM和Unicode。

String2Byte(String)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：将字符串转化为Byte数组，编码为Default

String2Byte(String,string Encoding)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：将字符串转化为Byte数组，Encoding定义编码，支持：Default，ASCII，BigEndianUnicode，UTF32，UTF7，UTF8和Unicode。

图像处理
-----------------

BarCode2D(string info,string displayName)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：根据信息生成二维码图片。

BarCode2D(string info,string displayName,string LogoImage)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：根据信息生成二维码图片。

BarCode2D(string info,string displayName,string LogoImage,int FontSize)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：根据信息生成二维码图片。

ColumnBppCount(Byte[] Image)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将图像二值化，返回每一列的有值像数个数。

ColumnBppCount(Byte[] Image, Int step)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将图像二值化，并进行平滑处理，返回每一列的有值像数个数；step指定平滑步长。

GetImageExif(string Image)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：获取图像的描述信息。

GetImageExif(string Image,string tagName)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：获取图像的描述信息。

ImageAddDesc(Byte[] Image,string)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：在图片上添加一段文字。

ImageClone(Byte[] Image,int left, int top, int right, int bottom)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：复制指定区域内的图像内容。

ImageFlipX(Byte[] SourceImage)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：图像水平翻转。

ImageFlipY(Byte[] SourceImage)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：图像垂直翻转。

ImageInfo(Byte[] Image)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：获取图像的基本信息,输出信息Width,Height,HorizontalResolution,VerticalResolution。

ImageRotate(Byte[] SourceImage,double Angle)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：图像旋转Angle度；Angle为角度（-360~360），正值为顺时针旋转，负值为逆时针旋转。

ImageToGray(Byte[] Image)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：图像二值化。

JPG(Byte[] SourceImage)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：将图片压缩成JPG格式

JPG(Byte[] SourceImage,int Quality)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：将图片压缩成JPG格式；Quality为压缩图像质量（0~100）。

JPG(Byte[] SourceImage,int Quality,int MaxWidth)
~~~~~~~~~~~~~~~~~~
返回值：Byte[]

说明：将图片压缩成JPG格式；Quality为压缩图像质量（0~100），MaxWidth为最大宽度。

RowBppCount(Byte[] Image)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将图像二值化，返回每一行的有值像数个数。

RowBppCount(Byte[] Image, Int step)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将图像二值化，并进行平滑处理，返回每一行的有值像数个数；step指定平滑步长。

信息函数
-----------------

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

IsDBNull(Item)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：空值判断，如果表达式Item的值为空，返回真（1），否则返回假（0）。

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

RemoveChinese(Item)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除字符串中的所有中文。

null
~~~~~~~~~~~~~~~~~~
返回值：null

说明：空。

typeof(ITEM)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回函数参数数据类型的字符串表示形式，如"integer、text、real、null"等。

比较函数
-----------------

IN
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判断值在规定的多个值之中，双目运算符。例：x IN( y,z,...)

Item1  >= Item2
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：大于等于，双目运算符。若Item1大于等于Item2返回为真值(1)，否则返回假值(0)。

Item1 != Item2
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：不等于，双目运算符，与<>相同。若Item1不等于Item2返回为真值(1)，否则返回假值(0)。

Item1 < Item2
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：小于，双目运算符。若Item1小于Item2返回为真值(1)，否则返回假值(0)。

Item1 <= Item2
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：小于等于，双目运算符。若Item1小于等于Item2返回为真值(1)，否则返回假值(0)。

Item1 <> Item2
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：不等于，双目运算符，与!=相同。若Item1不等于Item2返回为真值(1)，否则返回假值(0)。

Item1 = Item2
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：等于，双目运算符，与==相同。若Item1等于Item2返回为真值(1)，否则返回假值(0)。

Item1 == Item2
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：等于，双目运算符，与=相同。若Item1等于Item2返回为真值(1)，否则返回假值(0)。

Item1 > Item2
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：大于，双目运算符。若Item1大于Item2返回为真值(1)，否则返回假值(0)。

Item1 IS Item2
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：是，双目运算符。当两个参数都为Null时，返回1（真）；当一个参数都为Null时，返回0（假）；当两个参数都不为空时，与=运算符相同。

Item1 IS NOT Item2
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：不是，双目运算符。当两个参数都为Null时，返回0（假）；当一个参数都为Null时，返回1（真）；当两个参数都不为空时，与!=运算符相同。

NOT IN
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判断值不在规定的多个值之中，双目运算符。例：x NOT IN( y,z,...)

max(Number,...)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：返回函数参数中的最大值，如果有任何一个参数为NULL，则返回NULL。

min(Number,...)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：返回函数参数中的最小值，如果有任何一个参数为NULL，则返回NULL。

逻辑函数
-----------------

CASE Item1 WHEN Item2 THEN Item3 WHEN Item4 THEN Item5 ELSE Item6 END
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：条件语句。例：CASE x WHEN w1 THEN r1 WHEN w2 THEN r2 ELSE r3 END

CASE WHEN Item1 THEN Item2 WHEN Item3 THEN Item4 ELSE Item5 END
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：条件语句。例：CASE WHEN x=w1 THEN r1 WHEN x=w2 THEN r2 ELSE r3 END

Cond1 and Cond2
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：并且，双目逻辑运算符。当Cond1 与Cond2同时为真时返回真值。如果Cond1为假，则不求Cond2的值。

Cond1 or Cond2
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：或，双目逻辑运算符。当Cond1或Cond2为真或这两者同时为真时，返回真值。如果Cond1为真，则不求Cond2的值。

Item1 between Item2 and Item3
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：界于之间，三目逻辑运算符。例："x BETWEEN y AND z"等同于"x  >=y AND x< =z"。

NullIf(expr1, expr2)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：如果两个表达式相等，NullIf返回空值NULL,否则返回expr1的值。

decode(value, if1, then1, if2,then2, if3,then3, … else )
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：逻辑处理函数。类似于If-Then-Else进行逻辑判断。Value 代表某个表的任何类型的任意列或一个通过计算所得的任何结果。当每个value值被测试，如果value的值为if1，Decode 函数的结果是then1；如果value等于if2，Decode函数结果是then2；等等。

false
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：表示逻辑假值。

iif(Cond,TrueItem,FalseItem)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：条件函数。如果条件Cond满足(为真)，返回表达式TrueItem的值，否则表达式FalseItem的值。

not( Cond )
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：非，单目逻辑运算符。如果Cond为假，则返回真。否则，此运算将返回值0。

nvl(expr1, expr2)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：如果expr1不为NULL，则返回expr1的值；expr1为NULL，返回expr2的值。注：expr1和expr2必须为同一数据类型。

nvl2(Expression, IsNotNullItem, IsNullItem)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：如果Expression不为NULL，则返回IsNotNullItem；expr1为NULL，返回IsNullItem。

true
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：表示逻辑真值。

油田专用
-----------------

AppendWellHeaders(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：补全井头的汉字。按常见字符分隔字符串String，返回补全汉字字头以“.”隔的字符串，如井12，23->井12，井23。其中井头最大汉字数为4。

AppendWellHeaders(String,MaxLen)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：补全井头的汉字。按常见字符分隔字符串String，返回补全汉字字头以“.”隔的字符串，如井12，23->井12，井23。参数MaxLen为井头最大汉字数。

AppendWellHeaders(String,MaxLen,SplitChars)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：补全井头的汉字。按SplitChars指定的字符分隔字符串String，返回补全汉字字头以SplitChar隔的字符串，如井12，23->井12，井23。参数MaxLen为井头最大汉字数。

GetWellName(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：从字符串中，猜出井名

GetWellName(String,Headers,MiddleChinese,HeaderMaxLen,MiddleStringMaxLen,MaxIDCount)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：从字符串中，猜出井名；Headers指定井头；MiddleChinese指定井号中可出现的汉字，默认为空；HeaderMaxLen指定井字头的长度，默认为2；MiddleStringMaxLen排号中最大字符长度，默认为5；MaxIDCount最大排数，默认为3

RemoveWellHeaders(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除重复井头的汉字。按常见字符分隔字符串String，返回删除重复井汉字头以“.”隔的字符串，如井12，井23->井12，23。其中井头最大汉字数为4。

RemoveWellHeaders(String,MaxLen)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除重复井头的汉字。按常见字符分隔字符串String，返回删除重复井汉字头以“.”隔的字符串，如井12，井23->井12，23。参数MaxLen为井头最大汉字数。

RemoveWellHeaders(String,MaxLen,SplitChars)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：删除重复井头的汉字。按SplitChars指定的字符分隔字符串String，返回删除重复井汉字头以SplitChar隔的字符串，如井12，井23->井12，23。参数MaxLen为井头最大汉字数。

SplitWellHeaders(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：劈分连续的井头，按常见字符分隔字符串String，如井12井23->井12.井23。其中井头最大汉字数为4。

SplitWellHeaders(String,MaxLen)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：劈分连续的井头，按常见字符分隔字符串String，如井12井23->井12.井23。参数MaxLen为井头最大汉字数。

SplitWellHeaders(String,MaxLen,SplitChars)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：劈分连续的井头，按SplitChars指定的字符分隔字符串String，如井12井23->井12，井23。参数MaxLen为井头最大汉字数。

批处理命令
-----------------

Rename(FileName,NewFileName)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：合成重命名批处理命令。

copy(FileName,NewFileName)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：合成文件复制批处理命令。

del(Path)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：合成删除文件批处理命令。

md(Path)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：合成创建文件夹批处理命令。

move(FileName,NewFileName)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：合成移动文件批处理命令。

rd(Path)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：合成删除文件夹批处理命令。

位运算函数
-----------------

&
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：按位与，双目运算符。

<<
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：位左移，双目运算符。

>>
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：位右移，双目运算符。

|
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：按位或，双目运算符。

~
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：按位非，单目运算符。

空间统计
-----------------

@ShapeDifference( Shape )
~~~~~~~~~~~~~~~~~~
返回值：Shape

说明：按组别求多个图元的差集。

@ShapeDifference2( Shape )
~~~~~~~~~~~~~~~~~~
返回值：Shape

说明：按组别求多个图元的差集,逆向。

@ShapeIntersection( Shape )
~~~~~~~~~~~~~~~~~~
返回值：Shape

说明：按组别求多个图元的交集。

@ShapeSymmetricalDifference( Shape )
~~~~~~~~~~~~~~~~~~
返回值：Shape

说明：按组别求多个图元的异或集。

@ShapeUnion( Shape )
~~~~~~~~~~~~~~~~~~
返回值：Shape

说明：按组别求多个图元的并集。

随机函数
-----------------

Random()
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回整型的伪随机数,随机数介于-9223372036854775808和+9223372036854775807之间。

oneof(List)
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：返回一个从LIST 中随机选取的元素。应以[ITEM1,ITEM2,...,ITEM_N] 的形式输入列表项。注意，还可以指定字段名称列表。

random(maxInteger)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回一个小于maxInteger的非负随机数。maxInteger必须大于或等于零。返回值的范围通常包括零但不包括 maxInteger。不过，如果 maxInteger 等于零，则返回 maxInteger。

random(minInteger,maxInteger)
~~~~~~~~~~~~~~~~~~
返回值：Integer

说明：返回一个指定范围内的随机数。maxInteger 必须大于或等于 minInteger。返回值的范围包括 minInteger 但不包括 maxInteger。如果minInteger 等于 maxInteger，则返回 minInteger。

random_double()
~~~~~~~~~~~~~~~~~~
返回值：Double

说明：返回一个介于 0.0 和 1.0 之间的随机数。返回值大于等于 0.0 并且小于 1.0 的双精度浮点数。

数据缓存
-----------------

GetRedisData(KeyFieldName, Host, Port, Password, DB )
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：获取Redis的数据。

GetRedisData(KeyFieldName, Host, Port, Password, DB,timeOut )
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：获取Redis的数据；timeOut为毫秒，默认为3000。

RedisKeyExist(KeyFieldName, Host, Port, Password, DB )
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：判断Redis的Key是否存在。

RedisKeyExist(KeyFieldName, Host, Port, Password, DB,timeOut )
~~~~~~~~~~~~~~~~~~
返回值：Any

说明：判断Redis的Key是否存在；timeOut为毫秒，默认为3000。

网络相关
-----------------

ContainsIPAddress(String IPAddressRange, String IPAddress)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判别的IPAddress是否在IPAddressRange网段内，在返回真，不在返回假。 IPAddressRange支持格式'192.168.0.0/24'、'192.168.0.0/255.255.255.0'、’192.168.0.0-192.168.0.255'

ContainsIPAddressRange(IPAddressRange, SubIPAddressRange)
~~~~~~~~~~~~~~~~~~
返回值：Boolean

说明：判别IPAddressRange是否包含SubIPAddressRange网段，在返回真，不在返回假。 IPAddressRange支持格式'192.168.0.0/24'、'192.168.0.0/255.255.255.0'、’192.168.0.0-192.168.0.255'

GetIPAddressInRange(String IPAddressRange)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：返回本网段中所有的IP地址，多个IP地址用分号隔开。 IPAddressRange支持格式'192.168.0.0/24'、'192.168.0.0/255.255.255.0'、’192.168.0.0-192.168.0.255'

颜色函数
-----------------

ColorToHtml(Int Red,Int Green，Int Blue)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将颜色转换为HTML值。

ColorToHtml(List RGB)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将颜色转换为HTML值,RGB为列表，如：[202,211,223]。

ColorToHtml(String RGB)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将颜色转换为HTML值,RGB为字符串，如：202,211,223。

字符编码
-----------------

String2Unicode(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将字符串转为UniCode码字符串；如'中国'=>'\u4e2d\u56fd'

Unicode2String(String)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：将Unicode字符串转为正常字符串；如'\u4e2d\u56fd'=>'中国'

定时运行
-----------------

GetScheduler(StartTime, EndTime,ScheduleString)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：解析定时运行的时间，生成运行时间的列表。

其它
-----------------

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

GUIDParse(String)
~~~~~~~~~~~~~~~~~~
返回值：GUID

说明：将文本转换为GUID值。

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

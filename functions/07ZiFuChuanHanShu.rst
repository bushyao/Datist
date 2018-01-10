.. _ZiFuChuanHanShu:
字符串函数
======================

AllButFirst
~~~~~~~~~~~~~~~~~~
函数体： **AllButFirst(STRING,LEN)**

返回值：String

说明：返回STRING的子字符串，除去字符串STRING开始的LEN个字符。

AllButLast
~~~~~~~~~~~~~~~~~~
函数体： **AllButLast(STRING,LEN)**

返回值：String

说明：返回STRING的子字符串，除去字符串STRING结尾的LEN个字符。

AlphaBefore
~~~~~~~~~~~~~~~~~~
函数体： **AlphaBefore(String,BaseString)**

返回值：Boolean

说明：用于检查字符串的数字字母顺序。如果STRING在BaseString之前，则返回真值。

CharCommon
~~~~~~~~~~~~~~~~~~
函数体： **CharCommon(STRING1,STRING2)**

返回值：Integer

说明：对比两个字符串，返回共公的字符数。

函数体： **CharCommon(STRING1,STRING2,Bool Step)**

返回值：Integer

说明：对比两个字符串，返回共公的字符数；Step为真时，按位比较。

Count_SubString
~~~~~~~~~~~~~~~~~~
函数体： **Count_SubString(STRING,SUBSTRING)**

返回值：Boolean

说明：返回字符串中指定字符串出现的次数。例如，count_substring("foooo.txt", "oo") 返回3。

函数体： **Count_SubString(STRING,N,SUBSTRING)**

返回值：Boolean

说明：返回字符串中指定字符串出现的次数。N为搜索起始位置,其中N从0开始计数。

DefaultToUTF8
~~~~~~~~~~~~~~~~~~
函数体： **DefaultToUTF8(String Text)**

返回值：String

说明：字符串编码转换,默认编码转换为UTF8。

EndString
~~~~~~~~~~~~~~~~~~
函数体： **EndString(STRING,LEN)**

返回值：String

说明：返回STRING的子字符串，包括字符串STRING的最后的LEN个字符。与RightStr(STRING,LEN)相同。

EndsWith
~~~~~~~~~~~~~~~~~~
函数体： **EndsWith(STRING,SUBSTRING)**

返回值：Boolean

说明：如果STRING以SUBSTRING结束，返回真(1)，否则返回假(0)。

HasChars
~~~~~~~~~~~~~~~~~~
函数体： **HasChars(STRING,CHARS)**

返回值：Boolean

说明：检查字符串STRING中是否包含CHARS定义的字符，包含CHARS中任意字符返回真（1）。

HasEndString
~~~~~~~~~~~~~~~~~~
函数体： **HasEndString(STRING,SUBSTRING)**

返回值：Boolean

说明：如果STRING以SUBSTRING结束，返回真(1)，否则返回假(0)。

HasMidString
~~~~~~~~~~~~~~~~~~
函数体： **HasMidString(STRING,SUBSTRING)**

返回值：Boolean

说明：如果STRING中包含SUBSTRING，且SUBSTRING不以SUBSTRING开始或结束，返回真(1)，否则返回假(0)。

HasStartString
~~~~~~~~~~~~~~~~~~
函数体： **HasStartString(STRING,SUBSTRING)**

返回值：Boolean

说明：如果STRING以SUBSTRING开始，返回真(1)，否则返回假(0)。

HasSubString
~~~~~~~~~~~~~~~~~~
函数体： **HasSubString(STRING,SUBSTRING)**

返回值：Boolean

说明：如果STRING中包含SUBSTRING，返回真(1)，否则返回假(0)。

函数体： **HasSubString(STRING,N,SUBSTRING)**

返回值：Boolean

说明：如果STRING中包含SUBSTRING，返回真(1)，否则返回假(0)，N为搜索起始位置,其中N从0开始计数。

HasSubStringsAND
~~~~~~~~~~~~~~~~~~
函数体： **HasSubStringsAND(STRING,SUBSTRING1,SUBSTRING2,…)**

返回值：Boolean

说明：如果STRING中包含SUBSTRING1并且包括SUBSTRING2并且…，返回真(1)，否则返回假(0)。

HasSubStringsOR
~~~~~~~~~~~~~~~~~~
函数体： **HasSubStringsOR(STRING,SUBSTRING1,SUBSTRING2,…)**

返回值：Boolean

说明：如果STRING中包含SUBSTRING1或者包括SUBSTRING2或者…，返回真(1)，否则返回假(0)。

IndexOf
~~~~~~~~~~~~~~~~~~
函数体： **IndexOf(STRING,SUBSTRING)**

返回值：Integer

说明：字符串定位,返回SUBSTRING在STRING中第一个匹配的位置(第一个字符位置为1)。如果两个字符串不匹配返回0。

函数体： **IndexOf(STRING,N,SUBSTRING)**

返回值：Integer

说明：字符串定位,返回SUBSTRING在STRING中位置N之后的第一个匹配位置(第一个字符位置为1)。如果两个字符串不匹配返回0。

InsertString
~~~~~~~~~~~~~~~~~~
函数体： **InsertString(String,Id,InsertString)**

返回值：String

说明：向字符串插入指定的字符串。

IsMatch
~~~~~~~~~~~~~~~~~~
函数体： **IsMatch(String, RegexString)**

返回值：Boolean

说明：如果正则表达式匹配，返回真(1)，否则返回假(0)。

函数体： **IsMatch(String, RegexString, RegexOptions)**

返回值：Boolean

说明：如果正则表达式匹配，返回真(1)，否则返回假(0)。RegexOptions用于设置正则表达式选项的枚举值。例如：IsMatch("ASDV","^[a-z]+$","Compiled | IgnoreCase")选项值有：None,Compiled,CultureInvariant,ECMAScript,ExplicitCapture,IgnoreCase,IgnorePatternWhitespace,Multiline,RightToLeft,Singleline。

JoinItems
~~~~~~~~~~~~~~~~~~
函数体： **JoinItems(SplitChar,item1,Item2,……)**

返回值：String

说明：将多个字段内容合并成一个字符串。

JsonListItemValues
~~~~~~~~~~~~~~~~~~
函数体： **JsonListItemValues(String JsonText,String KeyName)**

返回值：String

说明：从简单Json列表中，取指定的属性值列表，元素之间以;分隔。

JsonObjectValue
~~~~~~~~~~~~~~~~~~
函数体： **JsonObjectValue(String JsonText,String PathName)**

返回值：Any

说明：从Json对象中取指定的属性值，PathName支持路径，如：routes[0].legs[0].distance.text。

JsonValue
~~~~~~~~~~~~~~~~~~
函数体： **JsonValue(String JsonText,String KeyName)**

返回值：String

说明：从Json对象中取指定的属性值，KeyName为关键字名称。

函数体： **JsonValue(String JsonText,String KeyName,String SplitChars)**

返回值：String

说明：从Json对象中取指定的属性值，KeyName为关键字名称，SplitChars为输出分隔符。

LastIndexOf
~~~~~~~~~~~~~~~~~~
函数体： **LastIndexOf(STRING,SUBSTRING)**

返回值：Integer

说明：返回子字符串的位置,从后向前匹配SUBSTRING在STRING中位置。如果两个字符串不匹配返回0。

函数体： **LastIndexOf(STRING,N,SUBSTRING)**

返回值：Integer

说明：返回子字符串的位置,从后向前匹配SUBSTRING在STRING中位置（N为从后向前计数的位置）。如果两个字符串不匹配返回0。

LCS
~~~~~~~~~~~~~~~~~~
函数体： **LCS(STRING1,STRING2)**

返回值：String

说明：LCS (Longest Common Subsequence) 算法用于找出两个字符串最长公共子串。

LeftStr
~~~~~~~~~~~~~~~~~~
函数体： **LeftStr(STRING,LEN)**

返回值：String

说明：返回STRING的左边N个字符串。

Length
~~~~~~~~~~~~~~~~~~
函数体： **Length(STRING)**

返回值：Integer

说明：如果参数STRING为字符串，则返回字符的数量，如果为数值，则返回该参数的字符串表示形式的长度，如果为NULL，则返回NULL。

LengthB
~~~~~~~~~~~~~~~~~~
函数体： **LengthB(string str)**

返回值：String

说明：返回文本的字节长度，中文为两个字节，字母为一个字节。

like
~~~~~~~~~~~~~~~~~~
操作符： **like**

返回值：Boolean

说明：相似模式匹配比较，不区分大小写。它左边包含被匹配的字符串，右边是一个匹配模式。在匹配模式中，%匹配字符串中任意0个或多个字符,_仅匹配一个任意的字符。

like escape
~~~~~~~~~~~~~~~~~~
操作符： **like escape**

返回值：String

说明：使用escape，定义转义字符，转义字符后面的%或_就不作为通配符了。例如：username like '%xiao\_%' escape '\'，字符\为转义字符。

Lower
~~~~~~~~~~~~~~~~~~
函数体： **Lower(STRING)**

返回值：String

说明：返回函数参数X的小写形式，缺省情况下，该函数只能应用于ASCII字符。

ltrim
~~~~~~~~~~~~~~~~~~
函数体： **ltrim(STRING)**

返回值：String

说明：删除STRING左边所有空格。

函数体： **ltrim(String,Chars)**

返回值：String

说明：删除String左边所有空格及Chars。

Match
~~~~~~~~~~~~~~~~~~
函数体： **Match(String,RegexString)**

返回值：String

说明：正则表达式匹配，返回第一个匹配结果。

函数体： **Match(String, RegexString, RegexOptions)**

返回值：Boolean

说明：正则表达式匹配，返回第一个匹配结果。RegexOptions用于设置正则表达式选项的枚举值。例如：Match("ASDV","[a-z]+","Compiled | IgnoreCase")选项值有：None,Compiled,CultureInvariant,ECMAScript,ExplicitCapture,IgnoreCase,IgnorePatternWhitespace,Multiline,RightToLeft,Singleline。

MatchDate
~~~~~~~~~~~~~~~~~~
函数体： **MatchDate(String)**

返回值：String

说明：通过正则表达式匹配从文本中抽取日期。支持格式：2000-1-1、2000年1月1日、2000/1/1

Matches
~~~~~~~~~~~~~~~~~~
函数体： **Matches(String,RegexString)**

返回值：List

说明：正则表达式匹配，返回字符串列表。

函数体： **Matches(String, RegexString, RegexOptions)**

返回值：List

说明：正则表达式匹配，返回字符串列表。RegexOptions用于设置正则表达式选项的枚举值。例如：Matches("$ASDV@ad","[a-z]+","Compiled | IgnoreCase")选项值有：None,Compiled,CultureInvariant,ECMAScript,ExplicitCapture,IgnoreCase,IgnorePatternWhitespace,Multiline,RightToLeft,Singleline。

MatchGroup
~~~~~~~~~~~~~~~~~~
函数体： **MatchGroup(String,RegexString,GroupName)**

返回值：String

说明：分组正则表达式匹配，返回第一个匹配结果。

函数体： **MatchGroup(String,RegexString,GroupName)**

返回值：List

说明：分组正则表达式匹配，返回字符串列表。

函数体： **MatchGroup(String, RegexString, GroupName, RegexOptions)**

返回值：String

说明：分组正则表达式匹配，返回第一个匹配结果。RegexOptions用于设置正则表达式选项的枚举值。例如：MatchGroup("关井油压5.7MPa,套压8.2MPa。", "油压(?<GN>[0-9]+(\.[0-9]+){0,1})" ,"GN","Compiled | IgnoreCase")选项值有：None,Compiled,CultureInvariant,ECMAScript,ExplicitCapture,IgnoreCase,IgnorePatternWhitespace,Multiline,RightToLeft,Singleline。

MatchGroups
~~~~~~~~~~~~~~~~~~
函数体： **MatchGroups(String, RegexString, GroupName, RegexOptions)**

返回值：List

说明：分组正则表达式匹配，返回字符串列表。RegexOptions用于设置正则表达式选项的枚举值。例如：MatchGroup("关井油压5.7MPa,套压8.2MPa。", "油压(?<GN>[0-9]+(\.[0-9]+){0,1})" ,"GN","Compiled | IgnoreCase")选项值有：None,Compiled,CultureInvariant,ECMAScript,ExplicitCapture,IgnoreCase,IgnorePatternWhitespace,Multiline,RightToLeft,Singleline。

MatchTime
~~~~~~~~~~~~~~~~~~
函数体： **MatchTime(String)**

返回值：String

说明：通过正则表达式匹配从文本中抽取时间。支持格式：20:30:30、20：30

NewLine
~~~~~~~~~~~~~~~~~~
函数体： **NewLine()**

返回值：String

说明：回车字符。

not like
~~~~~~~~~~~~~~~~~~
操作符： **not like**

返回值：Boolean

说明：不相似模式匹配比较，不区分大小写。它左边包含被匹配的字符串，右边是一个匹配模式。在匹配模式中，%匹配字符串中任意0个或多个字符,_仅匹配一个任意的字符。

Padc
~~~~~~~~~~~~~~~~~~
函数体： **Padc(STRING,LEN)**

返回值：String

说明：字符串两端补全，返回一个长度为LEN的字符串，在STRING两端增加多个空格，使其长度为LEN。当原有字符串的长度大于LEN时，返回原有STRING。

Padl
~~~~~~~~~~~~~~~~~~
函数体： **Padl(STRING,LEN)**

返回值：String

说明：左边字符串补全，返回一个长度为LEN的字符串，在STRING左边增加多个空格，使其长度为LEN。当原有字符串的长度大于LEN时，返回原有STRING。

函数体： **Padl(STRING,LEN,Char)**

返回值：String

说明：左边字符串补全，返回一个长度为LEN的字符串，在STRING左边增加多个Char，使其长度为LEN。当原有字符串的长度大于LEN时，返回原有STRING。

Padr
~~~~~~~~~~~~~~~~~~
函数体： **Padr(STRING,LEN)**

返回值：String

说明：右边字符串补全，返回一个长度为LEN的字符串，在STRING右边增加多个空格，使其长度为LEN。当原有字符串的长度大于LEN时，返回原有STRING。

函数体： **Padr(STRING,LEN,Char)**

返回值：String

说明：右边字符串补全，返回一个长度为LEN的字符串，在STRING右边增加多个Char，使其长度为LEN。当原有字符串的长度大于LEN时，返回原有STRING。

Proper
~~~~~~~~~~~~~~~~~~
函数体： **Proper(STRING)**

返回值：String

说明：首字母大写，将文本字符串STRING的首字母转换成大写，将其余的字母转换成小写。

RemoveBetweenS
~~~~~~~~~~~~~~~~~~
函数体： **RemoveBetweenS(STRING,StartSubString,EndSubString)**

返回值：String

说明：删除STRING中StartSubString-EndSubString之间的字符。

RemoveBreakAndSpace
~~~~~~~~~~~~~~~~~~
函数体： **RemoveBreakAndSpace(STRING)**

返回值：String

说明：删除字符串中的回车、中英文空格、制表符。

RemoveChars
~~~~~~~~~~~~~~~~~~
函数体： **RemoveChars(STRING,Chars)**

返回值：String

说明：从字符串STRING中，删除所有Chars字符。

RemoveHiddenCharacters
~~~~~~~~~~~~~~~~~~
函数体： **RemoveHiddenCharacters(STRING)**

返回值：String

说明：删除文本中所有不可见字符。

RemoveLineBreak
~~~~~~~~~~~~~~~~~~
函数体： **RemoveLineBreak(STRING)**

返回值：String

说明：删除文本中所有的换行符。

RemoveMinLine
~~~~~~~~~~~~~~~~~~
函数体： **RemoveMinLine(String,Length)**

返回值：String

说明：删除文本中的长度小于Length的行。

RemoveRedundantSpace
~~~~~~~~~~~~~~~~~~
函数体： **RemoveRedundantSpace(STRING)**

返回值：String

说明：将字符串中的多个空格替换成一个空格。

RemoveRept
~~~~~~~~~~~~~~~~~~
函数体： **RemoveRept(STRING,CHAR)**

返回值：String

说明：删除重复字符。

RemoveStrings
~~~~~~~~~~~~~~~~~~
函数体： **RemoveStrings(STRING,STRING1,STRING2,…)**

返回值：String

说明：从字符串STRING中，删除字符串STRING1,STRING2,…。

Replace
~~~~~~~~~~~~~~~~~~
函数体： **Replace(String, OLD_STRING1, NEW_STRING1, OLD_STRING2, NEW_STRING2...)**

返回值：String

说明：字符串替换，用NEW_STRING1替换OLD_STRING1,用NEW_STRING2替换OLD_STRING2...

ReplaceBetweenS
~~~~~~~~~~~~~~~~~~
函数体： **ReplaceBetweenS(STRING,StartSubString,EndSubString,ReplaceString)**

返回值：String

说明：用ReplaceString替换STRING中StartSubString-EndSubString之间的字符。

ReplaceLineBreak
~~~~~~~~~~~~~~~~~~
函数体： **ReplaceLineBreak(STRING,RepString)**

返回值：String

说明：用RepString替换文本中所有的换行符。

ReplaceReg
~~~~~~~~~~~~~~~~~~
函数体： **ReplaceReg(String, RegexString, RepString)**

返回值：String

说明：根据正则表达式，替换指定的匹配内容。

函数体： **ReplaceReg(String, RegexString, RepString, RegexOptions)**

返回值：String

说明：根据正则表达式，替换指定的匹配内容。RegexOptions用于设置正则表达式选项的枚举值。例如：ReplaceReg("$ASDV@","[a-z]+","dsdfs","Compiled | IgnoreCase")选项值有：None,Compiled,CultureInvariant,ECMAScript,ExplicitCapture,IgnoreCase,IgnorePatternWhitespace,Multiline,RightToLeft,Singleline。

Rept
~~~~~~~~~~~~~~~~~~
函数体： **Rept(STRING,N)**

返回值：String

说明：复制字符串，返回一个包括N个STRING的字符串。

Reverse
~~~~~~~~~~~~~~~~~~
函数体： **Reverse(STRING)**

返回值：String

说明：字符串反序，返回与STRING字符顺序相反的字符串。

RightStr
~~~~~~~~~~~~~~~~~~
函数体： **RightStr(STRING,LEN)**

返回值：String

说明：返回STRING的右边N个字符串。

rtrim
~~~~~~~~~~~~~~~~~~
函数体： **rtrim(STRING)**

返回值：String

说明：删除STRING右边所有空格。

函数体： **rtrim(String,Chars)**

返回值：String

说明：删除String右边所有空格及Chars。

SimpleString
~~~~~~~~~~~~~~~~~~
函数体： **SimpleString(STRING,LEN)**

返回值：String

说明：返回STRING的子字符串，包括字符串STRING开始的LEN个字符，与StartString相似，未端有...标记。

SpaceNormal
~~~~~~~~~~~~~~~~~~
函数体： **SpaceNormal(String Text)**

返回值：String

说明：将任何空白字符转换为空格，例如空格符、制表符和进纸符等。注：效率较慢。

SplitString
~~~~~~~~~~~~~~~~~~
函数体： **SplitString(String,SplitChars)**

返回值：String

说明：用SplitChars分隔String中的每个字符。

SplitText
~~~~~~~~~~~~~~~~~~
函数体： **SplitText(String)**

返回值：String

说明：对文本进行中文划词,采用双向最大匹配法。

函数体： **SplitText(String,DictID)**

返回值：String

说明：对文本进行中文划词,采用双向最大匹配法,DictID为字典的ID。

函数体： **SplitText(String,DictID,OnlyInDict)**

返回值：String

说明：对文本进行中文划词,采用双向最大匹配法,DictID为字典的ID,OnlyInDict布尔型，为真输出字典中的值。

函数体： **SplitText(String,DictID,OnlyInDict,LengthAsc)**

返回值：String

说明：对文本进行中文划词,采用双向最大匹配法,DictID为字典的ID,OnlyInDict布尔型，为真输出字典中的值；LengthDsc输出结果按长度排序，True为正序，False为倒序。

sscanf
~~~~~~~~~~~~~~~~~~
函数体： **sscanf(String,Format)**

返回值：String

说明：读取指定格式的数据。其中Format可以是%[*][width]type，加*表示跳过此数据不读；width表示读取宽度；type表示类型c为一个字符，d为整数，f为实数,s为多个任意字符；例如%s,%*3s等。

函数体： **sscanf(String,Format,SplitChar)**

返回值：String

说明：读取指定格式的数据。其中Format可以是%[*][width]type，加*表示跳过此数据不读；width表示读取宽度；type表示类型c为一个字符，d为整数，f为实数,s为多个任意字符。SplitChar为输出联接字符。

StartString
~~~~~~~~~~~~~~~~~~
函数体： **StartString(STRING,LEN)**

返回值：String

说明：返回STRING的子字符串，包括字符串STRING开始的LEN个字符。与LeftStr(STRING,LEN)相同。

StartsWith
~~~~~~~~~~~~~~~~~~
函数体： **StartsWith(STRING,SUBSTRING)**

返回值：Boolean

说明：如果STRING以SUBSTRING开始，返回真(1)，否则返回假(0)。

StartsWithOR
~~~~~~~~~~~~~~~~~~
函数体： **StartsWithOR(STRING,SUBSTRING1,SUBSTRING2,…)**

返回值：Boolean

说明：如果STRING以SUBSTRING1或者SUBSTRING2或者…开始，返回真(1)，否则返回假(0)。

StrFilter
~~~~~~~~~~~~~~~~~~
函数体： **StrFilter(String,SubString)**

返回值：String

说明：字符串过滤，在String中过滤出所有SubString，删除String中所有不等于SubString的字符串。

StringCompare
~~~~~~~~~~~~~~~~~~
函数体： **StringCompare(STRING,STRING)**

返回值：Integer

说明：两个字符串比较。

SubStr
~~~~~~~~~~~~~~~~~~
函数体： **SubStr(STRING,N)**

返回值：String

说明：返回函数参数STRING的子字符串，从第N位开始(STRING中的第一个字符位置为1)后面的所有字符。如果N值为负数，则从STRING字符串的尾部开始计数到第abs(N)的位置开始，后面的所有字符。

函数体： **SubStr(STRING,N,LEN)**

返回值：String

说明：返回函数参数STRING的子字符串，从第N位开始(第一个字符位置为1)截取LEN长度的字符。如果LEN的值为负数，则从第N位开始，向左截取abs(LEN)个字符。如果N值为负数，则从STRING字符串的尾部开始计数到第abs(N)的位置开始。

SubStrB
~~~~~~~~~~~~~~~~~~
函数体： **SubStrB(STRING,N)**

返回值：String

说明：与SubStr类似，该函数以字节数字计算字符长度，中文长度为2，字母长度为1；返回函数参数STRING的子字符串，从第N位开始后面的所有字符。如果N值为负数，则从STRING字符串的尾部开始计数到第abs(N)的位置开始，后面的所有字符。

函数体： **SubStrB(STRING,N,LEN)**

返回值：String

说明：与SubStr类似，该函数以字节数字计算字符长度，中文长度为2，字母长度为1；返回函数参数STRING的子字符串，从第N位开始截取LEN长度的字符。如果LEN的值为负数，则从第N位开始，向左截取abs(LEN)个字符。如果N值为负数，则从STRING字符串的尾部开始计数到第abs(N)的位置开始。

SubStrBetween
~~~~~~~~~~~~~~~~~~
函数体： **SubStrBetween(STRING,N,M)**

返回值：String

说明：返回STRING中N-M之间的子字符串。

SubStrBetweenL
~~~~~~~~~~~~~~~~~~
函数体： **SubStrBetweenL(STRING,List1,List2,ID,Char)**

返回值：String

说明：返回STRING中List1-List2之间的子字符串,ID可选，第N个匹配项，0为所有（默认），1第1个，2第二个...;Char可选，输出连接间隔符。如：SubStrBetweenL( 内容 , ['供稿:'] , ['审稿','审核','编审', '
' ])

SubStrBetweenS
~~~~~~~~~~~~~~~~~~
函数体： **SubStrBetweenS(STRING,StartSubString,EndSubString)**

返回值：String

说明：返回STRING中StartSubString-EndSubString之间的子字符串；若StartSubString为空，取EndSubString之前的所有字符串；若EndSubString为空，取StartSubString之后的所有字符串。

函数体： **SubStrBetweenS(STRING,StartSubString,EndSubString,ID [,Char])**

返回值：String

说明：返回STRING中StartSubString-EndSubString之间的子字符串;ID可选，第N个匹配项, 0为所有（默认），1第1个，2第二个...，负数从后向前-1为最后一个，-2倒数第二个;Char可选，输出连接间隔符。

ToChineseMoney
~~~~~~~~~~~~~~~~~~
函数体： **ToChineseMoney(Real)**

返回值：String

说明：将数字转为人民币汉字大写表示。

ToDBC
~~~~~~~~~~~~~~~~~~
函数体： **ToDBC(STRING)**

返回值：String

说明：将字符串STRING转化全角字符串。(Double Byte Characters，简称DBC)

ToPinyin
~~~~~~~~~~~~~~~~~~
函数体： **ToPinyin(String)**

返回值：String

说明：将汉字转化为拼音。

ToPinyinFirstLetter
~~~~~~~~~~~~~~~~~~
函数体： **ToPinyinFirstLetter(String)**

返回值：String

说明：将汉字转换为拼音首字母。

ToSBC
~~~~~~~~~~~~~~~~~~
函数体： **ToSBC(STRING)**

返回值：String

说明：将字符串STRING转化半角字符串。(Single Byte Characters，简称SBC)

trim
~~~~~~~~~~~~~~~~~~
函数体： **trim(STRING)**

返回值：String

说明：删除字符串两端的空格。

函数体： **trim(String,Chars)**

返回值：String

说明：删除String两端所有空格及Chars。

Upper
~~~~~~~~~~~~~~~~~~
函数体： **Upper(STRING)**

返回值：String

说明：返回函数参数X的大写形式，缺省情况下，该函数只能应用于ASCII字符。

UrlDecode
~~~~~~~~~~~~~~~~~~
函数体： **UrlDecode(STRING)**

返回值：String

说明：URL解码,如“%e7%a7%91%e6%8a%80%e5%88%9b%e6%96%b0”转化为“科技创新”

UrlEncode
~~~~~~~~~~~~~~~~~~
函数体： **UrlEncode(STRING)**

返回值：String

说明：URL编码,如“科技创新”转化为“%e7%a7%91%e6%8a%80%e5%88%9b%e6%96%b0”

WordDF
~~~~~~~~~~~~~~~~~~
函数体： **WordDF(String)**

返回值：String

说明：返回文本中出现频率最高的前10个词组,采用双向最大匹配法。

函数体： **WordDF(String,DictID)**

返回值：String

说明：返回文本中出现频率最高的前10个词组,采用双向最大匹配法,DictID为字典的ID。

函数体： **WordDF(String,DictID,OnlyInDict)**

返回值：String

说明：返回文本中出现频率最高的前10个词组,采用双向最大匹配法,DictID为字典的ID,OnlyInDict布尔型,为真输出字典中的值。

函数体： **WordDF(String,DictID,OnlyInDict,SplitChar)**

返回值：String

说明：返回文本中出现频率最高的前10个词组,采用双向最大匹配法,DictID为字典的ID,OnlyInDict布尔型,为真输出字典中的值,输出结果以SplitChar指定的字符分隔。

函数体： **WordDF(String,DictID,OnlyInDict,SplitChar,MaxCount)**

返回值：String

说明：返回文本中出现频率最高的前MaxCount个词组,采用双向最大匹配法,DictID为字典的ID,OnlyInDict布尔型,为真输出字典中的值,输出结果以SplitChar指定的字符分隔。

||
~~~~~~~~~~~~~~~~~~
操作符： **Item1 || Item2**

返回值：String

说明：连接符，双目运算符，连接两个字段的值，并返回结果字符串Item1Item2。

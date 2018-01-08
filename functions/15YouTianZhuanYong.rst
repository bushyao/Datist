.. _YouTianZhuanYong:
油田专用
======================

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

.. _HTMLHanShu:
HTML函数
======================

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

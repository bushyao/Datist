.. _LieBiaoHanShu:
列表函数
======================

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

CreateSequence(StartId,EndId)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：根据指定的定义起止序号，构造一个整数序列字符串（包括起止序号），其中StartId、EndId为整数；当 StartId 小于 EndId 输出递增序列，StartId 大于 EndId 输出递减序列。

CreateSequence(StartId,EndId,Step)
~~~~~~~~~~~~~~~~~~
返回值：String

说明：根据指定的定义起止序号，构造一个整数序列字符串（包括起止序号），其中StartId、EndId、Step为整数，Step定义增量步长；当 StartId 小于 EndId 输出递增序列，StartId 大于 EndId 输出递减序列。

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

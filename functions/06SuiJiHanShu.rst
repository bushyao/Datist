.. _SuiJiHanShu:
随机函数
======================

oneof
~~~~~~~~~~~~~~~~~~
函数体：oneof(List)

返回值：Any

说明：返回一个从LIST 中随机选取的元素。应以[ITEM1,ITEM2,...,ITEM_N] 的形式输入列表项。注意，还可以指定字段名称列表。

Random
~~~~~~~~~~~~~~~~~~
函数体：Random()

返回值：Integer

说明：返回整型的伪随机数,随机数介于-9223372036854775808和+9223372036854775807之间。

random
~~~~~~~~~~~~~~~~~~
函数体：random(maxInteger)

返回值：Integer

说明：返回一个小于maxInteger的非负随机数。maxInteger必须大于或等于零。返回值的范围通常包括零但不包括 maxInteger。不过，如果 maxInteger 等于零，则返回 maxInteger。

函数体：random(minInteger,maxInteger)

返回值：Integer

说明：返回一个指定范围内的随机数。maxInteger 必须大于或等于 minInteger。返回值的范围包括 minInteger 但不包括 maxInteger。如果minInteger 等于 maxInteger，则返回 minInteger。

random_double
~~~~~~~~~~~~~~~~~~
函数体：random_double()

返回值：Double

说明：返回一个介于 0.0 和 1.0 之间的随机数。返回值大于等于 0.0 并且小于 1.0 的双精度浮点数。

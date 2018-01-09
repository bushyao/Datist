.. _TongJi:
统计
======================

@AutoCorrelation
~~~~~~~~~~~~~~~~~~
函数体：@AutoCorrelation( FieldA , FieldB )

返回值：Double

说明：自相关系数。可用于判断两道曲线的相似程度。如果用方差 σ2 进行归一化处理，那么自协方差就变成了自相关系数 R(k)。在信息分析中，通常将自相关函数称之为自协方差方程。 用来描述信息在不同时间τ的，信息函数值的相关性。

@avg
~~~~~~~~~~~~~~~~~~
函数体：@avg(FIELD)

返回值：Double

说明：平均值，与@mean函数相同，返回字段的平均值，忽略空值记录。如果字段中没有非空数值，返回NULL。

@count
~~~~~~~~~~~~~~~~~~
函数体：@count(FIELD)

返回值：Integer

说明：计数，返回字段的记录数，忽略空值记录。

@CountIF
~~~~~~~~~~~~~~~~~~
函数体：@CountIF( Expression )

返回值：Integer

说明：统计符合指定条件的值个数。

@CovarianceP
~~~~~~~~~~~~~~~~~~
函数体：@CovarianceP( FieldA , FieldB )

返回值：Double

说明：返回总体协方差，即两个数据集中每对数据点的偏差乘积的平均数。

@CovarianceS
~~~~~~~~~~~~~~~~~~
函数体：@CovarianceS( FieldA , FieldB )

返回值：Double

说明：返回样本协方差，即两个数据集中每对数据点的偏差乘积的平均值。

@First
~~~~~~~~~~~~~~~~~~
函数体：@First( Field )

返回值：Any

说明：返回第一个数据值

@group_concat
~~~~~~~~~~~~~~~~~~
函数体：@group_concat(FIELD)

返回值：String

说明：连接字符串，用字符“,”连接字段中所有数据项，忽略空值记录。

函数体：@group_concat(FIELD,STRING)

返回值：String

说明：连接字符串，用字符“STRING”连接字段中所有数据项，忽略空值记录。

@InformationEntropy
~~~~~~~~~~~~~~~~~~
函数体：@InformationEntropy( Field )

返回值：Double

说明：求一组数据的信息熵。

@Kurtosis
~~~~~~~~~~~~~~~~~~
函数体：@Kurtosis( Field )

返回值：Double

说明：峰度系数，峰度是用来反映频数分布曲线顶端尖峭或扁平程度的指标

@Last
~~~~~~~~~~~~~~~~~~
函数体：@Last( Field )

返回值：Any

说明：返回最后一个数据值

@ListAgg
~~~~~~~~~~~~~~~~~~
函数体：@ListAgg( Field , Char )

返回值：String

说明：将字段内容连接成一个字符串

@lower_quartile
~~~~~~~~~~~~~~~~~~
函数体：@lower_quartile(FIELD)

返回值：Double

说明：第一个四分位数（第 25 个百分点值）。统计学中，把从小到大排列好的数值看作四等分时的三个分割点称为四分位数。

@max
~~~~~~~~~~~~~~~~~~
函数体：@max(FIELD)

返回值：Any

说明：最大值，返回字段中最大数值，忽略空值记录。如果字段中没有非空数值，返回NULL。

@MaxIF
~~~~~~~~~~~~~~~~~~
函数体：@MaxIF( Field , Expression )

返回值：Any

说明：对字段中符合指定条件的最大值。

@MaxIFByNumber
~~~~~~~~~~~~~~~~~~
函数体：@MaxIFByNumber( Field , Expression )

返回值：Any

说明：对字段中符合指定条件的最大值。

@mean
~~~~~~~~~~~~~~~~~~
函数体：@mean(FIELD)

返回值：Double

说明：平均值，与@avg函数相同，返回字段的平均值，忽略空值记录。如果字段中没有非空数值，返回NULL。

@median
~~~~~~~~~~~~~~~~~~
函数体：@median(FIELD)

返回值：Double

说明：中位数，返回在字段中居于中间的数值；在字段中，一半数字的值大于中位数,一半数字的值小于中位数。

@min
~~~~~~~~~~~~~~~~~~
函数体：@min(FIELD)

返回值：Any

说明：最小值，返回字段中最小数值，忽略空值记录。如果字段中没有非空数值，返回NULL。

@MinIF
~~~~~~~~~~~~~~~~~~
函数体：@MinIF( Field , Expression )

返回值：Any

说明：对字段中符合指定条件的最小值。

@MinIFByNumber
~~~~~~~~~~~~~~~~~~
函数体：@MinIFByNumber( Field , Expression )

返回值：Any

说明：对字段中符合指定条件的最小值。

@mode
~~~~~~~~~~~~~~~~~~
函数体：@mode(FIELD)

返回值：Double

说明：众数，返回字段中出现频率最多的数值。

@Quartile
~~~~~~~~~~~~~~~~~~
函数体：@Quartile( Field , Percent )

返回值：Double

说明：第Percent百分位数，将Field的数据从小到大排序，处于Percent位置的值，0<=Percent<=100。

@Skew
~~~~~~~~~~~~~~~~~~
函数体：@Skew( Field )

返回值：Double

说明：Skew

@SkewP
~~~~~~~~~~~~~~~~~~
函数体：@SkewP( Field )

返回值：Double

说明：SkewPop

@StdDevP
~~~~~~~~~~~~~~~~~~
函数体：@StdDevP( Field )

返回值：Double

说明：StdDevPop

@StdDevS
~~~~~~~~~~~~~~~~~~
函数体：@StdDevS( Field )

返回值：Double

说明：StdDevSamp

@stdev
~~~~~~~~~~~~~~~~~~
函数体：@stdev(FIELD)

返回值：Double

说明：标准偏差，又称均方差，一般用σ表示。反映数值相对于平均值(mean) 的离散程度。标准偏差越小，这些值偏离平均值就越少，反之亦然。

@sum
~~~~~~~~~~~~~~~~~~
函数体：@sum(FIELD)

返回值：Double

说明：求和，返回字段中非空数值和。如果字段中没有非空数值，返回NULL。

@SumIF
~~~~~~~~~~~~~~~~~~
函数体：@SumIF( Field , Expression )

返回值：Double

说明：对字段中符合指定条件的值求和。

@total
~~~~~~~~~~~~~~~~~~
函数体：@total(FIELD)

返回值：Double

说明：求和，返回字段中非空数值和，始终返回浮点数。如果字段中没有非空数值，返回0.0

@upper_quartile
~~~~~~~~~~~~~~~~~~
函数体：@upper_quartile(FIELD)

返回值：Double

说明：第三个四分位数（第 75 个百分点值）。统计学中，把从小到大排列好的数值看作四等分时的三个分割点称为四分位数。

@variance
~~~~~~~~~~~~~~~~~~
函数体：@variance(FIELD)

返回值：Double

说明：方差，返回各个数值与其算术平均数的离差平方和的平均数，通常以σ2表示。

@VarP
~~~~~~~~~~~~~~~~~~
函数体：@VarP( Field )

返回值：Double

说明：VariancePop

@VarS
~~~~~~~~~~~~~~~~~~
函数体：@VarS( Field )

返回值：Double

说明：VarianceSamp

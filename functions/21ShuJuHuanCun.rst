.. _ShuJuHuanCun:
数据缓存
======================

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

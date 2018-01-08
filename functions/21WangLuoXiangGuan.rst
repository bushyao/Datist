.. _WangLuoXiangGuan:
网络相关
======================

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

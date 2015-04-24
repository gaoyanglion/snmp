# snmpwalk
>获取v1、v2版本数据

snmpwalk -v 版本 -c 团体名 设备ip

例如：

snmpwalk -v 1 -c public 192.168.1.8

snmpwalk -v 2c -c public 192.168.1.8

>获取v3版本数据

 1. 不认证不加密

snmpwalk –v 3  –u 用户名 –l  安全级别 设备ip

例如：

snmpwalk -v 3 -u admin -l noAuthNoPriv 192.168.1.8

2. 






# snmpbulkwalk

# snmpwalk
>获取v1、v2版本数据

snmpwalk -v 版本 -c 团体名 设备ip

例如：

snmpwalk -v 1 -c public 192.168.1.8

snmpwalk -v 2c -c public 192.168.1.8

>获取v3版本数据

* 不认证不加密

snmpwalk –v 3  –u 用户名 –l  安全级别 设备ip

例如：

snmpwalk -v 3 -u admin -l noAuthNoPriv 192.168.1.8

* 只认证不加密

snmpwalk –v 3  –u 用户名 –l  安全级别 –a 认证协议 –A 认证密码 设备ip

例如：

snmpwalk -v 3 -u admin -l authNoPriv -a MD5 -A 123@abc 192.168.1.8

* 既认证又加密

snmpwalk –v 3  –u 用户名 –l  安全级别 –a 认证协议 –A 认证密码 –x 加密协议 –X 加密密码 设备ip 

例如：

snmpwalk -v 3 -u admin -l authNoPriv -a MD5 -A 123@abc -x DES -X 123@abc 192.168.1.8








# snmpbulkwalk

使用SNMP GETBULK来获取数据，比snmpwalk效率高，不过，v1下无法使用

语法同snmpwalk

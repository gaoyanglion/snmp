# common

1.3.6.1.2.1.1.2 sysObjectID 设备的systemoid，标识型号.

1.3.6.1.2.1.1.3 sysUpTime 设备运行时间

1.3.6.1.2.1.1.4 sysContact 设备联系方式

1.3.6.1.2.1.1.5 sysName 设备名称

1.3.6.1.2.1.1.6 sysLocation 设备位置

1.3.6.1.2.1.1.7 sysServices 设备服务

1.3.6.1.2.1.2.2.1.10 ifInOctets 接口接收字节数

1.3.6.1.2.1.2.2.1.16 ifOutOctets 接口发送字节数

1.3.6.1.2.1.2.2.1.1 ifindex 接口索引

1.3.6.1.2.1.2.2.1.5 ifspeed 接口带宽（32位计数器）

1.3.6.1.2.1.31.1.1.1.15 ifspeed 接口带宽（64位计数器）

1.3.6.1.2.1.2.2.1.2 ifname 接口名称

1.3.6.1.2.1.4.20.1.1 设备ip地址

1.3.6.1.2.1.2.2.1.7 ifadminstatus 接口管理状态

1.3.6.1.2.1.2.2.1.8 ifopeartestatus 接口操作状态

1.3.6.1.2.1.2.2.1.13 ifInDiscards 接口接收丢包数

1.3.6.1.2.1.2.2.1.19 ifOutDiscards 接口发送丢包数

1.3.6.1.2.1.31.1.1.1.18 ifdescription(ifAlias) 接口描述

1.3.6.1.2.1.31.1.1.1.6 ifHCInOctets 接口接收字节数（64位计数器 单位：octets）

1.3.6.1.2.1.31.1.1.1.10 ifHCOutOctets 接口发送字节数（64位计数器 单位：octets）

1.3.6.1.2.1.31.1.1.1.7 ifHCInUcastPkts 接口接收单播包数

1.3.6.1.2.1.31.1.1.1.11 ifHCOutUcastPkts 接口发送单播包数

1.3.6.1.2.1.31.1.1.1.8 ifHCInMulticastPkts 接口接收组播包数

1.3.6.1.2.1.31.1.1.1.12 ifHCOutMulticastPkts 接口发送组播包数

1.3.6.1.2.1.31.1.1.1.9 ifHCInBroadcastPkts 接口接收广播包数

1.3.6.1.2.1.31.1.1.1.13 ifHCOutBroadcastPkts 接口发送广播包数

1.3.6.1.2.1.31.1.1 ifXTable 接口表

1.3.6.1.2.1.2.2 ifTable 接口表

1.3.6.1.2.1.2.2.1.20 ifOutErrors 接口发送错包数

1.3.6.1.2.1.2.2.1.14 ifInErrors 接口接收错包数

1.3.6.1.2.1.2.2.1.13 ifInDiscards 接口接收丢包数

1.3.6.1.2.1.2.2.1.19 ifOutDiscards 接口发送丢包数

1.3.6.1.2.1.6.9 tcpCurrEstab TCP端口连接数

1.3.6.1.2.1.2.2.1.11 ifInUcastPkts 接口接收单播包数

1.3.6.1.2.1.2.2.1.17 ifOutUcastPkts 接口发送单播包数

1.3.6.1.2.1.31.1.1.1.3 ifInBroadcastPkts 接口接收广播包数

1.3.6.1.2.1.31.1.1.1.5 ifOutBroadcastPkts 接口发送广播包数

# host

1.3.6.1.2.1.25.3.3.1.2 cpu利用率

# FDB

1.3.6.1.2.1.17.4.3.1.1  FdbAddress

1.3.6.1.2.1.17.4.3.1.2 FdbPort

1.3.6.1.2.1.17.4.3.1.3 FdbStatus

# ARP

1.3.6.1.2.1.4.22.1   

# tcpConnTable（可得到类似“netstat -an -p tcp”命令结果）

1.3.6.1.2.1.6.13.1.1 连接状态（侦听，关闭等）

1.3.6.1.2.1.6.13.1.1 本地地址

1.3.6.1.2.1.6.13.1.3 本地端口

1.3.6.1.2.1.6.13.1.4 远程地址

1.3.6.1.2.1.6.13.1.5 远程端口

# udpEntry（可得到类似“netstat -an -p udp”命令结果）

1.3.6.1.2.1.7.5.1.1 本地地址

1.3.6.1.2.1.7.5.1.2 本地端口

# vlan（待验证）

1.3.6.1.2.1.17.7.1.4.2.1.6 vlan状态

1.3.6.1.2.1.17.7.1.4.3.1.1 vlan名称

http://www.oidview.com/mibs/0/Q-BRIDGE-MIB.html

https://support.huawei.com/enterprise/zh/doc/DOC1000027337?section=j00y

# OSPF邻居表

1.3.6.1.2.1.14.10.1.1 邻居的IP地址

1.3.6.1.2.1.14.10.1.3 ospfNbrRtrId,uniquely identifying the neighboring router in the autonomous system

1.3.6.1.2.1.14.10.1.6  	The state of the relationship with the neighbor. The states are: down (1) attempt (2) init (3)      twoWay(4)  exchangeStart (5)   exchange (6)  loading (7)  full (8)

# fdb相关

dbridge:1.3.6.1.2.1.17.4.3.1
qbridge:1.3.6.1.2.1.17.7.1.2.2.1

# 路由表

1.3.6.1.2.1.4.21




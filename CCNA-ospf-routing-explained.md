# CCNA-ospf-routing-explained
R0>en
R0#conf t
R0 fig#route ospf 1
R0 ter#network 125.0.0.0 0.0.0.3 area 0
R0 ter#network 192.168.0.0 0.0.0.255 area 1
R0 ter#network 10.0.0.0 0.255.255.255 area 2
ter#do copy run star
-------
R1>en
R1#conf t
R1 fig#route ospf 1
R1 ter#network 172.16.0.0 0.0.255.255
ter#do copy run star

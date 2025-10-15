# CCNA-OSPF-Routing-Explained

## Router R0 Configuration

```text
>en
#conf t
fig#router ospf 1
fig#network 125.0.0.0 0.0.0.3 area 0
fig#network 192.168.0.0 0.0.0.255 area 1
fig#network 10.0.0.0 0.255.255.255 area 2
ter#do copy run star
![OSPF Routing Explained](https://github.com/issawiold/CCNA-ospf-routing-explained/blob/main/Screenshot_20251015-134645_Firefox.png?raw=true)

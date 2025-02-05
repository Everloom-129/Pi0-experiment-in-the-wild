base) franka@franka-Alienware-x17-R2:~$ ip addr show
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host 
       valid_lft forever preferred_lft forever
2: enp44s0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether ac:91:a1:06:3a:25 brd ff:ff:ff:ff:ff:ff
    inet 172.16.0.1/24 brd 172.16.0.255 scope global noprefixroute enp44s0
       valid_lft forever preferred_lft forever
    inet6 fe80::3bf1:8fd8:2696:19d1/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
3: wlo1: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc noqueue state UP group default qlen 1000
    link/ether 74:04:f1:fb:4a:5a brd ff:ff:ff:ff:ff:ff
    altname wlp0s20f3
    inet 10.102.220.200/18 brd 10.102.255.255 scope global dynamic noprefixroute wlo1
       valid_lft 1585sec preferred_lft 1585sec
    inet6 2607:f470:6:1001:c40c:c517:eb36:580a/64 scope global temporary dynamic 
       valid_lft 593331sec preferred_lft 74862sec
    inet6 2607:f470:6:1001:4bf7:1b68:f266:ae12/64 scope global dynamic mngtmpaddr noprefixroute 
       valid_lft 2592000sec preferred_lft 604800sec
    inet6 fe80::9373:431c:457:52fc/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
5: docker0: <NO-CARRIER,BROADCAST,MULTICAST,UP> mtu 1500 qdisc noqueue state DOWN group default 
    link/ether 02:42:a9:91:f1:d0 brd ff:ff:ff:ff:ff:ff
    inet 172.17.0.1/16 brd 172.17.255.255 scope global docker0
       valid_lft forever preferred_lft forever
(base) franka@franka-Alienware-x17-R2:~$ 
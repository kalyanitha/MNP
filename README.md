Router R1
interface Loopback 0
ip address 192.168.1.1 255.255.255.0

interface Serial0/0/0
description R1 -->; ISP1
ip address 209.165.201.2 255.255.255.252
clock rate 128000
bandwidth 128
no shutdown

interface Serial0/0/1
description R1 -->; ISP2
ip address 209.165.202.130 255.255.255.252
bandwidth 128
no shutdown


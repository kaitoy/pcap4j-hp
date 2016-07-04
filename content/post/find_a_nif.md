+++
title = "Find Network Interface"
type = "post"
weight = 3
+++

It's time to write your awesome application.
Firstly, you probably want to find a network interface on which you want to capture packets.

```java
InetAddress addr = InetAddress.getByName("192.168.10.100");
PcapNetworkInterface nif = Pcaps.getDevByAddress(addr);
```

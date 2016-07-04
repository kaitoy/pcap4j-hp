+++
title = "Open Pcap Handle"
type = "post"
weight = 4
+++

Then, you can open a pcap handle from the network interface.
A pcap handle provides you APIs to capture packets, send packets, and so on.

```java
int snapLen = 65536;
PromiscuousMode mode = PromiscuousMode.PROMISCUOUS;
int timeout = 10
PcapHandle handle = nif.openLive(snapLen, mode, timeout);
```

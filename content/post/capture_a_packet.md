+++
title = "Capture Packet"
type = "post"
weight = 5
+++

Now you've got an ability to capture packets.
Let's get a packet using the pcap handle.

```java
Packet packet = handle.getNextPacketEx();
handle.close();
```

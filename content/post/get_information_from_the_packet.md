+++
title = "Get Packet Information"
type = "post"
weight = 6
+++

The packet you captured consists of headers and payloads of some protocols such as Ethernet, IPv4, and TCP.
The Packet API of Pcap4J enables you to get information from the protocol headers.

```java
IpV4Packet ipV4Packet = packet.get(IpV4Packet.class);
Inet4Address srcAddr = ipV4Packet.getHeader().getSrcAddr();
System.out.println(srcAddr);
```

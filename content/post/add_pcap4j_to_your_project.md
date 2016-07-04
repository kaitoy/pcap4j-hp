+++
title = "Add Dependencies"
type = "post"
weight = 2
+++

Before starting to write your code, you need to add Pcap4J and its dependencies to your classpath.
The easiest way to do that is to use a build tool such as [Gradle](http://gradle.org/) and [Maven](https://maven.apache.org/).

* Gradle

    ```groovy
    compile 'org.pcap4j:pcap4j-core:1.+'
    compile 'org.pcap4j:pcap4j-packetfactory-static:1.+'
    ```

* Maven

    ```xml
    <dependency>
      <groupId>org.pcap4j</groupId>
      <artifactId>pcap4j-core</artifactId>
      <version>[1.0, 2.0)</version>
    </dependency>
    <dependency>
      <groupId>org.pcap4j</groupId>
      <artifactId>pcap4j-packetfactory-static</artifactId>
      <version>[1.0, 2.0)</version>
    </dependency>
    ```

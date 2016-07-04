+++
class = "post first"
title = "Install Native Library"
type = "post"
weight = 1
+++

Let's start with installing [libpcap](http://www.tcpdump.org/) (for Mac/Linux/UNIX) or [WinPcap](https://www.winpcap.org/) (for Windows) on your computer.
They are native libraries that powers the core functionalities of Pcap4J.

* Ubuntu

    ```sh
    apt-get install libpcap-dev
    ```

* CentOs

    ```sh
    yum install libpcap-devel
    ```

* Mac

    ```sh
    brew install libpcap
    ```

* Windows

    ```sh
    choco install winpcap
    ```

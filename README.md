# [W6100](https://github.com/SoCXin/W6100)

[![sites](http://182.61.61.133/link/resources/SoC.png)](http://www.SoC.Xin)

#### [Vendor](https://github.com/SoCXin/Vendor)：[WCH](http://www.wch.cn/)
#### [Core](https://github.com/SoCXin/Cortex)：[Cortex M3](https://github.com/SoCXin/CM3)
#### [Level](https://github.com/SoCXin/Level)：72MHz

## [描述](https://github.com/SoCXin/W6100/wiki)

[W6100](https://github.com/SoCXin/W6100)是全球第一款支持IPv4/IPv6双核的新一代全硬件以太网TCP/IP协议栈控制器。W6100在WIZnet核心专利技术——全硬件TCP/IP协议栈IPv4的基础上增加了IPv6，并且支持TCP，UDP，IPv6，IPv4，ICMPv6，ICMPv4，IGMP，ARP以及PPPoE等协议。同时其内部集成了10/100M以太网数据链路层（MAC）以及物理层（PHY），使用户能够更加简单快速地实现嵌入式设备的联网功能。

W6100具有8个独立的硬件SOCKET，并且支持多种SOCKET-less命令，这些命令通过ARP、PINGv4及PINGv6来实现IPv6自动配置、监查和管理网络。

W6100具有SPI和并行总线两种主机接口，并自带32KB的高速数据缓存用于发送和接收数据。同时为了满足日益增加的低功耗需求，W6100提供了网络唤醒（WOL）和以太网PHY掉电模式，方便用户在不同的应用中使用。

此外，W6100提供LQFP48和QFN48两种无铅封装，并且与W5100S PIN-2-PIN兼容。

[![sites](docs/W6100.png)](https://github.com/SoCXin/W6100)

##### 关键特性

* 支持IPv4/IPv6双协议栈
* 支持TCP、UDP、IPv6、IPv4、ICMPv6、ICMPv4、IGMP、MLDv1、ARP、PPPoE
* 支持8个独立SOCKET，同时具有32K的收发缓存
* 支持多种SOCKET-less命令ARP4、ARP6、PING4、PING6、NS（DAD）、RS、UNA
* 支持PHY掉电和关闭系统时钟两种节能模式
* 支持基于UDP协议的网络唤醒（WOL）功能
* 支持串行和并行主机接口高速SPI（MODE 0/3）
* 具有内部32K的收发缓存
* 集成了10BaseT/10BaseTe/100BaseTX的以太网PHY
* 支持auto-MDIX自动极性转换（仅在自动协商模式下）
* 工作电压：3V（I/O耐压5V）
* 48管脚LQFP和QFN两种无铅封装(7x7mm，5mm间距)

### [资源收录](https://github.com/SoCXin/W6100)

* [参考文档](docs/)
* [参考资源](src/)
* [参考工程](project/)

### [选型建议](https://github.com/SoCXin)

[W6100](https://github.com/SoCXin/W6100) 相较于其他的XX32XXX产品，接口相对集中丰富，具有USB、CAN2.0B 、DAC，支持5.5V电压

###  [www.SoC.xin(芯)](http://www.SoC.Xin)

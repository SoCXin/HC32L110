# [HC32L110](https://doc.soc.xin/HC32L110)

[![Build Status](https://github.com/SoCXin/HC32L110/workflows/src/badge.svg)](https://github.com/SoCXin/HC32L110/actions/workflows/src.yml)

* [XHSC](http://www.xhsc.com.cn/): [Cortex-M0](https://github.com/SoCXin/Cortex)
* [L1R1](https://github.com/SoCXin/Level): 32 MHz , [￥3.56](https://item.szlcsc.com/3163073.html)

## [简介](https://github.com/SoCXin/HC32L110/wiki)

[HC32L110](http://www.xhsc.com.cn/Productlist/info.aspx?itemid=1851) 系列是一款旨在延长便携式测量系统的电池使用寿命的超低功耗、Low Pin Count、宽电压
工作范围的 MCU。集成 12 位 1Msps 高精度 SARADC 以及集成了比较器、多路 UART、SPI、I2C 等丰富的通讯外设，具有高整合度、高抗干扰、高可靠性和超低功耗的特点。本产品内核采用 Cortex-M0+内核，配合成熟的 Keil & IAR 调试开发软件，支持 C 语言及汇编语言，汇编指令。

### 关键参数

* 32 MHz Cortex-M0
* 4KB SRAM + 32KB FLASH
* 12 位 1Msps 采样的高速高精度 SARADC，内置运放，可测量外部微弱信号
* 集成 6 位 DAC 和可编程基准输入的 2 路电压比较器 VC
* 集成低电压侦测器 LVD，可配置 16 阶比较电平，可监控端口电压以及电源电压
* 工作温度：-40 ~ 85℃
* 工作电压：1.8 ~ 5.5V
* QFN20，TSSOP20，TSSOP16，CSP16


### 低功耗

* 0.5μA @ 3V 深度休眠模式：所有时钟关闭，上电复位有效，IO 状态保持，IO 中断有效，所有寄存器，RAM 和 CPU 数据保存状态时的功耗
* 1.0μA @3V 深度休眠模式+ RTC 工作
* 6μA@32.768kHz 低速工作模式：CPU 和外设模块运行，从 flash 运行程序
* 20μA/MHz@3V@16MHz 休眠模式：CPU 停止工作，外设模块运行，主时钟运行
* 120μA/MHz@3V@16MHz 工作模式：CPU和外设模块运行，从 Flash 运行程序
* 4μs 超低功耗唤醒时间，使模式切换更加灵活高效，系统反应更为敏捷
* 上述特性为室温下典型值，具体的电气特性、功耗特性参考电气特性章节


## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)

## [选型建议](https://github.com/SoCXin/HC32L110)

[HC32L110](https://item.szlcsc.com/3163073.html)定位小封装低功耗MCU，类似定位的产品较多，例如：

* [STM32L011](https://github.com/SoCXin/STM32L011)
* [CS32L010](https://github.com/SoCXin/CS32L010)
* [MM32L073](https://github.com/SoCXin/MM32L073)

低功耗MCU应用领域相对无线通信SoC而言较受限于通信传输，往往需要外接通信单元，低功耗内核主要应用于待机唤醒和中断检测。

对于GPIO数量要求较高可以或者封装尺寸要求较高的，可以通过查看[STM32L系列](https://www.st.com/zh/microcontrollers-microprocessors/stm32-ultra-low-power-mcus.html)确定目标范围。



## [www.SoC.xin](http://www.SoC.Xin)

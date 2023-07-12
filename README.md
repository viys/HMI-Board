# HMI-Board
## [开发板介绍](https://www.rt-thread.org/document/site/#/rt-thread-version/rt-thread-standard/hw-board/ra6m3-hmi-board/ra6m3-hmi-board?id=开发板介绍)

HMI-Board 为 RT-Thread 联合瑞萨推出的高性价比图形评估套件，取代传统的 HMI + 主控板 硬件，一套硬件即可实现 HMI + IoT + 控制 的全套能力。依托于瑞萨高性能芯片 RA6M3 及 RT-Thread 软件生态，HMI Board 不仅硬件性能强劲，同时软件生态丰富，助力开发者快速开发出 GUI 智能硬件产品。

开发板正面外观如下图：

![img](https://www.rt-thread.org/document/site/rt-thread-version/rt-thread-standard/hw-board/ra6m3-hmi-board/figures/front.png)

开发板背面外观如下图：

![img](https://www.rt-thread.org/document/site/rt-thread-version/rt-thread-standard/hw-board/ra6m3-hmi-board/figures/back.png)

该开发板常用 **板载资源** 如下，搭载 2M Flash 大容量主控芯片 RA6M3，内置 2D 加速、JPEG 编解码器、LCD控制器等模块，助力图形应用开发，并且板载TFT显示屏和音频接口，可以让开发者在 HMI 领域大展身手；此外，HMI-Board 还支持 IoT 连接，板载以太网接口、高速WIFI模块，让开发板无时无刻连接云端；同时，HMI-Board 还支持多种控制方式，包括 CAN 接口、Arduino 接口以及两路 PMOD 接口等，可以让开发者方便地扩展各种外设，从而实现更加灵活的控制方式。

![img](https://www.rt-thread.org/document/site/rt-thread-version/rt-thread-standard/hw-board/ra6m3-hmi-board/figures/resources.png)

通过 HMI-Board 开发板，开发者可以轻松实现 GUI 智能硬件产品。

## [外设支持](https://www.rt-thread.org/document/site/#/rt-thread-version/rt-thread-standard/hw-board/ra6m3-hmi-board/ra6m3-hmi-board?id=外设支持)

本 BSP 目前对外设的支持情况如下：

| **片上外设** | **支持情况** | **备注**                 |
| ------------ | ------------ | ------------------------ |
| UART         | 支持         | UART9 为默认日志输出端口 |
| GPIO         | 支持         |                          |
| LCD          | 支持         |                          |
| SDHI         | 支持         |                          |
| JPEG         | 支持         |                          |
| G2D          | 支持         |                          |
| RW007        | 支持         |                          |
| ETH          | 支持         |                          |
| SPI          | 支持         |                          |
| I2C          | 支持         |                          |
| CAN          | 支持         |                          |

- 注意：BSP默认是最小系统，若需添加/使能其他外设需参考：[外设驱动使用教程 (rt-thread.org)](https://www.rt-thread.org/document/site/#/rt-thread-version/rt-thread-standard/tutorial/make-bsp/renesas-ra/RA系列BSP外设驱动使用教程)
- 文档中心:[📖](https://www.rt-thread.org/document/site/#/rt-thread-version/rt-thread-standard/hw-board/ra6m3-hmi-board/ra6m3-hmi-board)

## 仓库说明:

- sdk-bsp-ra6m3-hmi-board:RTT官方仓库

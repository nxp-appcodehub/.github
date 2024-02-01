# [NXP Application Code Hub](https://mcuxpresso.nxp.com/appcodehub) - Index Of Application SW Packs
[<img src="https://mcuxpresso.nxp.com/static/icon/nxp-logo-color.svg" width="100">]([https://www.nxp.com|https://www.nxp.com/])

## Index
1. [ML State Monitor](#ap-ml-state-monitor)
2. [ML Person Detector](#ap-ml-person-detector)
3. [Conversa Voice Calling Software Pack](#ap-conversa-voice-calling)
4. [DVS With Internal PVT Sensor](#ap-dvs-pvt-sensor)
5. [i.MX RT INDUSTRIAL DRIVE DEVELOPMENT PLATFORM](#ap-qmc2g-industrial)
6. [Power Optimized Voice UI](#ap-optimized-voice-ui)
7. [Basic Matter Ready Connected HMI platform with cost-optimized MCU, Wi-Fi 4, Thread, and BLE 5](#ap-basic-matter-ready-connected-hmi)

<!-- ap-ml-state-monitor -->
## 1. ML State Monitor<a name="ap-ml-state-monitor"></a>
### Overview
This repository holds the ML-Based System State Monitor App SW Pack and depends on the MCUXpresso SDK overall delivery. This Application Software Pack relies on the Deep Learning (DL) subfield of ML and enables developers to develop and deploy neural networks on MCU-based systems for building smart sensing and state monitoring solutions.

#### Families:           Kinetis, LPC, i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, SDIO, SENSOR, UART, TIMER 
#### Categories:         AI/ML, Anomaly Detection, RTOS, SDMMC, Sensor, Tools 
#### Application format: Zephyr Project
#### Compatible boards:
* [FRDM-K66F](https://www.nxp.com/design/development-boards/freedom-development-boards/mcu-boards/freedom-development-platform-for-kinetis-k66-k65-and-k26-mcus:FRDM-K66F)
* [LPCXpresso55S69](https://www.nxp.com/design/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s69-development-board:LPC55S69-EVK)
* [MIMXRT1170-EVK](https://www.nxp.com/design/development-boards/i-mx-evaluation-and-development-boards/i-mx-rt1170-evaluation-kit:MIMXRT1170-EVK)

#### Expansion boards
* [FRDM-STBI-A8974](https://mcuxpresso.nxp.com/eb-hub/product/frdm-stbi-a8974)

#### **Repository URL:** https://github.com/nxp-appcodehub/ap-ml-state-monitor
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=ap-ml-state-monitor

<!-- ap-ml-person-detector -->
## 2. ML Person Detector<a name="ap-ml-person-detector"></a>
### Overview
 This App SW Pack provides a ML example for people detection using eIQ. The software provides customers with product quality code that can be integrated into their designs. 

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY, UART, VIDEO 
#### Categories:         AI/ML, Industrial, Security, Vision 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [EVK-MIMXRT1060](https://www.nxp.com/design/development-boards/i-mx-evaluation-and-development-boards/i-mx-rt1060-evaluation-kit:MIMXRT1060-EVKB)
* [MIMXRT1170-EVK](https://www.nxp.com/design/development-boards/i-mx-evaluation-and-development-boards/i-mx-rt1170-evaluation-kit:MIMXRT1170-EVK)


#### **Repository URL:** https://github.com/nxp-appcodehub/ap-ml-person-detector
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=ap-ml-person-detector

<!-- ap-conversa-voice-calling -->
## 3. Conversa Voice Calling Software Pack<a name="ap-conversa-voice-calling"></a>
### Overview
 This project holds the <a href="https://www.nxp.com/design/software/embedded-software/application-software-packs/application-software-pack-conversa-voice-calling:APP-SW-PACK-CONVERSA-VOICE" target="_blank">Conversa Voice Calling App SW Pack</a>.<br>This application software pack enables a complete voice call application over USB using NXP’s MCUs and <a href="https://www.nxp.com/design/software/embedded-software/conversa-voice-suite:CONVERSA-VOICE-SUITE" target="_blank">Conversa Voice Suite</a>. <br>This project speeds up the evaluation of Voice over Internet Protocol (VoIP) products and provides sufficient audio quality required to meet the Microsoft Teams specification and receive certification.<br><br>The <i>main_rt1170</i> branch contains the conversa voice calling software pack for the <a href="https://www.nxp.com/design/development-boards/i-mx-evaluation-and-development-boards/i-mx-rt1170-evaluation-kit:MIMXRT1170-EVK" target="_blank">i.MX RT1170</a>.<br>The <i>main_lpc55</i> branch branch contains the conversa voice calling software pack for the <a href="https://www.nxp.com/design/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s69-development-board:LPC55S69-EVK" target="_blank">LPC55S69</a>.<br>To see other available devices, please check the other branches.<br><br>

#### Families:           i.MX, LPC 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DMA, SAI, USB, I2S 
#### Categories:         Voice 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S69](https://www.nxp.com/design/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s69-development-board:LPC55S69-EVK)
* [MIMXRT1170-EVK](https://www.nxp.com/design/development-boards/i-mx-evaluation-and-development-boards/i-mx-rt1170-evaluation-kit:MIMXRT1170-EVK)


#### **Repository URL:** https://github.com/nxp-appcodehub/ap-conversa-voice-calling
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=ap-conversa-voice-calling

<!-- ap-dvs-pvt-sensor -->
## 4. DVS With Internal PVT Sensor<a name="ap-dvs-pvt-sensor"></a>
### Overview
 This application showcase the dynamic voltage scaling (DVS) capabilities of i.MX RT500 using the internal PVT sensor. 

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        CLOCKS, I2C, TIMER, UART 
#### Categories:         Low Power, Power Conversion 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [EVK-MIMXRT595](https://www.nxp.com/design/development-boards/i-mx-evaluation-and-development-boards/i-mx-rt595-evaluation-kit:MIMXRT595-EVK)


#### **Repository URL:** https://github.com/nxp-appcodehub/ap-dvs-pvt-sensor
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=ap-dvs-pvt-sensor

<!-- ap-qmc2g-industrial -->
## 5. i.MX RT INDUSTRIAL DRIVE DEVELOPMENT PLATFORM<a name="ap-qmc2g-industrial"></a>
### Overview
 The Industrial Drive Development Platform shows how a single i.MX RT1176 Crossover MCU can control up to four different motors, while managing wired or wireless connectivity and an HMI interface. 

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        ADC, CAN, CLOCKS, DISPLAY, DMA, ETHERNET, FLASH, GPIO, I2C, PWM, SENSOR, SPI, UART, USB, WATCHDOG, TIMER 
#### Categories:         Industrial, RTOS, Secure Provisioning, Security, Sensor, Motor Control, Graphics, Cloud Connected Devices, Time Sensitive Networking 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [ISI-QMC-DGC-02]()


#### **Repository URL:** https://github.com/nxp-appcodehub/ap-qmc2g-industrial
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=ap-qmc2g-industrial

<!-- ap-optimized-voice-ui -->
## 6. Power Optimized Voice UI<a name="ap-optimized-voice-ui"></a>
### Overview
 This Application Software Pack provides a power optimized application featuring local voice control using NXP's <a href="https://www.nxp.com/design/software/embedded-software/voice-intelligent-technology:VOICE-INTELLIGENT-TECHNOLOGY" target="_blank">Voice Intelligent Technology (VIT)</a> on the i.MX RT595 Crossover MCU. 

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, UART, DMA 
#### Categories:         Voice 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [EVK-MIMXRT595](https://www.nxp.com/design/development-boards/i-mx-evaluation-and-development-boards/i-mx-rt595-evaluation-kit:MIMXRT595-EVK)


#### **Repository URL:** https://github.com/nxp-appcodehub/ap-optimized-voice-ui
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=ap-optimized-voice-ui

<!-- ap-basic-matter-ready-connected-hmi -->
## 7. Basic Matter Ready Connected HMI platform with cost-optimized MCU, Wi-Fi 4, Thread, and BLE 5<a name="ap-basic-matter-ready-connected-hmi"></a>
### Overview
 NXP's cost-optimized MCU (FreeRTOS) platform enables Matter-ready edge node development with Wi-Fi 4, Thread, and BLE 5 wireless connectivity protocols using i.MX RT1060 MCU, K32W0x MCU, and 88W8801 Wi-Fi SoC. 

#### Families:           MW, K32W, i.MX RT 
#### Toolchains:         GCC 
#### Peripherals:        DISPLAY, DMA, FLASH, GPIO, I2C, SPI, UART, USB 
#### Categories:         Wireless Connectivity, HMI, Cloud Connected Devices, RTOS 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [EVK-MIMXRT1060](https://www.nxp.com/design/development-boards/i-mx-evaluation-and-development-boards/i-mx-rt1060-evaluation-kit:MIMXRT1060-EVKB)

#### Expansion boards
* [muRata 88W8801 module](https://mcuxpresso.nxp.com/eb-hub/product/murata 88w8801 module)

#### **Repository URL:** https://github.com/nxp-appcodehub/ap-basic-matter-ready-connected-hmi
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=ap-basic-matter-ready-connected-hmi


# [NXP Application Code Hub](https://mcuxpresso.nxp.com/appcodehub) - Index Of Reference Designs
[<img src="https://mcuxpresso.nxp.com/static/icon/nxp-logo-color.svg" width="100">]([https://www.nxp.com|https://www.nxp.com/])

<a id="top"></a>



## Index
1. [How to set up the motion control reference design on iMX.RT1180](#rd-motion-control-slave-servo-mimxrt1180)
2. [i.MX RT106V Based Smart Voice User Interface Solution](#rd-mcu-svui)
3. [NXP EasyEVSE iMXRT106x](#rd-nxp-easyevse-imxrt106x)
4. [Remote IO Platform: ECAT Sample Application](#rd-riop-ecat)
5. [Remote IO Platform: Demo](#rd-riop-demo)

<!-- rd-motion-control-slave-servo-mimxrt1180/. -->
## 1. How to set up the motion control reference design on iMX.RT1180<a id="rd-motion-control-slave-servo-mimxrt1180"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application demonstrates how to implement EtherCAT+ PMSM motor control on the iMX.RT1180.  

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        ADC, ETHERNET, PWM 
#### Categories:         Motor Control, Industrial, Networking 
#### Application format: CMSIS Pack
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/rd-motion-control-slave-servo-mimxrt1180/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=rd-motion-control-slave-servo-mimxrt1180

<!-- rd-mcu-svui/. -->
## 2. i.MX RT106V Based Smart Voice User Interface Solution<a id="rd-mcu-svui"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This NXP EdgeReady solution for both local and online voice control leverages the i.MX RT106V crossover MCU, with integrated Voice Intelligent Technology (VIT) Speech to Intent offering a natural voice user interface for touchless applications. This ultra-small form-factor, production ready hardware design comes with fully integrated software running on FreeRTOS, for quick out-of-the-box evaluation and proof of concept development. This turnkey solution minimizes time to market, risk, and development effort enabling OEMs to easily add voice to their smart home and smart appliance products. This NXP EdgeReady solution is part of the EdgeVerse™ edge computing platform. The October 2024 software update enables Wifi connectivity and incorporates the Matter interoperability standard for IoT devices along with NXP’s proprietary Speech to Intent (S2I) natural language voice control for the edge. With this upgrade, developers can now use RT106V to design Matter connected IoT nodes and control any node on the system with natural voice commands. 

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        CLOCKS, DMA, FLASH, GPIO, I2S, PWM, SPI, UART, USB, SDMMC, SDIO, SAI, FlexIO 
#### Categories:         Voice, HMI, Audio, RTOS, User Interface 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/rd-mcu-svui/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=rd-mcu-svui

<!-- rd-nxp-easyevse-imxrt106x/. -->
## 3. NXP EasyEVSE iMXRT106x<a id="rd-nxp-easyevse-imxrt106x"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 EasyEVSE is a simulated electric vehicle charging station, J1772 compliant, connected to the Microsoft Azure IoT Central over Ethernet or Wi-Fi communication. The provided application is available in 2 flavors. One is the basic enablement, available on github, while the full enablement can be found at nxp.com.&nbsp;<br>Basic enablement provides:<ul><li>Graphical UI using LVGL and NXP Gui Guider tool</li><li>Network connectivity using either Ethernet or Wi-Fi<br></li><li>Secure Microsoft Azure Cloud connectivity using the SE050 secure element</li><li>EVSE-SIG-BRD add-on development board communication for J1772 vehicle charger standard</li><li>Kinetis KM3x Metrology MCU communication.</li></ul>Full enablement provides the following additional functionalities:<br><ul><li>Integration with Sevenstax ISO15118-2 high level charging protocol using the&nbsp;HomePlug Green PHY (HPGP) transceiver (Lumissil IS32CG5317)</li><li>integration with NXP CLRC663 NFC for external identification method</li></ul>

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY, DMA, ETHERNET, FLASH, GPIO, I2C, SPI, UART, USB, SDMMC, SDIO 
#### Categories:         HMI, Cloud Connected Devices, Industrial, RTOS, Networking, Wireless Connectivity, User Interface 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [EVK-MIMXRT1060](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1060-evaluation-kit:MIMXRT1060-EVKB)
* [EVK-MIMXRT1064](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1064-evaluation-kit:MIMXRT1064-EVK)

#### Expansion boards
* [RK043FN66HS-CTG](https://mcuxpresso.nxp.com/eb-hub/product/rk043fn66hs-ctg)
* [OM-SE050ARD-E](https://mcuxpresso.nxp.com/eb-hub/product/om-se050ard-e)
* [muRata IW416 module](https://mcuxpresso.nxp.com/eb-hub/product/murata iw416 module)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/rd-nxp-easyevse-imxrt106x/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=rd-nxp-easyevse-imxrt106x

<!-- rd-riop-ecat/. -->
## 4. Remote IO Platform: ECAT Sample Application<a id="rd-riop-ecat"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This application showcases the analog and digital I/O features supported by the Remote IO Platform in combination with the EtherCAT industrial protocol. The platform communicates over ethernet with a TwinCAT-driven soft-PLC application running on a PC.<br /><br />    The features include:<br /><ul><li>Signal generator</li><li>MCU Digital Input pin control</li><li>MCU Digital Output pin control</li><li>AFE Digital I/Os control</li><li>External Voltage Signal Measurement (HVSIG)</li><li>Current Measurement</li><li>Temperature Measurement</li><li>Internal Voltage References measurement (LVSIG)</li><li>Voltage Calibration</li><li>Resistance Calibration</li></ul>

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        ADC, CAN, CLOCKS, DMA, ETHERNET, FLASH, GPIO, PINCTRL, PWM, SPI, TIMER, UART 
#### Categories:         Sensor, Industrial, RTOS, Networking, Analog Front End 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/rd-riop-ecat/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=rd-riop-ecat

<!-- rd-riop-demo/. -->
## 5. Remote IO Platform: Demo<a id="rd-riop-demo"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This application showcases the analog and digital I/O features supported by the Remote IO Platform without using any industrial protocols. The platform communicates with a PC-based FreeMASTER application via NETC over ethernet. <br /><br />    The features include:<br /><ul><li>Signal generator</li><li>MCU Digital Input pin control</li><li>MCU Digital Output pin control</li><li>AFE Digital I/Os control</li><li>External Voltage Signal Measurement (HVSIG)</li><li>Current Measurement</li><li>Temperature Measurement</li><li>Internal Voltage References measurement (LVSIG)</li><li>Voltage Calibration</li><li>Resistance Calibration</li></ul>The application comes pre-programmed into the Remote IO Platform and is part of the Out-of-Box Experience. It is supported by MCUXpresso IDE and VS Code.

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        ADC, CAN, CLOCKS, DMA, ETHERNET, FLASH, GPIO, PINCTRL, PWM, SPI, TIMER, UART 
#### Categories:         Sensor, Industrial, RTOS, Networking, Analog Front End 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/rd-riop-demo/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=rd-riop-demo


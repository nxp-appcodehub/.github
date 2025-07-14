# [NXP Application Code Hub](https://mcuxpresso.nxp.com/appcodehub) - Index Of Application Notes
[<img src="https://mcuxpresso.nxp.com/static/icon/nxp-logo-color.svg" width="100">]([https://www.nxp.com|https://www.nxp.com/])

<a id="top"></a>

## Index
1. [AN13569 How to run dual-servo motor on LPC553x](#an-lpc553x-dual-servo-motor-control_.)
2. [AN13793: FLAC codec porting and performance evaluation based on i.MX RT685](#an-flac-codec-rt685_.)
3. [AN12125: Using LPC802 as I2C-bus EEPROM](#an-lpc802_io_eeprom_.)
4. [AN12126: Using LPC802 as an I2C I/O expander](#an-lpc802_io_expander_.)
5. [multiple-usb-audio-formats-on-lpc5500](#an-multiple-usb-audio-formats-on-lpc5500_.)
6. [LPC55S36_mc_bldc_wHall](#an-lpc55s36_mc_bldc_whall_.)
7. [AN13498: PowerQuad digital signal processing on NXP LPC553x/LPC55S3x](#an-dsp_for_lpc553x_using_pq_.)
8. [flexio_camera_rt1010](#an-flexio_camera_rt1010_.)
9. [AN13437: Triggering ADC multi-channel conversion via low power interrupt timer on KE17Z](#an-ftm_lpit_adc12_multi_channel_.)
10. [AN13075：i.MX RT1170 heterogeneous graphics pipeline](#an-graphics_features_rt1170_.)
11. [DRM172: Half bridge LLC converter based on MC56F81xxx](#an-hbllc_mc56f8xxxx_.)
12. [AN12110: Developing a camera application with i.MX RT series](#an-hd_camera_rt1050_.)
13. [AN13730: Developing a GUI on a memory constrained MCU with GUI Guider and LVGL](#an-lvgl_demo_for_small_mcu_.)
14. [DRM174: Totem-pole power factor correction using MC56F81xxx](#an-tppfc_mc56f8xxxx_.)
15. [AN12103: Simple USB video class device on i.MX RT1050](#an-uvc_imxrt_.)
16. [AN13778: Porting VGLite driver for bare metal or single task](#an-vglite_porting_imxrt_.)
17. [AN12822: Emulation of 8080 bus via FlexIO on RT1050](#an-flexio_8080_rt1050_.)
18. [AN13184: 3-phase PMSM sensorless vector control and 2-phase interleaved PFC on MC56F83783](#an-mc_pfc_56f83783_.)
19. [AN13496: Computing FFT with PowerQuad and CMSIS-DSP on LPC5500](#an-fft_with_pq_and_cmsis_dsp_.)
20. [AN13497: Firmware update using secondary bootloader](#an-fw_update_using_sec_bootloader_.)
21. [lpc_uart_server](#an-lpc_uart_server_.)
22. [mipi-dsi-screen-pushing-rt500](#an-mipi-dsi-screen-pushing-rt500_.)
23. [AN12004: Low-Power Motion Wake-Up Examples for FXLS8974CF using Sensor Data Change Detection (SDCD) Block](#an-fxls8974cf-low-power-wake-up-examples_.)
24. [MCX N PLU setup and usage](#an-mcxn-plu-setupandusage_.)
25. [AN14099: PMSM Sensorless FOC Using MCXA153](#an-pmsm-foc-mcxa153_.)
26. [Using the Real Time Clock (RTC) on MCX](#an-mcx-rtc-example_.)
27. [USB to CAN-FD Adaptor based on MCXN Microcontroller](#an-usb-to-can-adaptor-mcxn947_.)
28. [Using SLCD controller on MCXC444 MCU](#an-using-slcd-controller-on-mcxc444_.)
29. [USB to Multi VCOM on MCXC444 Series MCU](#an-usb-to-multi-vcom-on-mcxc444_.)
30. [AN13768: LCD display On/Off switching in low-power mode on i.MX RT1170](#an-display_low_power_rt1170_.)
31. [How to use In-System Programming (ISP) on FRDM-RW612](#an-frdmrw612-in-system-programming_.)
32. [AN14354: Multimode bidirectional AC-DC converter design using MC56F83783](#an-bidirectional-acdc-mc56f83783_.)
33. [AN14333: Bidirectional Resonant DC-DC Converter Design using MC56F83783](#an-bidirectional-dcdc-mc56f83783_.)
34. [XIP from external NOR flash and configuring external pSRAM using multiport FlexSPI module](#an-xip-external-nor-flash-plus-external-psram_.)
35. [AN13953 Integrating NFC Reader Library in a KW4x Bluetooth Low Energy Application](#an-kw4x-bluetooth-le-nfc-integration_.)
36. [AN14017 Permanent Magnet Synchronous Motors One-shunt Control Using LPC86x](#an-pmsm-one-shunt-lpc86x_.)
37. [AN14018: Sensorless Brushless DC(BLDC) Motor Control on LPC86x](#an-mc-bldc-lpc86x_.)
38. [Sensorless BLDC motor control on KE17Z](#an-mc-bldc-ke17z_.)
39. [AN14434 How to implement MCXN236 USB to I3C demo](#an-mcxn236-usb-bridge-to-i3c_.)
40. [Migration guide from FRDM-RW612 to third-party module memories](#an-frdmrw612-module-migration-guide_.)
41. [Sensorless BLDC motor control on MCXA153](#an-mc-bldc-mcxa153_.)
42. [AN14605 Using the RTC OSC Calibration Feature of the LPC5500](#an-lpc55s69-rtc-osc-calibration_.)
43. [AN12149: Implementing an IEEE 1588 V2 on i.MX RT  Using PTPd, FreeRTOS, and lwIP TCP/IP  stack](#an-ethernet-lwip-ptpd-imxrt_.)
44. [emulating i2s bus with flexio on mcxa156](#an-emulating-i2s-bus-with-flexio-on-mcxa156_.)

<!-- an-lpc553x-dual-servo-motor-control/. -->
## 1. AN13569 How to run dual-servo motor on LPC553x<a id="an-lpc553x-dual-servo-motor-control_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application note describes the dual servo demo with the NXP LPC55S36 processor. It also can be used as a reference for motor control application developing based on other products. 

#### Families:           LPC 
#### Toolchains:         IAR 
#### Peripherals:        ADC, GPIO, CLOCKS, PWM, UART, TIMER 
#### Categories:         Motor Control 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S36](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s36-development-board:LPCXpresso55S36)

#### Expansion boards
* [FRDM-MC-LVPMSM](https://mcuxpresso.nxp.com/eb-hub/product/frdm-mc-lvpmsm)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-lpc553x-dual-servo-motor-control/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-lpc553x-dual-servo-motor-control

<!-- an-flac-codec-rt685/. -->
## 2. AN13793: FLAC codec porting and performance evaluation based on i.MX RT685<a id="an-flac-codec-rt685_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
The FLAC demo application demonstrates how to porting FLAC and evaluation performance&nbsp;on i.MXRT685 evk board.

#### Families:           i.MX RT 
#### Toolchains:         IAR 
#### Peripherals:        SDMMC, UART, GPIO 
#### Categories:         Audio, RTOS, SDMMC 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [EVK-MIMXRT685](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt600-evaluation-kit:MIMXRT685-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-flac-codec-rt685/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-flac-codec-rt685

<!-- an-lpc802_io_eeprom/. -->
## 3. AN12125: Using LPC802 as I2C-bus EEPROM<a id="an-lpc802_io_eeprom_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 AN12125: Using LPC802 as I2C-bus EEPROM&nbsp; 

#### Families:           LPC 
#### Toolchains:         MDK 
#### Peripherals:        UART, GPIO, FLASH 
#### Categories:         Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso802](https://www.nxp.com/products/processors-and-microcontrollers/arm-microcontrollers/general-purpose-mcus/lpc800-arm-cortex-m0-plus-/lpcxpresso802-for-the-lpc802-family-of-mcus:OM40000)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-lpc802_io_eeprom/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-lpc802_io_eeprom

<!-- an-lpc802_io_expander/. -->
## 4. AN12126: Using LPC802 as an I2C I/O expander<a id="an-lpc802_io_expander_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application note introduces how to use LPC802 as I/O expander via the I2C-bus interface. Please refer to AN12126 for complete instructions on how to use this software. https://www.nxp.com/docs/en/application-note/AN12126.pdf 

#### Families:           LPC 
#### Toolchains:         MDK 
#### Peripherals:        UART, GPIO, FLASH 
#### Categories:         Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso802](https://www.nxp.com/products/processors-and-microcontrollers/arm-microcontrollers/general-purpose-mcus/lpc800-arm-cortex-m0-plus-/lpcxpresso802-for-the-lpc802-family-of-mcus:OM40000)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-lpc802_io_expander/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-lpc802_io_expander

<!-- an-multiple-usb-audio-formats-on-lpc5500/. -->
## 5. multiple-usb-audio-formats-on-lpc5500<a id="an-multiple-usb-audio-formats-on-lpc5500_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application note will show you how to implement multiple USB audio formats on LPC5500 series. 

#### Families:           LPC 
#### Toolchains:         MDK 
#### Peripherals:        DMA, I2S, USB 
#### Categories:         Audio 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S69](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s69-development-board:LPC55S69-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-multiple-usb-audio-formats-on-lpc5500/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-multiple-usb-audio-formats-on-lpc5500

<!-- an-lpc55s36_mc_bldc_whall/. -->
## 6. LPC55S36_mc_bldc_wHall<a id="an-lpc55s36_mc_bldc_whall_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application note describes the implementation of the 3-phase Brushless DC motor (BLDC) control with Hall sensor based on the NXP LPC55S36 processor. Please refer to AN13571 for complete instructions on how to use this software.&nbsp;<a href="https://www.nxp.com/docs/en/application-note/AN13571.pdf" target="_blank"></a><a href="https://www.nxp.com/docs/en/application-note/AN13571.pdf" target="_blank">https://www.nxp.com/docs/en/application-note/AN13571.pdf</a>.<br>The LPC55S3x/LPC553x is an Arm Cortex-M33 based microcontroller for embedded applications. These devices include up to 256 KB on-chip flash, up to 128 KB of on-chip SRAM, one SCTimer/PWM, eight flexible serial communication peripherals (which can be configured as a USART, SPI, high speed SPI, I2C, or I2S interface), two 16-bit 2.0 Msamples/sec ADCs capable of four simultaneous conversions, four comparators, two temperature sensors, three 12-bit 1 Msample/sec DACs, three OpAmps, two FlexPWM timers. The Arm Cortex-M33 provides a security foundation, offering isolation to protect valuable IP and data with TrustZone® technology. It simplifies the design and software development of digital signal control systems with the integrated digital signal processing (DSP) instructions.<br>This application note mainly introduces the principle of BLDC six-step control with hall sensor, hardware and software implementation, including a detailed peripheral setup and driver description.<br>

#### Families:           LPC 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        ADC, PWM, GPIO, TIMER 
#### Categories:         Motor Control 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S36](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s36-development-board:LPCXpresso55S36)

#### Expansion boards
* [FRDM-MC-LVPMSM](https://mcuxpresso.nxp.com/eb-hub/product/frdm-mc-lvpmsm)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-lpc55s36_mc_bldc_whall/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-lpc55s36_mc_bldc_whall

<!-- an-dsp_for_lpc553x_using_pq/. -->
## 7. AN13498: PowerQuad digital signal processing on NXP LPC553x/LPC55S3x<a id="an-dsp_for_lpc553x_using_pq_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 AN13498: Digital Signal Processing for NXP LPC553x/LPC55S3x Using PowerQuad 

#### Families:           LPC 
#### Toolchains:         MDK 
#### Peripherals:        UART, GPIO, FLASH 
#### Categories:         Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S36](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s36-development-board:LPCXpresso55S36)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-dsp_for_lpc553x_using_pq/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-dsp_for_lpc553x_using_pq

<!-- an-flexio_camera_rt1010/. -->
## 8. flexio_camera_rt1010<a id="an-flexio_camera_rt1010_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This software accompanies application note [AN12686](https://www.nxp.com/docs/en/application-note/AN12686.pdf), which describes how to&nbsp;use the FlexIO to emulate the parallel camera interface to receive real-time image data from a camera device based on i.MX RT1010. 

#### Families:           i.MX RT 
#### Toolchains:         IAR 
#### Peripherals:        VIDEO, I2C, SPI 
#### Categories:         Graphics, Vision 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-flexio_camera_rt1010/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-flexio_camera_rt1010

<!-- an-ftm_lpit_adc12_multi_channel/. -->
## 9. AN13437: Triggering ADC multi-channel conversion via low power interrupt timer on KE17Z<a id="an-ftm_lpit_adc12_multi_channel_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
The demo code shows the implementation of periodic triggering of the four ADC channels using LPIT0.

#### Families:           Kinetis 
#### Toolchains:         IAR 
#### Peripherals:        ADC, PWM, TIMER 
#### Categories:         Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-KE17Z](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/freedom-development-platform-for-72mhz-ke17z-ke13z-ke12z-mcus:FRDM-KE17Z)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-ftm_lpit_adc12_multi_channel/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-ftm_lpit_adc12_multi_channel

<!-- an-graphics_features_rt1170/. -->
## 10. AN13075：i.MX RT1170 heterogeneous graphics pipeline<a id="an-graphics_features_rt1170_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application note gives a brief overview of each one of the graphics engines (PxP, GPU2D, and LCDIFv2) how to initialize them, use them independently, and finally, it introduces a use case on how to use them in unison to get a performance and resource boost. Each stage has an associated software project to make things easier. 

#### Families:           i.MX RT 
#### Toolchains:         IAR 
#### Peripherals:        DISPLAY 
#### Categories:         Graphics 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MIMXRT1170-EVKB](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1170-evaluation-kit:MIMXRT1170-EVKB)
* [MIMXRT1170-EVK]()


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-graphics_features_rt1170/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-graphics_features_rt1170

<!-- an-hbllc_mc56f8xxxx/. -->
## 11. DRM172: Half bridge LLC converter based on MC56F81xxx<a id="an-hbllc_mc56f8xxxx_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This is an LLC resonant converter reference design using MC56F8xxxx DSC. 

#### Families:           DSC 
#### Toolchains:         CodeWarrior 
#### Peripherals:        ADC, FLASH, GPIO, PWM, TIMER, UART 
#### Categories:         Power Conversion 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-hbllc_mc56f8xxxx/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-hbllc_mc56f8xxxx

<!-- an-hd_camera_rt1050/. -->
## 12. AN12110: Developing a camera application with i.MX RT series<a id="an-hd_camera_rt1050_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This software accompanies application note [AN12110](https://www.nxp.com/docs/en/application-note/AN12110.pdf), which describes how to develop an HD camera application with the NXP i.MX RT1050 processor. 

#### Families:           i.MX RT 
#### Toolchains:         IAR 
#### Peripherals:        VIDEO, DISPLAY, SDMMC 
#### Categories:         Graphics, Vision, SDMMC 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [EVKB-IMXRT1050](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1050-evaluation-kit:MIMXRT1050-EVK)
* [EVK-MIMXRT1050](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1050-evaluation-kit:MIMXRT1050-EVK)

#### Expansion boards
* [RK043FN66HS-CTG](https://mcuxpresso.nxp.com/eb-hub/product/rk043fn66hs-ctg)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-hd_camera_rt1050/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-hd_camera_rt1050

<!-- an-lvgl_demo_for_small_mcu/. -->
## 13. AN13730: Developing a GUI on a memory constrained MCU with GUI Guider and LVGL<a id="an-lvgl_demo_for_small_mcu_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo is an example of dashboard for electric bicycle. This demo is based on LVGL GUI library and GUI Guider. This demo can be used by customer to evaluate GUI performance of NXP part. Here, this demo uses LPC5506 as target MCU and uses an external SPI Flash to store image source and font source. This demo supports various GUI widget to show customer information such as meter panel, chart, label. 

#### Families:           LPC 
#### Toolchains:         MDK 
#### Peripherals:        DISPLAY 
#### Categories:         Graphics 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-lvgl_demo_for_small_mcu/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-lvgl_demo_for_small_mcu

<!-- an-tppfc_mc56f8xxxx/. -->
## 14. DRM174: Totem-pole power factor correction using MC56F81xxx<a id="an-tppfc_mc56f8xxxx_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This is a totem-pole bridgeless power factor correction reference design using MC56F8xxxx DSC. 

#### Families:           DSC 
#### Toolchains:         CodeWarrior 
#### Peripherals:        ADC, CLOCKS, FLASH, GPIO, PWM, TIMER, UART 
#### Categories:         Power Conversion 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-tppfc_mc56f8xxxx/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-tppfc_mc56f8xxxx

<!-- an-uvc_imxrt/. -->
## 15. AN12103: Simple USB video class device on i.MX RT1050<a id="an-uvc_imxrt_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This software accompanies application note [AN12103](https://www.nxp.com/docs/en/application-note/AN12103.pdf), which describes how to develop a simple UVC device using the NXP i.MX RT1050 or i.MX RT1170 processor. 

#### Families:           i.MX RT 
#### Toolchains:         IAR 
#### Peripherals:        VIDEO, USB 
#### Categories:         Graphics, Vision 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [EVKB-IMXRT1050](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1050-evaluation-kit:MIMXRT1050-EVK)
* [MIMXRT1170-EVKB](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1170-evaluation-kit:MIMXRT1170-EVKB)
* [MIMXRT1170-EVK]()
* [EVK-MIMXRT1050](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1050-evaluation-kit:MIMXRT1050-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-uvc_imxrt/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-uvc_imxrt

<!-- an-vglite_porting_imxrt/. -->
## 16. AN13778: Porting VGLite driver for bare metal or single task<a id="an-vglite_porting_imxrt_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application outlines the software structure of vglite middleware, analyzes current driver code to support multitask, then gives the details on how to port vglite middleware for bare metal and single task. The ported source code and its examples are provided. 

#### Families:           i.MX RT 
#### Toolchains:         IAR 
#### Peripherals:        DISPLAY 
#### Categories:         Graphics 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MIMXRT1170-EVKB](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1170-evaluation-kit:MIMXRT1170-EVKB)
* [MIMXRT1170-EVK]()


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-vglite_porting_imxrt/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-vglite_porting_imxrt

<!-- an-flexio_8080_rt1050/. -->
## 17. AN12822: Emulation of 8080 bus via FlexIO on RT1050<a id="an-flexio_8080_rt1050_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This example shows how to use the FlexIO module to emulate the 8080 parallel bus and to drive a graphic TFT LCD with the 8080 bus interface. 

#### Families:           i.MX RT 
#### Toolchains:         IAR 
#### Peripherals:        DISPLAY 
#### Categories:         Graphics 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-flexio_8080_rt1050/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-flexio_8080_rt1050

<!-- an-mc_pfc_56f83783/. -->
## 18. AN13184: 3-phase PMSM sensorless vector control and 2-phase interleaved PFC on MC56F83783<a id="an-mc_pfc_56f83783_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 One PMSM Sensorless FOC and 2-ph Interleaved Boost PFC<br>Control based on MC56F83783 <br>

#### Families:           DSC 
#### Toolchains:         CodeWarrior 
#### Peripherals:        ADC, PWM, TIMER, UART 
#### Categories:         Motor Control, Industrial, Power Conversion 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:

#### Expansion boards
* [HVP-MC3PH](https://mcuxpresso.nxp.com/eb-hub/product/hvp-mc3ph)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-mc_pfc_56f83783/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-mc_pfc_56f83783

<!-- an-fft_with_pq_and_cmsis_dsp/. -->
## 19. AN13496: Computing FFT with PowerQuad and CMSIS-DSP on LPC5500<a id="an-fft_with_pq_and_cmsis_dsp_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 AN13496: Computing FFT with PowerQuad and CMSIS-DSP on LPC5500 

#### Families:           LPC 
#### Toolchains:         MDK 
#### Peripherals:        UART, GPIO, FLASH 
#### Categories:         Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S69](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s69-development-board:LPC55S69-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-fft_with_pq_and_cmsis_dsp/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-fft_with_pq_and_cmsis_dsp

<!-- an-fw_update_using_sec_bootloader/. -->
## 20. AN13497: Firmware update using secondary bootloader<a id="an-fw_update_using_sec_bootloader_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 AN13497: Firmware Update Using Secondary Bootloader 

#### Families:           LPC 
#### Toolchains:         MDK 
#### Peripherals:        UART, GPIO, FLASH 
#### Categories:         Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S69](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s69-development-board:LPC55S69-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-fw_update_using_sec_bootloader/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-fw_update_using_sec_bootloader

<!-- an-lpc_uart_server/. -->
## 21. lpc_uart_server<a id="an-lpc_uart_server_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 AN12625 Multi-TTY ExpansioUSB to uart sever based on lpc54018 and lpc54608 

#### Families:           LPC 
#### Toolchains:         MDK 
#### Peripherals:        DMA, UART, USB 
#### Categories:         Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso54018](https://www.nxp.com/products/interfaces/usb-interfaces/lpcxpresso54018-development-board:OM40003)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-lpc_uart_server/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-lpc_uart_server

<!-- an-mipi-dsi-screen-pushing-rt500/. -->
## 22. mipi-dsi-screen-pushing-rt500<a id="an-mipi-dsi-screen-pushing-rt500_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application code is to illustrate graphics drawing methods and performance comparisons under different conditions based on i.MX RT595. 

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        CLOCKS, DMA, GPIO, TIMER, UART 
#### Categories:         Graphics 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [EVK-MIMXRT595](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt595-evaluation-kit:MIMXRT595-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-mipi-dsi-screen-pushing-rt500/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-mipi-dsi-screen-pushing-rt500

<!-- an-fxls8974cf-low-power-wake-up-examples/. -->
## 23. AN12004: Low-Power Motion Wake-Up Examples for FXLS8974CF using Sensor Data Change Detection (SDCD) Block<a id="an-fxls8974cf-low-power-wake-up-examples_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
<ul><li>This software describes how to configure SDCD block of FXLS897xCF sensor to enable low-power motion wake-up in interrupt mode and use auto-wake/sleep feature to autonomously put the sensor back to low-power sleep mode when no-motion is detected for configured auto-sleep timer.<br></li></ul>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, SPI, UART 
#### Categories:         Low Power, Sensor 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MCX-N9XX-EVK](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/evaluation-kit-for-mcx-n94x-mcus:MCX-N9XX-EVK)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [FRDM-STBI-A8974](https://mcuxpresso.nxp.com/eb-hub/product/frdm-stbi-a8974)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-fxls8974cf-low-power-wake-up-examples/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-fxls8974cf-low-power-wake-up-examples

<!-- an-mcxn-plu-setupandusage/. -->
## 24. MCX N PLU setup and usage<a id="an-mcxn-plu-setupandusage_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application note explains the elements that compose the PLU module and how to integrate them to achieve logic networks, as well as providing examples of combinational, sequential and wakeup circuits. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        PLU 
#### Categories:         Low Power 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-mcxn-plu-setupandusage/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-mcxn-plu-setupandusage

<!-- an-pmsm-foc-mcxa153/. -->
## 25. AN14099: PMSM Sensorless FOC Using MCXA153<a id="an-pmsm-foc-mcxa153_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application note describes the implementation of sensorless flux oriented control(FOC) application for 3-phase Permanent Magnet Synchronous Motors (PMSM) on the FRDM-MCXA153 board based on the NXP MCXA153 MCU. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        ADC, PWM 
#### Categories:         Motor Control 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)

#### Expansion boards
* [FRDM-MC-LVPMSM](https://mcuxpresso.nxp.com/eb-hub/product/frdm-mc-lvpmsm)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-pmsm-foc-mcxa153/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-pmsm-foc-mcxa153

<!-- an-mcx-rtc-example/. -->
## 26. Using the Real Time Clock (RTC) on MCX<a id="an-mcx-rtc-example_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This example serves as a guide on enabling the RTC module on MCX, selecting the correct clock source, enable the time keeping functions, enabling the alarm mode and wake timer to wake the MCU from a Deep Power Down state. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        CLOCKS 
#### Categories:         Low Power 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MCX-N9XX-EVK](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/evaluation-kit-for-mcx-n94x-mcus:MCX-N9XX-EVK)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-mcx-rtc-example/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-mcx-rtc-example

<!-- an-usb-to-can-adaptor-mcxn947/. -->
## 27. USB to CAN-FD Adaptor based on MCXN Microcontroller<a id="an-usb-to-can-adaptor-mcxn947_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application note aims to build a USB to CAN-FD adaptor where the USB data retransmit to CAN-bus and vice versa. NXP MCXN devices a high-speed USB port and CAN-FD controllers. HS USB can reach up to 480 Mbit/s transmission speed, which is enough for transmitting CAN-FD frame at highest CAN baud rate on MCXN 8Mbit/s. To make the system easy to use and compatible with other devices, we use USB CDC virtual COM port as communication. Python Interface is used to visualize the CAN-FD information in ASCII format. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        CAN, USB 
#### Categories:         Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MCX-N9XX-EVK](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/evaluation-kit-for-mcx-n94x-mcus:MCX-N9XX-EVK)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-usb-to-can-adaptor-mcxn947/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-usb-to-can-adaptor-mcxn947

<!-- an-using-slcd-controller-on-mcxc444/. -->
## 28. Using SLCD controller on MCXC444 MCU<a id="an-using-slcd-controller-on-mcxc444_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 SLCD is one of the oldest display technologies. It is still one of the most popular technologies, due to the lowest price and power consumption. <br>     <br> Segment LCD displays, also called static displays or glass-only displays, consist of two pieces of Indium Tin Oxide (ITO) glass with a twisted nematic fluid sandwiched in between. A static display is a segment display with one pin for each segment. A segment is any line, dot, or symbol that can be turned on and off independently. NXP MCXC444 MCU integrates an SLCD controller module with up to eight backplanes and 47 frontplanes, such as, 8 × 47 or 4 × 51. This document describes the usage of on-chip SLCD controller by enabling an SLCD device, S401M16KR, which is a four- digit 0.17" seven segment custom LCD panel. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY 
#### Categories:         HMI 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXC444](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c444-mcus:FRDM-MCXC444)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-using-slcd-controller-on-mcxc444/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-using-slcd-controller-on-mcxc444

<!-- an-usb-to-multi-vcom-on-mcxc444/. -->
## 29. USB to Multi VCOM on MCXC444 Series MCU<a id="an-usb-to-multi-vcom-on-mcxc444_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 usb-to-multi-vcom-on-mcxc444 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        USB 
#### Categories:         Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXC444](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c444-mcus:FRDM-MCXC444)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-usb-to-multi-vcom-on-mcxc444/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-usb-to-multi-vcom-on-mcxc444

<!-- an-display_low_power_rt1170/. -->
## 30. AN13768: LCD display On/Off switching in low-power mode on i.MX RT1170<a id="an-display_low_power_rt1170_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application note describes how to add low-power mode operation on the Mobile Industry Processor Interface (MIPI) Display Serial Interface (DSI) host controller and LCDIFv2 controller. It is done to drive a DSI-compliant LCD panel on i.MX RT1170 to switch off and then back on again. 

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY 
#### Categories:         Graphics 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MIMXRT1170-EVK]()


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-display_low_power_rt1170/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-display_low_power_rt1170

<!-- an-frdmrw612-in-system-programming/. -->
## 31. How to use In-System Programming (ISP) on FRDM-RW612<a id="an-frdmrw612-in-system-programming_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This Application Note shows you how to use the In-System Programming (ISP) feature of the RW61x family to program the external flash on the RW612-FRDM board. The RW family counts with on-chip ROM containing In-System Programming capability, supporting UART, SPI, I2C and USB flash programming (store application code and data), as well as APIs for user code and In-application-programming functionality by the IAP API, via the unified memory interface or the secondary bootloader API. 

#### Families:           RW 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        I2C, SPI, UART, USB 
#### Categories:         Tools 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-frdmrw612-in-system-programming/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-frdmrw612-in-system-programming

<!-- an-bidirectional-acdc-mc56f83783/. -->
## 32. AN14354: Multimode bidirectional AC-DC converter design using MC56F83783<a id="an-bidirectional-acdc-mc56f83783_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This software accompanies application note AN14354, which describes how to design a multimode bidirectional ACDC converter using MC56F83783. 

#### Families:           DSC 
#### Toolchains:         CodeWarrior 
#### Peripherals:        ADC, GPIO, PWM, TIMER 
#### Categories:         Power Conversion 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-bidirectional-acdc-mc56f83783/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-bidirectional-acdc-mc56f83783

<!-- an-bidirectional-dcdc-mc56f83783/. -->
## 33. AN14333: Bidirectional Resonant DC-DC Converter Design using MC56F83783<a id="an-bidirectional-dcdc-mc56f83783_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This is a bidirectional CLLC resonant converter reference design using MC56F83783 DSC. 

#### Families:           DSC 
#### Toolchains:         CodeWarrior 
#### Peripherals:        ADC, GPIO, PWM, TIMER 
#### Categories:         Power Conversion 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-bidirectional-dcdc-mc56f83783/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-bidirectional-dcdc-mc56f83783

<!-- an-xip-external-nor-flash-plus-external-psram/. -->
## 34. XIP from external NOR flash and configuring external pSRAM using multiport FlexSPI module<a id="an-xip-external-nor-flash-plus-external-psram_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 RW61x has a FlexSPI module with two ports that allows you to connect two QSPI/SPI memories allowing to perform XIP from one of them. This application note will guide you step by step how to configure the NOR flash connected to the portA and perform XIP and configure a pSRAM memory connected to the portB and access them through the AHB bus (cache) and IP bus. 

#### Families:           RW 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        SPI, FLASH 
#### Categories:         Memory 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-xip-external-nor-flash-plus-external-psram/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-xip-external-nor-flash-plus-external-psram

<!-- an-kw4x-bluetooth-le-nfc-integration/. -->
## 35. AN13953 Integrating NFC Reader Library in a KW4x Bluetooth Low Energy Application<a id="an-kw4x-bluetooth-le-nfc-integration_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This software accompanies application note [AN13953], which gives instructions on how to create a Bluetooth Low Energy project for the EVK-KW45 development board and MCUXpresso IDE, and how to integrate NFC Reader Library.  

#### Families:           Kinetis, K32W, PN 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        UART, GPIO, SPI, TIMER 
#### Categories:         Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [KW45B41Z-EVK]()
* [K32W148-EVK](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/k32w148-evaluation-kit-with-multiprotocol-radio:K32W148-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-kw4x-bluetooth-le-nfc-integration/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-kw4x-bluetooth-le-nfc-integration

<!-- an-pmsm-one-shunt-lpc86x/. -->
## 36. AN14017 Permanent Magnet Synchronous Motors One-shunt Control Using LPC86x<a id="an-pmsm-one-shunt-lpc86x_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This project implements sensorless one-shunt FOC on NXP LPCXpresso860-MAX board. Refer README to set up demo hardware. Peripheral setup, driver description and control algorithms are described in AN14017. 

#### Families:           LPC 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        ADC, PWM 
#### Categories:         Motor Control 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso860MAX]()

#### Expansion boards
* [FRDM-MC-LVPMSM](https://mcuxpresso.nxp.com/eb-hub/product/frdm-mc-lvpmsm)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-pmsm-one-shunt-lpc86x/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-pmsm-one-shunt-lpc86x

<!-- an-mc-bldc-lpc86x/. -->
## 37. AN14018: Sensorless Brushless DC(BLDC) Motor Control on LPC86x<a id="an-mc-bldc-lpc86x_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This project implements sensorless six-step square wave brushless DC(BLDC) motor control on NXP LPCXpresso860-MAX board. Refer README to set up demo hardware. Peripheral setup, driver description and control algorithms are described in AN14018. 

#### Families:           LPC 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        PWM, ADC 
#### Categories:         Motor Control 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso860MAX]()


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-mc-bldc-lpc86x/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-mc-bldc-lpc86x

<!-- an-mc-bldc-ke17z/. -->
## 38. Sensorless BLDC motor control on KE17Z<a id="an-mc-bldc-ke17z_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application note demonstrates how to implement the six-step commutation control of brushless direct current(BLDC) motor on KE17Z512 and KE17Z256 MCUs. The NXP Freedom board FRDM-MC-LVBLDC is used as a hardware platform for the motor control reference solution. The hardware-dependent part of the motor control software is addressed as well, including a detailed peripheral setup and driver description. The FreeMASTER operation is also described in this document.<a target="_blank"></a>

#### Families:           Kinetis 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        PWM, ADC 
#### Categories:         Motor Control 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-KE17Z](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/freedom-development-platform-for-72mhz-ke17z-ke13z-ke12z-mcus:FRDM-KE17Z)
* [FRDM-KE17Z512](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-96-mhz-ke17z-ke13z-ke12z-with-512-kb-flash-mcus:FRDM-KE17Z512)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-mc-bldc-ke17z/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-mc-bldc-ke17z

<!-- an-mcxn236-usb-bridge-to-i3c/. -->
## 39. AN14434 How to implement MCXN236 USB to I3C demo<a id="an-mcxn236-usb-bridge-to-i3c_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This is the complementary project for [AN14434](https://www.nxp.com.cn/docs/en/application-note/AN14434.pdf), which demonstrates how implement usb to i3c demo on MCXN236.<br><br>In the MCXN236 USB to I3C demo, the USB device uses USB CDC virtual com class to communicate with PC host.&nbsp;<br>You can use terminal tool to send a serial data to control I3C interface.<br>The terminal tool used in following contents is pzh-py-com tool. Customer can download it from followed link: https://github.com/JayHeng/pzh-py-com.<br>This demo provided some commands such as Dynamic address assign, direct write, direct read, write with register address, read with register address, IBI/Hot-join functions.<br>[&lt;img src="./images/MCXN236_USB_TO_I3C_Block.png" align="center" width="800"/&gt;](./images/MCXN236_USB_TO_I3C_Block.png) 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I3C, USB 
#### Categories:         HMI 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN236](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n23x-mcus:FRDM-MCXN236)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-mcxn236-usb-bridge-to-i3c/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-mcxn236-usb-bridge-to-i3c

<!-- an-frdmrw612-module-migration-guide/. -->
## 40. Migration guide from FRDM-RW612 to third-party module memories<a id="an-frdmrw612-module-migration-guide_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 The objective of this application note is to help developers migrating their applications from the RW612-FRDM board to their module-based board. <br>This application note contains: <br><ul><li>An overview of what does imply to move your application to a different board with different Flash and pSRAM.</li><li>Flash configuration files (flash_config.c) for each supported module.</li><li>Application Flash and pSRAM configurations for each supported module.</li></ul>

#### Families:           RW 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        FLASH 
#### Categories:         Memory 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-frdmrw612-module-migration-guide/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-frdmrw612-module-migration-guide

<!-- an-mc-bldc-mcxa153/. -->
## 41. Sensorless BLDC motor control on MCXA153<a id="an-mc-bldc-mcxa153_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application note demonstrates how to implement the six-step commutation control of brushless direct current(BLDC) motor on the MCXA family of MCUs. The NXP Freedom board FRDM-MC-LVBLDC is used as a hardware platform for the motor control reference solution. The hardware-dependent part of the motor control software is addressed as well, including a detailed peripheral setup and driver description. The FreeMASTER operation is also described in this document.<a target="_blank"></a>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        ADC, PWM 
#### Categories:         Motor Control 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)

#### Expansion boards
* [FRDM-MC-LVPMSM](https://mcuxpresso.nxp.com/eb-hub/product/frdm-mc-lvpmsm)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-mc-bldc-mcxa153/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-mc-bldc-mcxa153

<!-- an-lpc55s69-rtc-osc-calibration/. -->
## 42. AN14605 Using the RTC OSC Calibration Feature of the LPC5500<a id="an-lpc55s69-rtc-osc-calibration_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
This software accompanies application note AN14605, which describes how to use the RTC OSC Calibration Feature of the LPC5500.

#### Families:           LPC 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        CLOCKS 
#### Categories:         Real Time Clock 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S69](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s69-development-board:LPC55S69-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-lpc55s69-rtc-osc-calibration/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=lpc55s69-rtc-osc-calibration

<!-- an-ethernet-lwip-ptpd-imxrt/. -->
## 43. AN12149: Implementing an IEEE 1588 V2 on i.MX RT  Using PTPd, FreeRTOS, and lwIP TCP/IP  stack<a id="an-ethernet-lwip-ptpd-imxrt_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
This software accompanies application note AN12149, which describes how to implementation a 1588 V2 application based on ptpd.

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        ETHERNET 
#### Categories:         Time Sensitive Networking, Networking 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [EVKB-IMXRT1050](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1050-evaluation-kit:MIMXRT1050-EVK)
* [EVK-MIMXRT1020](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1020-evaluation-kit:MIMXRT1020-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-ethernet-lwip-ptpd-imxrt/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=ethernet-lwip-ptpd-imxrt

<!-- an-emulating-i2s-bus-with-flexio-on-mcxa156/. -->
## 44. emulating i2s bus with flexio on mcxa156<a id="an-emulating-i2s-bus-with-flexio-on-mcxa156_."></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application note describes how to emulate I2S interface with FlexIO on MCXA156 and implement a USB speaker device on MCXA156. The audio function is tested using the codec on LPCXpress55s69 board. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DMA, FlexIO, I2C, USB, I2S 
#### Categories:         Audio 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S69](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s69-development-board:LPC55S69-EVK)
* [FRDM-MCXA156](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a144-5-6-a154-5-6-mcus:FRDM-MCXA156)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/an-emulating-i2s-bus-with-flexio-on-mcxa156/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=an-emulating-i2s-bus-with-flexio-on-mcxa156


# [NXP Application Code Hub](https://mcuxpresso.nxp.com/appcodehub) - Index Of Demos
[<img src="https://mcuxpresso.nxp.com/static/icon/nxp-logo-color.svg" width="100">]([https://www.nxp.com|https://www.nxp.com/])

<a id="top"></a>

## Index
1. [BLE smart label based on LVGL using Waveshare e-ink display and KW45](#dm-lvgl-epaper-smartlabel-kw45)
2. [Instrument cluster demo on MIMXRT1170-EVK with Raspberry Pi 7" touch panel, using LVGL](#dm-lvgl_cluster_rt1170_evkb_rpi)
3. [Demo of coffee machine using voice recognition (VIT) and LVGL graphics on i.MX RT1060](#dm-lvgl-vit-rt1060)
4. [How to enable a LVGL cluster demo with i.MX RT1170-EVK.](#dm-lvgl_cluster_rt1170_evk)
5. [Leveraging deep learning to count the number of people in a room using a low-resolution 8x8 infrared array sensor](#dm-ml-ir-sensor-people-counting)
6. [LPC55S36 Low End Audio Demo](#dm-lpc55s36-low-end-audio-demo)
7. [Smart lighting LED bulb using LPC860](#dm-lpc860-smart-lighting)
8. [Full Appliance Demo](#dm-rt1170evkb-full-appliance)
9. [i.MX RT1170 + NAFE13388 drivers and demos](#dm-nafe_rt1170)
10. [Very simple serial bootloader for NXP MCU](#dm-nxp_mcu_easy_bootloader)
11. [Raw Video Playback Demo for MCX N947](#dm-mcxn947-video-playback)
12. [MCXN947 NPU vs Tensorflm Benchmark](#dm-mcxn947-npu-vs-tensorflm-benchmark)
13. [How to implement low power on MCXA153](#dm-low-power-implementation-mcxa153)
14. [Fashion MNIST Recognition on MCXN947](#dm-fashion-mnist-recognition-on-mcxn947)
15. [On device training fan anomaly detection on MCXN947](#dm-on-device-training-fan-anomaly-on-mcxn947)
16. [MCXN94x power manager training lab](#dm-mcxn947-power-manager)
17. [Label the CIFAR10 images from the camera on FRDM-MCXN947](#dm-label-cifar10-images-on-mcxn947)
18. [Heart rate (BPM) and SPO2 monitoring on FRDM-MCXA153](#dm-frdm-mcxa153-freemaster-heart-rate)
19. [How to implement USB audio 7.1 channel speaker on MCXN947](#dm-usb-audio-7-1-channel-speaker-on-mcxn947)
20. [Multiple face detection on mcxn947](#dm-multiple-face-detection-on-mcxn947)
21. [Multiple Person Detection on MCXN947](#dm-multiple-person-detection-on-mcxn947)
22. [How to develop an electric bicycle dashboard design on MCXN947](#dm-frdm-mcxn947-ebike)
23. [MCX STREAMDECK](#dm-mcx-streamdeck)
24. [Industrial Panel FRDM-MCXN947](#dm-industrial-panel-frdm-mcxn947)
25. [Magnetic Wake-up Example using NMH1000 Magnetic Switch Sensor](#dm-nmh1000-magnetic-switch-example)
26. [vital signal monitor](#dm-mcxn947-lcd-heart-rate-spo2)
27. [MCXN - how to enable the windowed watchdog on low power](#dm-mcxn-windowed-watchdog)
28. [Pressure and Altimeter Examples using MPL3115 Sensor](#dm-mpl3115-pressure-altimeter-examples)
29. [Using SmartDMA to implement camera interface in MCXN236](#dm-mcxn236-camera-interface-by-smartdma)
30. [This example demonstrates FXLS89xxxF 3-axis accelerometer evaluation GUI using ISSDK and FreeMASTER](#dm-freemaster-fxls89xxxf-evaluation-gui-firmware)
31. [This demo provides APIs to configure and read accurate temperature using P3T1085UK sensor](#dm-p3t1085uk-temperature-sensor-driver-with-demo-app)
32. [PCF2131 : Real Time Clock driver on FRDM-MCXN947.](#dm-pcf2131-real-time-clock-driver-with-demo-app)
33. [K32W148 BLDC Motor control FreeRTOS application](#dm-bldc-motor-control-k32w148)
34. [Touch Keypad Tuning on MCXN](#dm-mcxn-touch-keypad-tuning)
35. [NMH1000 magnetic switch sensor evaluation GUI using ISSDK and FreeMASTER](#dm-freemaster-nmh1000-evaluation-gui-firmware)
36. [low power measurement on mcxn236](#dm-low-power-measurement-on-mcxn236)
37. [PCA9957HN led driver with demo app running on FRDM-MCXN947 and FRDM-MCXA153](#dm-pca9957hn-led-driver-with-demo-app)
38. [Multi sensor demo with FRDM-MCXN947 and LDC-PAR-S035](#dm-mcx-accel-and-pressure-monitor)
39. [Accel and Pressure sensor demo with FRDM-MCXA153](#dm-mcxa-accel-and-pressure-logger)
40. [PCA9959HN led driver with demo app running on FRDM-MCXN947 and FRDM-MCXA153](#dm-pca9959hn-led-driver-with-demo-app)
41. [Nafe Industrial Application Examples using API Libraries](#dm-nafex388-application-examples)
42. [EVSE-SIG-BRD using LPC5536/LPC55S36 for electric vehicle chargers](#dm-lpc5536-evse-sigbrd)
43. [PCF85063AT : Tiny Real Time Clock driver on FRDM-MCXN947 and MCXA153.](#dm-pcf85063at-real-time-clock-demo-app)
44. [Tamper detection with low-power wakeup sensor using BLE wireless UART](#dm-tamper-detection-using-low-power-wakeup-sensor-over-ble)
45. [FRDM RW612 Kitchen Timer](#dm-frdm-rw612-kitchen-timer)
46. [FRDMHB2002ESEVM: Driver and demo app for MC33HB2002ES H-bridge motor controller](#dm-frdmhb2002esevm-motor-control-demo-app)
47. [SJA1124EVB : Quad LIN Commander Transceiver with LIN Commander Controller](#dm-sja1124evb-spi-to-quad-lin-bridge)
48. [FRDM33926PNBEVM: Driver and demo app for MC33926 motor controller](#dm-frdm33926pnbevm-motor-control-driver-demo-app)
49. [i.MX Driver Monitor System](#nxp-demo-experience-demos-list/dm-i-mx-dms)
50. [i.MX Smart Fitness](#nxp-demo-experience-demos-list/dm-i-mx-smart-fitness)
51. [Selfie Segmenter](#nxp-demo-experience-demos-list/dm-selfie-segmenter)
52. [i.MX Smart Kitchen](#nxp-demo-experience-demos-list/dm-i-mx-smart-kitchen)

<!-- dm-lvgl-epaper-smartlabel-kw45 -->
## 1. BLE smart label based on LVGL using Waveshare e-ink display and KW45<a id="dm-lvgl-epaper-smartlabel-kw45"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This is an example project to demonstrate the use of GUI Guider and LVGL in the context of a BLE Smart Label using NXP KW45B41Z-EVK or K32W148-EVK boards, a Waveshare 2.9" E-Ink display and NXP IoT Toolbox application. 

#### Families:           K32W 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        SPI 
#### Categories:         Graphics 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [KW45B41Z-EVK]()
* [K32W148-EVK](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/k32w148-evaluation-kit-with-multiprotocol-radio:K32W148-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-lvgl-epaper-smartlabel-kw45/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lvgl-epaper-smartlabel-kw45

<!-- dm-lvgl_cluster_rt1170_evkb_rpi -->
## 2. Instrument cluster demo on MIMXRT1170-EVK with Raspberry Pi 7" touch panel, using LVGL<a id="dm-lvgl_cluster_rt1170_evkb_rpi"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Cluster demo with LVGL on Raspberry Pi 7" touch panel. 

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY 
#### Categories:         Graphics 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MIMXRT1170-EVKB](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1170-evaluation-kit:MIMXRT1170-EVKB)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-lvgl_cluster_rt1170_evkb_rpi/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lvgl_cluster_rt1170_evkb_rpi

<!-- dm-lvgl-vit-rt1060 -->
## 3. Demo of coffee machine using voice recognition (VIT) and LVGL graphics on i.MX RT1060<a id="dm-lvgl-vit-rt1060"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This application code is to demonstrate LVGL Coffee Machine GUI + NXP VIT on RT1060-EVK for smart panel demo 

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY, I2C, I2S 
#### Categories:         Graphics, Voice, HMI, RTOS 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [EVK-MIMXRT1060](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1060-evaluation-kit:MIMXRT1060-EVKB)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-lvgl-vit-rt1060/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lvgl-vit-rt1060

<!-- dm-lvgl_cluster_rt1170_evk -->
## 4. How to enable a LVGL cluster demo with i.MX RT1170-EVK.<a id="dm-lvgl_cluster_rt1170_evk"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This is a cluster demo with LVGL on MIMXRT1170-EVK with RK055HDMIPI4M 5.5" LCD panel. This demo shows the interface of the car/e-bike when driving, shows the interface of speedometer gear switching and signal icons switching. 

#### Families:           i.MX RT 
#### Toolchains:         IAR 
#### Peripherals:        DISPLAY 
#### Categories:         Graphics, RTOS 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MIMXRT1170-EVK]()

#### Expansion boards
* [RK055HDMIPI4MA0](https://mcuxpresso.nxp.com/eb-hub/product/rk055hdmipi4ma0)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-lvgl_cluster_rt1170_evk/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lvgl_cluster_rt1170_evk

<!-- dm-ml-ir-sensor-people-counting -->
## 5. Leveraging deep learning to count the number of people in a room using a low-resolution 8x8 infrared array sensor<a id="dm-ml-ir-sensor-people-counting"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This shows how to create a deep learning model to count the number of people in a room using a low-resolution 8x8 infrared array sensor. 

#### Families:           LPC 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, SENSOR, UART, TIMER, CLOCKS 
#### Categories:         AI/ML, Vision 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S69](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s69-development-board:LPC55S69-EVK)
* [LPCXpresso55S28](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s28-development-board:LPC55S28-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-ml-ir-sensor-people-counting/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-ml-ir-sensor-people-counting

<!-- dm-lpc55s36-low-end-audio-demo -->
## 6. LPC55S36 Low End Audio Demo<a id="dm-lpc55s36-low-end-audio-demo"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This example demo uses DAC output to generate low end audio through an external speaker. 

#### Families:           LPC 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DAC, UART, USB 
#### Categories:         Voice, Audio 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S36](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s36-development-board:LPCXpresso55S36)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-lpc55s36-low-end-audio-demo/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lpc55s36-low-end-audio-demo

<!-- dm-lpc860-smart-lighting -->
## 7. Smart lighting LED bulb using LPC860<a id="dm-lpc860-smart-lighting"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This is the source code for using LPC860 as an IEC-62386 compatible smart RGB light bulb, and is the default firmware for the smart lighting control gear board. 

#### Families:           LPC 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        ADC, TIMER, PWM, DMA 
#### Categories:         HMI 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-lpc860-smart-lighting/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lpc860-smart-lighting

<!-- dm-rt1170evkb-full-appliance -->
## 8. Full Appliance Demo<a id="dm-rt1170evkb-full-appliance"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This is a Full Appliance Demo with LVGL on MIMXRT1170-EVKB with RK055HDMIPI4M 5.5" LCD panel. This Demo shows three appliances, an Oven, an Aircon and a Hood (each appliance has its own animations and can switch bettwen screens), it also has a central dashboard with the status of all appliances. 

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY 
#### Categories:         Graphics, HMI, RTOS 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MIMXRT1170-EVKB](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1170-evaluation-kit:MIMXRT1170-EVKB)

#### Expansion boards
* [RK055HDMIPI4MA0](https://mcuxpresso.nxp.com/eb-hub/product/rk055hdmipi4ma0)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-rt1170evkb-full-appliance/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-rt1170evkb-full-appliance

<!-- dm-nafe_rt1170 -->
## 9. i.MX RT1170 + NAFE13388 drivers and demos<a id="dm-nafe_rt1170"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This example demonstrates how to use NAFE13388 and i.MXRT1170 to sample analog signals. The results are either shown in a serial terminal window or in waveforms by using the FreeMASTER Run-Time Debugging Tool. 

#### Families:           i.MX RT 
#### Toolchains:         IAR, MCUXpresso IDE, VS Code 
#### Peripherals:        DMA, GPIO, SPI, UART 
#### Categories:         Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MIMXRT1170-EVK]()


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-nafe_rt1170/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-nafe_rt1170

<!-- dm-nxp_mcu_easy_bootloader -->
## 10. Very simple serial bootloader for NXP MCU<a id="dm-nxp_mcu_easy_bootloader"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Simplified version of XP official MCUBOOT, implemented in C, removing most of the features and only retaining serial download functionality. 

#### Families:           Kinetis, LPC 
#### Toolchains:         MDK 
#### Peripherals:        FLASH 
#### Categories:         Tools 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-nxp_mcu_easy_bootloader/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-nxp_mcu_easy_bootloader

<!-- dm-mcxn947-video-playback -->
## 11. Raw Video Playback Demo for MCX N947<a id="dm-mcxn947-video-playback"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo plays raw video file from SD card file system directly to LCD panel, in order to achieve high frame rate on performance constrained MCUs. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        SDMMC, DISPLAY 
#### Categories:         Graphics, SDMMC 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcxn947-video-playback/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxn947-video-playback

<!-- dm-mcxn947-npu-vs-tensorflm-benchmark -->
## 12. MCXN947 NPU vs Tensorflm Benchmark<a id="dm-mcxn947-npu-vs-tensorflm-benchmark"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo shows the performance benchmark between NPU and TensorFLM. Real time results are displayed on TFT LCD. On-chip NPU accelerates AI/ML algorithms and improves the performance. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY 
#### Categories:         Graphics, AI/ML 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [TFT PROTO 5 Capacitive](https://mcuxpresso.nxp.com/eb-hub/product/tft proto 5 capacitive)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcxn947-npu-vs-tensorflm-benchmark/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxn947-npu-vs-tensorflm-benchmark

<!-- dm-low-power-implementation-mcxa153 -->
## 13. How to implement low power on MCXA153<a id="dm-low-power-implementation-mcxa153"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 The low power implementation demo is used for power mode switch, wake up time measurement and low power current measurement on the FRDM-MCXA153 board. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        CLOCKS, UART 
#### Categories:         Low Power, Power Conversion 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-low-power-implementation-mcxa153/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-low-power-implementation-mcxa153

<!-- dm-fashion-mnist-recognition-on-mcxn947 -->
## 14. Fashion MNIST Recognition on MCXN947<a id="dm-fashion-mnist-recognition-on-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Fashion-MNIST recognition based on machine learning algorithm, power by MCXN947.Model is trained on Fashion-MNIST dataset, which can recognition 10 classes of fashion product from camera.Machine learning algorithm is accelerated by the NPU inside, the inference during is smaller than 10ms.<br><br>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        DISPLAY 
#### Categories:         HMI, AI/ML 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-fashion-mnist-recognition-on-mcxn947/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-fashion-mnist-recognition-on-mcxn947

<!-- dm-on-device-training-fan-anomaly-on-mcxn947 -->
## 15. On device training fan anomaly detection on MCXN947<a id="dm-on-device-training-fan-anomaly-on-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 On device trainable anomaly detection based on MCXN947. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        DISPLAY, I2C 
#### Categories:         Graphics, Anomaly Detection, AI/ML 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)
* [ACCEL 4 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/accel 4 click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-on-device-training-fan-anomaly-on-mcxn947/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-on-device-training-fan-anomaly-on-mcxn947

<!-- dm-mcxn947-power-manager -->
## 16. MCXN94x power manager training lab<a id="dm-mcxn947-power-manager"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 The Power Manager example uses runtime menus to evaluate the power modes and power management features of the MCX Nx4x.  This example also uses the Power Manager component of MCUXpresso SDK, which provides a common framework of APIs for power management. For more details how to use this example and measure current, refer to the lab guide "MCXNx4x Power Management Lab.pdf". 

#### Families:           MCX 
#### Toolchains:         IAR, MCUXpresso IDE, VS Code 
#### Peripherals:        CLOCKS 
#### Categories:         Low Power 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MCX-N9XX-EVK](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/evaluation-kit-for-mcx-n94x-mcus:MCX-N9XX-EVK)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcxn947-power-manager/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxn947-power-manager

<!-- dm-label-cifar10-images-on-mcxn947 -->
## 17. Label the CIFAR10 images from the camera on FRDM-MCXN947<a id="dm-label-cifar10-images-on-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Label the CIFAR10 images from the camera on FRDM-MCXN947 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        DISPLAY 
#### Categories:         HMI, AI/ML 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-label-cifar10-images-on-mcxn947/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-label-cifar10-images-on-mcxn947

<!-- dm-frdm-mcxa153-freemaster-heart-rate -->
## 18. Heart rate (BPM) and SPO2 monitoring on FRDM-MCXA153<a id="dm-frdm-mcxa153-freemaster-heart-rate"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo mainly demonstrates how to use FRDM-MCXA153 to collect ecg, heart rate and blood oxygen saturation data, also uses FreeMASTER as the UI for display. The MCU (MCXA153) adjusts intensity of LED's in sensor for reads better values of light intensity data from MAX30101 via the I2C bus, performs filtering, other signal processing operations and algorithms to obtain the final result (ecg ,heart rate and SPO2 with waveforms), and saves it in the on-chip RAM. The on-board debugger of FRDM-MCXA153 reads the ecg, heart rate and blood oxygen data from the MCU via the SWD, and displays the results on the FreeMASTER web page. The UI of FreeMASTER uses JS script for web-based waveform display. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C 
#### Categories:         Sensor 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)

#### Expansion boards
* [HEART RATE 4 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/heart rate 4 click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-frdm-mcxa153-freemaster-heart-rate/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-frdm-mcxa153-freemaster-heart-rate

<!-- dm-usb-audio-7-1-channel-speaker-on-mcxn947 -->
## 19. How to implement USB audio 7.1 channel speaker on MCXN947<a id="dm-usb-audio-7-1-channel-speaker-on-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo will show you how to implement a USB audio 7.1 channel speaker on MCXN947 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        SAI, USB 
#### Categories:         Audio 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [AUD-EXP-42448](https://mcuxpresso.nxp.com/eb-hub/product/aud-exp-42448)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-usb-audio-7-1-channel-speaker-on-mcxn947/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-usb-audio-7-1-channel-speaker-on-mcxn947

<!-- dm-multiple-face-detection-on-mcxn947 -->
## 20. Multiple face detection on mcxn947<a id="dm-multiple-face-detection-on-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Multiple face detection on FRDM-MCXN947 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        DISPLAY, PWM 
#### Categories:         AI/ML 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-multiple-face-detection-on-mcxn947/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-multiple-face-detection-on-mcxn947

<!-- dm-multiple-person-detection-on-mcxn947 -->
## 21. Multiple Person Detection on MCXN947<a id="dm-multiple-person-detection-on-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Multiple person detection based on machine learning algorithms, powered by MCXN947. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        DISPLAY 
#### Categories:         AI/ML 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-multiple-person-detection-on-mcxn947/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-multiple-person-detection-on-mcxn947

<!-- dm-frdm-mcxn947-ebike -->
## 22. How to develop an electric bicycle dashboard design on MCXN947<a id="dm-frdm-mcxn947-ebike"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo is an example of dashboard for electric bicycle. This demo is based on LVGL 8.3.10 and GUI Guider 1.6.0-GA. This demo can be used by customers to evaluate GUI performance of MCXN947. Here, this demo uses MCXN947 as target MCU and uses internal flash to store image source and font source. This demo supports various GUI widgets to show customer information such as meter panel, chart, label. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY 
#### Categories:         HMI 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-frdm-mcxn947-ebike/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-frdm-mcxn947-ebike

<!-- dm-mcx-streamdeck -->
## 23. MCX STREAMDECK<a id="dm-mcx-streamdeck"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 A touch user interface to send hotkeys or shorcuts 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        USB, DISPLAY 
#### Categories:         Graphics, HMI 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [TFT PROTO 5 Capacitive](https://mcuxpresso.nxp.com/eb-hub/product/tft proto 5 capacitive)
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcx-streamdeck/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcx-streamdeck

<!-- dm-industrial-panel-frdm-mcxn947 -->
## 24. Industrial Panel FRDM-MCXN947<a id="dm-industrial-panel-frdm-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo demostrate capabilities of new FRDM-MCXN947. With only one core, the demo run motor control, lvgl, server, two temperature sensors, touch sensitive and get core performance.<br>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        ADC, PWM, UART, TIMER, I2C, ETHERNET 
#### Categories:         Graphics, Sensor, Motor Control, Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [FRDM-MC-LVPMSM](https://mcuxpresso.nxp.com/eb-hub/product/frdm-mc-lvpmsm)
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-industrial-panel-frdm-mcxn947/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-industrial-panel-frdm-mcxn947

<!-- dm-nmh1000-magnetic-switch-example -->
## 25. Magnetic Wake-up Example using NMH1000 Magnetic Switch Sensor<a id="dm-nmh1000-magnetic-switch-example"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This example demo describes how to configure NMH1000 magnetic switch sensor to enable magnetic wake-up use-case. Such use-case can find many applications where user would like to completely shut off power supply or put the device in power down mode etc. based on magnetic field applied. Examples include, smart meters, shelf labels, reed switch replacement, smart home etc.<br>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, SENSOR, UART 
#### Categories:         Low Power, Sensor 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [FRDM-STBI-NMH1000](https://mcuxpresso.nxp.com/eb-hub/product/frdm-stbi-nmh1000)
* [HALL SWITCH 3 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/hall switch 3 click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-nmh1000-magnetic-switch-example/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-nmh1000-magnetic-switch-example

<!-- dm-mcxn947-lcd-heart-rate-spo2 -->
## 26. vital signal monitor<a id="dm-mcxn947-lcd-heart-rate-spo2"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 The project is vital sign monitor that use a pulse-oximeter sensor to obtain the values and uses an LCD to show the values and the graphics of the measurements. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY, DMA, I2C 
#### Categories:         Graphics, Sensor, HMI 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)
* [HEART RATE 4 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/heart rate 4 click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcxn947-lcd-heart-rate-spo2/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxn947-lcd-heart-rate-spo2

<!-- dm-mcxn-windowed-watchdog -->
## 27. MCXN - how to enable the windowed watchdog on low power<a id="dm-mcxn-windowed-watchdog"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Create package software about how to enable watchdog in low power examples. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        WATCHDOG 
#### Categories:         Low Power 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcxn-windowed-watchdog/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxn-windowed-watchdog

<!-- dm-mpl3115-pressure-altimeter-examples -->
## 28. Pressure and Altimeter Examples using MPL3115 Sensor<a id="dm-mpl3115-pressure-altimeter-examples"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This example demo describes how to configure absolute pressure sensor MPL3115 for pressure and altimeter mode. This sensor can find use in many industrial, medical applications. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, UART 
#### Categories:         Low Power, Sensor 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [FRDMSTBC-P3115](https://mcuxpresso.nxp.com/eb-hub/product/frdmstbc-p3115)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mpl3115-pressure-altimeter-examples/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mpl3115-pressure-altimeter-examples

<!-- dm-mcxn236-camera-interface-by-smartdma -->
## 29. Using SmartDMA to implement camera interface in MCXN236<a id="dm-mcxn236-camera-interface-by-smartdma"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo introduces a parallel interface for the camera solution for MCXN236 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        GPIO, VIDEO 
#### Categories:         Graphics, HMI 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN236](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n23x-mcus:FRDM-MCXN236)

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcxn236-camera-interface-by-smartdma/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxn236-camera-interface-by-smartdma

<!-- dm-freemaster-fxls89xxxf-evaluation-gui-firmware -->
## 30. This example demonstrates FXLS89xxxF 3-axis accelerometer evaluation GUI using ISSDK and FreeMASTER<a id="dm-freemaster-fxls89xxxf-evaluation-gui-firmware"></a> <a href="#top" style="float:right">⤒</a>

### Overview
<ul><li>This example demonstrates combining ISSDK and FreeMASTER to create FXLS89xxxF 3-axis accelerometer evaluation GUI for our customer to evaluate this sensor using sensor development tools with sensors expansion boards.</li><li>NXP’s next-generation accelerometer feature a strong balance of intelligent integration, logic and customizable platform software to enable smarter, more differentiated applications<br></li><li>This example demonstrates how we can combine multiple middleware(s)  (e.g. ISSDK, FreeMASTER) to develop evaluation tools that helps improve "ease of evaluation and development" for our customers using our parts.</li></ul>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, SENSOR, UART 
#### Categories:         Sensor, Tools 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [FRDM-STBI-A8974](https://mcuxpresso.nxp.com/eb-hub/product/frdm-stbi-a8974)
* [ACCEL 4 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/accel 4 click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-freemaster-fxls89xxxf-evaluation-gui-firmware/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-freemaster-fxls89xxxf-evaluation-gui-firmware

<!-- dm-p3t1085uk-temperature-sensor-driver-with-demo-app -->
## 31. This demo provides APIs to configure and read accurate temperature using P3T1085UK sensor<a id="dm-p3t1085uk-temperature-sensor-driver-with-demo-app"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This example demo describes how to configure the accurate temperature sensor P3T1085UK for temperature measurement. This sensor can be used in many industrial and medical applications. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C 
#### Categories:         Sensor 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [P3T1085UK-ARD](https://mcuxpresso.nxp.com/eb-hub/product/p3t1085uk-ard)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-p3t1085uk-temperature-sensor-driver-with-demo-app/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-p3t1085uk-temperature-sensor-driver-with-demo-app

<!-- dm-pcf2131-real-time-clock-driver-with-demo-app -->
## 32. PCF2131 : Real Time Clock driver on FRDM-MCXN947.<a id="dm-pcf2131-real-time-clock-driver-with-demo-app"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This example demo provides CMSIS Compliant APIs to configure different operating modes of PCF2131 RTC. It also provides APIs to perform below mentioned operations:<br><ul><li>RTC Start</li><li>RTC Stop</li><li>Get Time</li><li>Set Time</li><li>Record Timestamps on Switches</li><li>Software Reset </li></ul>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        SPI, I2C 
#### Categories:         Real Time Clock 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [PCF2131-ARD](https://mcuxpresso.nxp.com/eb-hub/product/pcf2131-ard)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-pcf2131-real-time-clock-driver-with-demo-app/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-pcf2131-real-time-clock-driver-with-demo-app

<!-- dm-bldc-motor-control-k32w148 -->
## 33. K32W148 BLDC Motor control FreeRTOS application<a id="dm-bldc-motor-control-k32w148"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This software shows how to control a Brushless DC (BLDC) Motor with K32W148. 

#### Families:           K32W, KW45 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        ADC, GPIO, PWM 
#### Categories:         Motor Control, RTOS 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [KW45B41Z-EVK]()
* [K32W148-EVK](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/k32w148-evaluation-kit-with-multiprotocol-radio:K32W148-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-bldc-motor-control-k32w148/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-bldc-motor-control-k32w148

<!-- dm-mcxn-touch-keypad-tuning -->
## 34. Touch Keypad Tuning on MCXN<a id="dm-mcxn-touch-keypad-tuning"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 The demo shows how to use NXP Touch sensing library with the python tool for Capacitive Touch keypad sensitivity tuning 

#### Families:           Kinetis, MCX 
#### Toolchains:         IAR 
#### Peripherals:        TSI 
#### Categories:         Touch Sensing, HMI 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcxn-touch-keypad-tuning/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxn-touch-keypad-tuning

<!-- dm-freemaster-nmh1000-evaluation-gui-firmware -->
## 35. NMH1000 magnetic switch sensor evaluation GUI using ISSDK and FreeMASTER<a id="dm-freemaster-nmh1000-evaluation-gui-firmware"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This example demonstrates combining ISSDK and FreeMASTER to create NMH1000 magnetic switch evaluation GUI for our customer to evaluate this sensor using sensor development tools with sensor expansion boards.<br>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, UART 
#### Categories:         Low Power, Sensor 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [HALL SWITCH 3 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/hall switch 3 click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-freemaster-nmh1000-evaluation-gui-firmware/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-freemaster-nmh1000-evaluation-gui-firmware

<!-- dm-low-power-measurement-on-mcxn236 -->
## 36. low power measurement on mcxn236<a id="dm-low-power-measurement-on-mcxn236"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 The low power measurement demo is used to reproduce the power consumption and wake-up time in the datasheet on the FRDM-MCXN236 board. 

#### Families:           MCX 
#### Toolchains:         IAR 
#### Peripherals:        CLOCKS, UART 
#### Categories:         Low Power 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN236](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n23x-mcus:FRDM-MCXN236)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-low-power-measurement-on-mcxn236/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-low-power-measurement-on-mcxn236

<!-- dm-pca9957hn-led-driver-with-demo-app -->
## 37. PCA9957HN led driver with demo app running on FRDM-MCXN947 and FRDM-MCXA153<a id="dm-pca9957hn-led-driver-with-demo-app"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 A graphical interface allows the user to easily explore the different functions of the driver to use the LED controller features for color mixing, blinking and dimming LEDs. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        SPI 
#### Categories:         User Interface 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-pca9957hn-led-driver-with-demo-app/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-pca9957hn-led-driver-with-demo-app

<!-- dm-mcx-accel-and-pressure-monitor -->
## 38. Multi sensor demo with FRDM-MCXN947 and LDC-PAR-S035<a id="dm-mcx-accel-and-pressure-monitor"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo shows how to integrate the NXP sensors FXLS8974CF (3-axis accelerometer) and MPL3115 (absolute pressure) with FRDM-MCXN947 platform. Both sensors share the I2C bus of the Accel &amp; Pressure click board, that is used in the demo for digital communication between the MCXN947 and the sensors. The demo uses the LVGL graphics framework and a TFT Display (LCD-PAR-S035) to show sensor data 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY, GPIO, I2C, SENSOR, UART 
#### Categories:         Sensor 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)
* [ACCEL PRESSURE CLICK](https://mcuxpresso.nxp.com/eb-hub/product/accel pressure click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcx-accel-and-pressure-monitor/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcx-accel-and-pressure-monitor

<!-- dm-mcxa-accel-and-pressure-logger -->
## 39. Accel and Pressure sensor demo with FRDM-MCXA153<a id="dm-mcxa-accel-and-pressure-logger"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 The demo implements the ISSDK FXLS8974 &amp; MPL3115 sensor driver example demonstration with RGB LED status on FRDM-MCXA153 using Accel &amp; Pressure Click. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, UART, SENSOR, GPIO, TIMER 
#### Categories:         Sensor 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)

#### Expansion boards
* [ACCEL PRESSURE CLICK](https://mcuxpresso.nxp.com/eb-hub/product/accel pressure click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcxa-accel-and-pressure-logger/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxa-accel-and-pressure-logger

<!-- dm-pca9959hn-led-driver-with-demo-app -->
## 40. PCA9959HN led driver with demo app running on FRDM-MCXN947 and FRDM-MCXA153<a id="dm-pca9959hn-led-driver-with-demo-app"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo application provides a command line interface which allows the user to easily explore the different functions <br> of the driver to use the LED controller features for grid duration control , grid-group configuration, channel configuration and gradation control<br>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        SPI 
#### Categories:         User Interface 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [PCA9959HN-ARD](https://mcuxpresso.nxp.com/eb-hub/product/pca9959hn-ard)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-pca9959hn-led-driver-with-demo-app/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-pca9959hn-led-driver-with-demo-app

<!-- dm-nafex388-application-examples -->
## 41. Nafe Industrial Application Examples using API Libraries<a id="dm-nafex388-application-examples"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This is a collection of MCUXpresso projects, in this collection several fundamental voltage/current/sensor readout applications via NXP analog front-end are exposed. 

#### Families:           LPC 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        GPIO, SPI, TIMER, UART, SENSOR, DMA 
#### Categories:         Sensor, Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso54628](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso54628-development-board:OM13098)
* [LPCXpresso54S018](https://www.nxp.com/products/processors-and-microcontrollers/arm-microcontrollers/general-purpose-mcus/lpc54000-arm-cortex-m4-/lpcxpresso54s018-development-board:LPC54S018-EVK)

#### Expansion boards
* [NAFExx388-EVB](https://mcuxpresso.nxp.com/eb-hub/product/nafexx388-evb)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-nafex388-application-examples/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-nafex388-application-examples

<!-- dm-lpc5536-evse-sigbrd -->
## 42. EVSE-SIG-BRD using LPC5536/LPC55S36 for electric vehicle chargers<a id="dm-lpc5536-evse-sigbrd"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 The EVSE-SIG-BRD is an add-on development board that supports electric vehicle supply equipment (EVSE) platform development. The board also supports the proximity pilot, ground fault circuit interrupter (GFCI), and relay drive features. The main host of the system is on a separate processor development board, for example, NXP i.MX RT1060 EVK, i.MX 8M Nano EVK, or S32G-VNP-RDB3. The ISO 15118 protocol stack and communication software run on the host processor.  The power-line communication(PLC) path is via the onboard HomePlug Green PHY (HPGP) transceiver (Lumissil IS32CG5317). 

#### Families:           LPC 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        UART, TIMER, SPI, PWM, I2C, GPIO, FLASH, CLOCKS, ADC, CAN, ETHERNET 
#### Categories:         Low Power, Industrial, Security, Safety 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-lpc5536-evse-sigbrd/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lpc5536-evse-sigbrd

<!-- dm-pcf85063at-real-time-clock-demo-app -->
## 43. PCF85063AT : Tiny Real Time Clock driver on FRDM-MCXN947 and MCXA153.<a id="dm-pcf85063at-real-time-clock-demo-app"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This example demo provides CMSIS Compliant APIs to configure different operating modes of PCF85063AT RTC. It also provides APIs to perform below mentioned operations:<br><ul><li>RTC Start</li><li>RTC Stop</li><li>Get/Set Time and date </li><li>Minute/Half Minute Interrupt</li><li>Offset Modes </li><li>Correction Interrupts </li><li>Get &amp; Set Alarm  etc. </li></ul>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C 
#### Categories:         Real Time Clock 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [PCF85063AT](https://mcuxpresso.nxp.com/eb-hub/product/pcf85063at)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-pcf85063at-real-time-clock-demo-app/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-pcf85063at-real-time-clock-demo-app

<!-- dm-tamper-detection-using-low-power-wakeup-sensor-over-ble -->
## 44. Tamper detection with low-power wakeup sensor using BLE wireless UART<a id="dm-tamper-detection-using-low-power-wakeup-sensor-over-ble"></a> <a href="#top" style="float:right">⤒</a>

### Overview
<ul><li>This example demo describes how to configure low-power motion or magnetic wake-up sensor for tamper/theft detection and transmit ALERT to connected end user via BLE wireless UART using FRDM-MCXW71.</li><li>Such use-case can find many applications where user would like to completely shut off power supply or put the device in power down mode etc. based on magnetic field applied. Examples include, smart meters, shelf labels, reed switch replacement, smart home etc.<br></li></ul>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, UART 
#### Categories:         Low Power, Sensor, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXW7X]()
* [FRDM-MCXW71](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-w71x-wireless-mcus:FRDM-MCXW71)

#### Expansion boards
* [HALL SWITCH 3 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/hall switch 3 click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-tamper-detection-using-low-power-wakeup-sensor-over-ble/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-tamper-detection-using-low-power-wakeup-sensor-over-ble

<!-- dm-frdm-rw612-kitchen-timer -->
## 45. FRDM RW612 Kitchen Timer<a id="dm-frdm-rw612-kitchen-timer"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo shows a kitchen timer that has a config screen to set the timer, date and color 

#### Families:           RW 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY 
#### Categories:         Graphics, HMI, RTOS 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-frdm-rw612-kitchen-timer/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-frdm-rw612-kitchen-timer

<!-- dm-frdmhb2002esevm-motor-control-demo-app -->
## 46. FRDMHB2002ESEVM: Driver and demo app for MC33HB2002ES H-bridge motor controller<a id="dm-frdmhb2002esevm-motor-control-demo-app"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo application provides various Motor Control interfaces like fault detection (over, under voltage and active current limits etc ) , Fault detection control and Motor can be either control by PWM or SPI.  Using PWM speed can be controlled by changing the duty cycles. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        ADC, GPIO, PWM, SPI 
#### Categories:         Motor Control 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [FRDM-HB2002ESEVM](https://mcuxpresso.nxp.com/eb-hub/product/frdm-hb2002esevm)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-frdmhb2002esevm-motor-control-demo-app/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-frdmhb2002esevm-motor-control-demo-app

<!-- dm-sja1124evb-spi-to-quad-lin-bridge -->
## 47. SJA1124EVB : Quad LIN Commander Transceiver with LIN Commander Controller<a id="dm-sja1124evb-spi-to-quad-lin-bridge"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This example provides CMSIS Compliant APIs to configure different device configurations of SJA1124. It also provides the APIS lmentioned below :<br><ol><li>LIN traffic send/receive in between commander and responder</li><li>Low power mode support </li><li>Device configuration support</li></ol>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        SPI 
#### Categories:         Bridge 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [SJA1124EVB](https://mcuxpresso.nxp.com/eb-hub/product/sja1124evb)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-sja1124evb-spi-to-quad-lin-bridge/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-sja1124evb-spi-to-quad-lin-bridge

<!-- dm-frdm33926pnbevm-motor-control-driver-demo-app -->
## 48. FRDM33926PNBEVM: Driver and demo app for MC33926 motor controller<a id="dm-frdm33926pnbevm-motor-control-driver-demo-app"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 The 33926 is a SMARTMOS monolithic H-bridge power IC designed primarily for automotive electronic throttle control, but is applicable to any low-voltage DC servo motor control application within the current and voltage limits stated in this specification. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        ADC, GPIO, PWM 
#### Categories:         Motor Control 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [FRDM33926PNBEVM](https://mcuxpresso.nxp.com/eb-hub/product/frdm33926pnbevm)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-frdm33926pnbevm-motor-control-driver-demo-app/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-frdm33926pnbevm-motor-control-driver-demo-app

<!-- nxp-demo-experience-demos-list/dm-i-mx-dms -->
## 49. i.MX Driver Monitor System<a id="nxp-demo-experience-demos-list/dm-i-mx-dms"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 i.MX Driver Monitor System is a vehicle safety system to assess the driver's alertness and warn the driver if needed using a camera and NPU. 

#### Families:           i.MX 
#### Toolchains:         VS Code 
#### Peripherals:        DISPLAY, MIPI-CSI, USB, VIDEO 
#### Categories:         AI/ML, Vision 
#### Application format: Python (Linux)
#### Compatible boards:
* [EVK-MIMX8MP](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-plus-applications-processor:8MPLUSLPD4-EVK)
* [MCIMX93-EVK]()


#### **Repository URL:** https://github.com/nxp-imx-support/nxp-demo-experience-demos-list/tree/lf-6.6.36_2.1.0/scripts/machine_learning/dms
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-i-mx-dms

<!-- nxp-demo-experience-demos-list/dm-i-mx-smart-fitness -->
## 50. i.MX Smart Fitness<a id="nxp-demo-experience-demos-list/dm-i-mx-smart-fitness"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 i.MX Smart Fitness tracks the 'squats' fitness exercise using a camera and NPU on i.MX Applications Processors. 

#### Families:           i.MX 
#### Toolchains:         VS Code 
#### Peripherals:        MIPI-CSI, DISPLAY, USB, VIDEO 
#### Categories:         AI/ML, Vision 
#### Application format: Python (Linux)
#### Compatible boards:
* [EVK-MIMX8MP](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-plus-applications-processor:8MPLUSLPD4-EVK)
* [MCIMX93-EVK]()


#### **Repository URL:** https://github.com/nxp-imx-support/nxp-demo-experience-demos-list/tree/lf-6.6.36_2.1.0/scripts/machine_learning/imx_smart_fitness
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-i-mx-smart-fitness

<!-- nxp-demo-experience-demos-list/dm-selfie-segmenter -->
## 51. Selfie Segmenter<a id="nxp-demo-experience-demos-list/dm-selfie-segmenter"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Selfie Segmenter lets you segment the portrait of a person and can be used to replace or modify the background of an image  using a camera and the NPU. 

#### Families:           i.MX 
#### Toolchains:         VS Code 
#### Peripherals:        MIPI-CSI, DISPLAY, USB, VIDEO 
#### Categories:         AI/ML, Vision 
#### Application format: Python (Linux)
#### Compatible boards:
* [EVK-MIMX8MP](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-plus-applications-processor:8MPLUSLPD4-EVK)
* [MCIMX93-EVK]()


#### **Repository URL:** https://github.com/nxp-imx-support/nxp-demo-experience-demos-list/tree/lf-6.6.36_2.1.0/scripts/machine_learning/selfie_segmenter
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-selfie-segmenter

<!-- nxp-demo-experience-demos-list/dm-i-mx-smart-kitchen -->
## 52. i.MX Smart Kitchen<a id="nxp-demo-experience-demos-list/dm-i-mx-smart-kitchen"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 i.MX Smart Kitchen emulates an interactive kitchen through a GUI controlled by voice commands. 

#### Families:           i.MX 
#### Toolchains:         VS Code 
#### Peripherals:        DISPLAY 
#### Categories:         Graphics, Voice, HMI, User Interface 
#### Application format: Yocto Project
#### Compatible boards:
* [EVK-MIMX8MM](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-mini-applications-processor:8MMINILPD4-EVK)
* [EVK-MIMX8MP](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-plus-applications-processor:8MPLUSLPD4-EVK)
* [MCIMX93-EVK]()


#### **Repository URL:** https://github.com/nxp-imx-support/nxp-demo-experience-demos-list/tree/lf-6.6.36_2.1.0/scripts/multimedia/smart_kitchen
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-i-mx-smart-kitchen


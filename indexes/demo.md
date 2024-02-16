# [NXP Application Code Hub](https://mcuxpresso.nxp.com/appcodehub) - Index Of Demos
[<img src="https://mcuxpresso.nxp.com/static/icon/nxp-logo-color.svg" width="100">]([https://www.nxp.com|https://www.nxp.com/])

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
10. [Raw Video Playback Demo for MCX N947](#dm-mcxn947-video-playback)
11. [MCXN94x power manager training lab](#dm-mcxn947-power-manager)
12. [On device training fan anomaly detection on MCXN947](#dm-on-device-training-fan-anomaly-on-mcxn947)
13. [Magnetic Wake-up Example using NMH1000 Magnetic Switch Sensor](#dm-nmh1000-magnetic-switch-example)
14. [MCXN - how to enable the windowed watchdog on low power](#dm-mcxn-windowed-watchdog)
15. [Label the CIFAR10 images from the camera on FRDM-MCXN947](#dm-label-cifar10-images-on-mcxn947)
16. [MCXN947 NPU vs Tensorflm Benchmark](#dm-mcxn947-npu-vs-tensorflm-benchmark)
17. [How to implement USB audio 7.1 channel speaker on MCXN947](#dm-usb-audio-7-1-channel-speaker-on-mcxn947)
18. [How to develop an electric bicycle dashboard design on MCXN947](#dm-frdm-mcxn947-ebike)
19. [Fashion MNIST Recognition on MCXN947](#dm-fashion-mnist-recognition-on-mcxn947)
20. [Multiple face detection on mcxn947](#dm-multiple-face-detection-on-mcxn947)
21. [How to implement low power on MCXA153](#dm-low-power-implementation-mcxa153)
22. [Multiple Person Detection on MCXN947](#dm-multiple-person-detection-on-mcxn947)
23. [Heart rate (BPM) and SPO2 monitoring on FRDM-MCXA153](#dm-frdm-mcxa153-freemaster-heart-rate)
24. [Industrial Panel FRDM-MCXN947](#dm-industrial-panel-frdm-mcxn947)
25. [MCX STREAMDECK](#dm-mcx-streamdeck)
26. [vital signal monitor](#dm-mcxn947-lcd-heart-rate-spo2)

<!-- dm-lvgl-epaper-smartlabel-kw45 -->
## 1. BLE smart label based on LVGL using Waveshare e-ink display and KW45<a name="dm-lvgl-epaper-smartlabel-kw45"></a>
### Overview
 This is an example project to demonstrate the use of GUI Guider and LVGL in the context of a BLE Smart Label using NXP KW45B41Z-EVK or K32W148-EVK boards, a Waveshare 2.9" E-Ink display and NXP IoT Toolbox application. 

#### Families:           K32W 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        SPI 
#### Categories:         Graphics 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [KW45B41Z-EVK](https://www.nxp.com/docs/en/supporting-information/AH1301_Application_Hints_TJA1052i.pdf)
* [K32W148-EVK](https://www.nxp.com/design/software/development-software/mcuxpresso-software-and-tools-/k32w148-evaluation-kit-with-multiprotocol-radio:K32W148-EVK)


#### **Repository URL:** https://github.com/nxp-appcodehub/dm-lvgl-epaper-smartlabel-kw45
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lvgl-epaper-smartlabel-kw45

<!-- dm-lvgl_cluster_rt1170_evkb_rpi -->
## 2. Instrument cluster demo on MIMXRT1170-EVK with Raspberry Pi 7" touch panel, using LVGL<a name="dm-lvgl_cluster_rt1170_evkb_rpi"></a>
### Overview
 Cluster demo with LVGL on Raspberry Pi 7" touch panel. 

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY 
#### Categories:         Graphics 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MIMXRT1170-EVKB]()


#### **Repository URL:** https://github.com/nxp-appcodehub/dm-lvgl_cluster_rt1170_evkb_rpi
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lvgl_cluster_rt1170_evkb_rpi

<!-- dm-lvgl-vit-rt1060 -->
## 3. Demo of coffee machine using voice recognition (VIT) and LVGL graphics on i.MX RT1060<a name="dm-lvgl-vit-rt1060"></a>
### Overview
 This application code is to demonstrate LVGL Coffee Machine GUI + NXP VIT on RT1060-EVK for smart panel demo 

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY, I2C, I2S 
#### Categories:         Graphics, HMI, RTOS, Voice 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [EVK-MIMXRT1060](https://www.nxp.com/design/development-boards/i-mx-evaluation-and-development-boards/i-mx-rt1060-evaluation-kit:MIMXRT1060-EVKB)


#### **Repository URL:** https://github.com/nxp-appcodehub/dm-lvgl-vit-rt1060
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lvgl-vit-rt1060

<!-- dm-lvgl_cluster_rt1170_evk -->
## 4. How to enable a LVGL cluster demo with i.MX RT1170-EVK.<a name="dm-lvgl_cluster_rt1170_evk"></a>
### Overview
 This is a cluster demo with LVGL on MIMXRT1170-EVK with RK055HDMIPI4M 5.5" LCD panel. This demo shows the interface of the car/e-bike when driving, shows the interface of speedometer gear switching and signal icons switching. 

#### Families:           i.MX RT 
#### Toolchains:         IAR 
#### Peripherals:        DISPLAY 
#### Categories:         Graphics, RTOS 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MIMXRT1170-EVK](https://www.nxp.com/design/development-boards/i-mx-evaluation-and-development-boards/i-mx-rt1170-evaluation-kit:MIMXRT1170-EVK)

#### Expansion boards
* [RK055HDMIPI4MA0](https://mcuxpresso.nxp.com/eb-hub/product/rk055hdmipi4ma0)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-lvgl_cluster_rt1170_evk
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lvgl_cluster_rt1170_evk

<!-- dm-ml-ir-sensor-people-counting -->
## 5. Leveraging deep learning to count the number of people in a room using a low-resolution 8x8 infrared array sensor<a name="dm-ml-ir-sensor-people-counting"></a>
### Overview
 This shows how to create a deep learning model to count the number of people in a room using a low-resolution 8x8 infrared array sensor. 

#### Families:           LPC 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, SENSOR, UART, TIMER, CLOCKS 
#### Categories:         AI/ML, Vision 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S69](https://www.nxp.com/design/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s69-development-board:LPC55S69-EVK)
* [LPCXpresso55S28](https://www.nxp.com/design/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s28-development-board:LPC55S28-EVK)


#### **Repository URL:** https://github.com/nxp-appcodehub/dm-ml-ir-sensor-people-counting
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-ml-ir-sensor-people-counting

<!-- dm-lpc55s36-low-end-audio-demo -->
## 6. LPC55S36 Low End Audio Demo<a name="dm-lpc55s36-low-end-audio-demo"></a>
### Overview
 This example demo uses DAC output to generate low end audio through an external speaker. 

#### Families:           LPC 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DAC, UART, USB 
#### Categories:         Audio, Voice 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S36](https://www.nxp.com/design/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s36-development-board:LPCXpresso55S36)


#### **Repository URL:** https://github.com/nxp-appcodehub/dm-lpc55s36-low-end-audio-demo
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lpc55s36-low-end-audio-demo

<!-- dm-lpc860-smart-lighting -->
## 7. Smart lighting LED bulb using LPC860<a name="dm-lpc860-smart-lighting"></a>
### Overview
 This is the source code for using LPC860 as an IEC-62386 compatible smart RGB light bulb, and is the default firmware for the smart lighting control gear board. 

#### Families:           LPC 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        ADC, TIMER, PWM, DMA 
#### Categories:         HMI 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/nxp-appcodehub/dm-lpc860-smart-lighting
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lpc860-smart-lighting

<!-- dm-rt1170evkb-full-appliance -->
## 8. Full Appliance Demo<a name="dm-rt1170evkb-full-appliance"></a>
### Overview
 This is a Full Appliance Demo with LVGL on MIMXRT1170-EVKB with RK055HDMIPI4M 5.5" LCD panel. This Demo shows three appliances, an Oven, an Aircon and a Hood (each appliance has its own animations and can switch bettwen screens), it also has a central dashboard with the status of all appliances. 

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY 
#### Categories:         Graphics, HMI, RTOS 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MIMXRT1170-EVKB]()

#### Expansion boards
* [RK055HDMIPI4MA0](https://mcuxpresso.nxp.com/eb-hub/product/rk055hdmipi4ma0)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-rt1170evkb-full-appliance
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-rt1170evkb-full-appliance

<!-- dm-nafe_rt1170 -->
## 9. i.MX RT1170 + NAFE13388 drivers and demos<a name="dm-nafe_rt1170"></a>
### Overview
 This example demonstrates how to use NAFE13388 and i.MXRT1170 to sample analog signals. The results are either shown in a serial terminal window or in waveforms by using the FreeMASTER Run-Time Debugging Tool. 

#### Families:           i.MX RT 
#### Toolchains:         IAR 
#### Peripherals:        DMA, GPIO, SPI, UART 
#### Categories:         Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MIMXRT1170-EVKB]()
* [MIMXRT1170-EVK](https://www.nxp.com/design/development-boards/i-mx-evaluation-and-development-boards/i-mx-rt1170-evaluation-kit:MIMXRT1170-EVK)


#### **Repository URL:** https://github.com/nxp-appcodehub/dm-nafe_rt1170
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-nafe_rt1170

<!-- dm-mcxn947-video-playback -->
## 10. Raw Video Playback Demo for MCX N947<a name="dm-mcxn947-video-playback"></a>
### Overview
 This demo plays raw video file from SD card file system directly to LCD panel, in order to achieve high frame rate on performance constrained MCUs. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        SDMMC, DISPLAY 
#### Categories:         Graphics, SDMMC 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947]()

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-mcxn947-video-playback
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxn947-video-playback

<!-- dm-mcxn947-power-manager -->
## 11. MCXN94x power manager training lab<a name="dm-mcxn947-power-manager"></a>
### Overview
 The Power Manager example uses runtime menus to evaluate the power modes and power management features of the MCX Nx4x.  This example also uses the Power Manager component of MCUXpresso SDK, which provides a common framework of APIs for power management. For more details how to use this example and measure current, refer to the lab guide "MCXNx4x Power Management Lab.pdf". 

#### Families:           MCX 
#### Toolchains:         IAR, MCUXpresso IDE, VS Code 
#### Peripherals:        CLOCKS 
#### Categories:         Low Power 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MCX-N9XX-EVK]()
* [FRDM-MCXN947]()


#### **Repository URL:** https://github.com/nxp-appcodehub/dm-mcxn947-power-manager
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxn947-power-manager

<!-- dm-on-device-training-fan-anomaly-on-mcxn947 -->
## 12. On device training fan anomaly detection on MCXN947<a name="dm-on-device-training-fan-anomaly-on-mcxn947"></a>
### Overview
 On device trainable anomaly detection based on MCXN947. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        DISPLAY, I2C 
#### Categories:         AI/ML, Anomaly Detection, Graphics 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947]()

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)
* [ACCEL 4 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/accel 4 click)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-on-device-training-fan-anomaly-on-mcxn947
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-on-device-training-fan-anomaly-on-mcxn947

<!-- dm-nmh1000-magnetic-switch-example -->
## 13. Magnetic Wake-up Example using NMH1000 Magnetic Switch Sensor<a name="dm-nmh1000-magnetic-switch-example"></a>
### Overview
 This example demo describes how to configure NMH1000 magnetic switch sensor to enable magnetic wake-up use-case. Such use-case can find many applications where user would like to completely shut off power supply or put the device in power down mode etc. based on magnetic field applied. Examples include, smart meters, shelf labels, reed switch replacement, smart home etc.<br>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, SENSOR, UART 
#### Categories:         Sensor, Low Power 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947]()

#### Expansion boards
* [FRDM-STBI-NMH1000](https://mcuxpresso.nxp.com/eb-hub/product/frdm-stbi-nmh1000)
* [HALL SWITCH 3 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/hall switch 3 click)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-nmh1000-magnetic-switch-example
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-nmh1000-magnetic-switch-example

<!-- dm-mcxn-windowed-watchdog -->
## 14. MCXN - how to enable the windowed watchdog on low power<a name="dm-mcxn-windowed-watchdog"></a>
### Overview
 Create package software about how to enable watchdog in low power examples. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        WATCHDOG 
#### Categories:         Low Power 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947]()


#### **Repository URL:** https://github.com/nxp-appcodehub/dm-mcxn-windowed-watchdog
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxn-windowed-watchdog

<!-- dm-label-cifar10-images-on-mcxn947 -->
## 15. Label the CIFAR10 images from the camera on FRDM-MCXN947<a name="dm-label-cifar10-images-on-mcxn947"></a>
### Overview
 Label the CIFAR10 images from the camera on FRDM-MCXN947 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        DISPLAY 
#### Categories:         AI/ML, HMI 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947]()

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-label-cifar10-images-on-mcxn947
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-label-cifar10-images-on-mcxn947

<!-- dm-mcxn947-npu-vs-tensorflm-benchmark -->
## 16. MCXN947 NPU vs Tensorflm Benchmark<a name="dm-mcxn947-npu-vs-tensorflm-benchmark"></a>
### Overview
 This demo shows the performance benchmark between NPU and TensorFLM. Real time results are displayed on TFT LCD. On-chip NPU accelerates AI/ML algorithms and improves the performance. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY 
#### Categories:         AI/ML, Graphics 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947]()

#### Expansion boards
* [TFT PROTO 5 Capacitive](https://mcuxpresso.nxp.com/eb-hub/product/tft proto 5 capacitive)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-mcxn947-npu-vs-tensorflm-benchmark
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxn947-npu-vs-tensorflm-benchmark

<!-- dm-usb-audio-7-1-channel-speaker-on-mcxn947 -->
## 17. How to implement USB audio 7.1 channel speaker on MCXN947<a name="dm-usb-audio-7-1-channel-speaker-on-mcxn947"></a>
### Overview
 This demo will show you how to implement a USB audio 7.1 channel speaker on MCXN947 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        SAI, USB 
#### Categories:         Audio 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947]()

#### Expansion boards
* [AUD-EXP-42448](https://mcuxpresso.nxp.com/eb-hub/product/aud-exp-42448)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-usb-audio-7-1-channel-speaker-on-mcxn947
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-usb-audio-7-1-channel-speaker-on-mcxn947

<!-- dm-frdm-mcxn947-ebike -->
## 18. How to develop an electric bicycle dashboard design on MCXN947<a name="dm-frdm-mcxn947-ebike"></a>
### Overview
 This demo is an example of dashboard for electric bicycle. This demo is based on LVGL 8.3.10 and GUI Guider 1.6.0-GA. This demo can be used by customers to evaluate GUI performance of MCXN947. Here, this demo uses MCXN947 as target MCU and uses internal flash to store image source and font source. This demo supports various GUI widgets to show customer information such as meter panel, chart, label. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY 
#### Categories:         HMI 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947]()

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-frdm-mcxn947-ebike
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-frdm-mcxn947-ebike

<!-- dm-fashion-mnist-recognition-on-mcxn947 -->
## 19. Fashion MNIST Recognition on MCXN947<a name="dm-fashion-mnist-recognition-on-mcxn947"></a>
### Overview
 Fashion-MNIST recognition based on machine learning algorithm, power by MCXN947.Model is trained on Fashion-MNIST dataset, which can recognition 10 classes of fashion product from camera.Machine learning algorithm is accelerated by the NPU inside, the inference during is smaller than 10ms.<br><br>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        DISPLAY 
#### Categories:         AI/ML, HMI 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947]()

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-fashion-mnist-recognition-on-mcxn947
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-fashion-mnist-recognition-on-mcxn947

<!-- dm-multiple-face-detection-on-mcxn947 -->
## 20. Multiple face detection on mcxn947<a name="dm-multiple-face-detection-on-mcxn947"></a>
### Overview
 Multiple face detection on FRDM-MCXN947 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        DISPLAY, PWM 
#### Categories:         AI/ML 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947]()

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-multiple-face-detection-on-mcxn947
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-multiple-face-detection-on-mcxn947

<!-- dm-low-power-implementation-mcxa153 -->
## 21. How to implement low power on MCXA153<a name="dm-low-power-implementation-mcxa153"></a>
### Overview
 The low power implementation demo is used for power mode switch, wake up time measurement and low power current measurement on the FRDM-MCXA153 board. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        CLOCKS, UART 
#### Categories:         Low Power, Power Conversion 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA153]()


#### **Repository URL:** https://github.com/nxp-appcodehub/dm-low-power-implementation-mcxa153
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-low-power-implementation-mcxa153

<!-- dm-multiple-person-detection-on-mcxn947 -->
## 22. Multiple Person Detection on MCXN947<a name="dm-multiple-person-detection-on-mcxn947"></a>
### Overview
 Multiple person detection based on machine learning algorithms, powered by MCXN947. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        DISPLAY 
#### Categories:         AI/ML 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947]()

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-multiple-person-detection-on-mcxn947
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-multiple-person-detection-on-mcxn947

<!-- dm-frdm-mcxa153-freemaster-heart-rate -->
## 23. Heart rate (BPM) and SPO2 monitoring on FRDM-MCXA153<a name="dm-frdm-mcxa153-freemaster-heart-rate"></a>
### Overview
 This demo mainly demonstrates how to use FRDM-MCXA153 to collect ecg, heart rate and blood oxygen saturation data, also uses FreeMASTER as the UI for display. The MCU (MCXA153) adjusts intensity of LED's in sensor for reads better values of light intensity data from MAX30101 via the I2C bus, performs filtering, other signal processing operations and algorithms to obtain the final result (ecg ,heart rate and SPO2 with waveforms), and saves it in the on-chip RAM. The on-board debugger of FRDM-MCXA153 reads the ecg, heart rate and blood oxygen data from the MCU via the SWD, and displays the results on the FreeMASTER web page. The UI of FreeMASTER uses JS script for web-based waveform display. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C 
#### Categories:         Sensor 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153]()

#### Expansion boards
* [HEART RATE 4 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/heart rate 4 click)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-frdm-mcxa153-freemaster-heart-rate
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-frdm-mcxa153-freemaster-heart-rate

<!-- dm-industrial-panel-frdm-mcxn947 -->
## 24. Industrial Panel FRDM-MCXN947<a name="dm-industrial-panel-frdm-mcxn947"></a>
### Overview
 This demo demostrate capabilities of new FRDM-MCXN947. With only one core, the demo run motor control, lvgl, server, two temperature sensors, touch sensitive and get core performance.<br>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        ADC, PWM, UART, TIMER, I2C, ETHERNET 
#### Categories:         Graphics, Industrial, Motor Control, Sensor 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947]()

#### Expansion boards
* [FRDM-MC-LVPMSM](https://mcuxpresso.nxp.com/eb-hub/product/frdm-mc-lvpmsm)
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-industrial-panel-frdm-mcxn947
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-industrial-panel-frdm-mcxn947

<!-- dm-mcx-streamdeck -->
## 25. MCX STREAMDECK<a name="dm-mcx-streamdeck"></a>
### Overview
 A touch user interface to send hotkeys or shorcuts 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        USB, DISPLAY 
#### Categories:         Graphics, HMI 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947]()

#### Expansion boards
* [TFT PROTO 5 Capacitive](https://mcuxpresso.nxp.com/eb-hub/product/tft proto 5 capacitive)
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-mcx-streamdeck
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcx-streamdeck

<!-- dm-mcxn947-lcd-heart-rate-spo2 -->
## 26. vital signal monitor<a name="dm-mcxn947-lcd-heart-rate-spo2"></a>
### Overview
 The project is vital sign monitor that use a pulse-oximeter sensor to obtain the values and uses an LCD to show the values and the graphics of the measurements. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY, DMA, I2C 
#### Categories:         HMI, Graphics, Sensor 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947]()

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)
* [HEART RATE 4 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/heart rate 4 click)

#### **Repository URL:** https://github.com/nxp-appcodehub/dm-mcxn947-lcd-heart-rate-spo2
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxn947-lcd-heart-rate-spo2


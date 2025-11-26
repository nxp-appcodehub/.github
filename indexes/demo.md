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
7. [LPC55S69 Multi Face Detection](#dm-lpc55s69-multi-face-detection)
8. [LPC55S69 Fashion Mnist Object Recognition](#dm-lpc55s69-fashion-mnist-object-recognition)
9. [Smart lighting LED bulb using LPC860](#dm-lpc860-smart-lighting)
10. [Full Appliance Demo](#dm-rt1170evkb-full-appliance)
11. [i.MX RT1170 + NAFE13388 drivers and demos](#dm-nafe_rt1170)
12. [Very simple serial bootloader for NXP MCU](#dm-nxp_mcu_easy_bootloader)
13. [Raw Video Playback Demo for MCX N947](#dm-mcxn947-video-playback)
14. [MCXN947 NPU vs Tensorflm Benchmark](#dm-mcxn947-npu-vs-tensorflm-benchmark)
15. [How to implement low power on MCXA153](#dm-low-power-implementation-mcxa153)
16. [Fashion MNIST Recognition on MCXN947](#dm-fashion-mnist-recognition-on-mcxn947)
17. [On device training fan anomaly detection on MCXN947](#dm-on-device-training-fan-anomaly-on-mcxn947)
18. [MCXN94x power manager training lab](#dm-mcxn947-power-manager)
19. [Label the CIFAR10 images from the camera on FRDM-MCXN947](#dm-label-cifar10-images-on-mcxn947)
20. [Heart rate (BPM) and SPO2 monitoring on FRDM-MCXA153](#dm-frdm-mcxa153-freemaster-heart-rate)
21. [How to implement USB audio 7.1 channel speaker on MCXN947](#dm-usb-audio-7-1-channel-speaker-on-mcxn947)
22. [Multiple face detection on mcxn947](#dm-multiple-face-detection-on-mcxn947)
23. [Multiple Person Detection on MCXN947](#dm-multiple-person-detection-on-mcxn947)
24. [How to develop an electric bicycle dashboard design on MCXN947](#dm-frdm-mcxn947-ebike)
25. [MCX STREAMDECK](#dm-mcx-streamdeck)
26. [EZH implements keyscan function in lpc5516](#dm-lpc55s16-keyscan-by-ezh)
27. [Industrial Panel FRDM-MCXN947](#dm-industrial-panel-frdm-mcxn947)
28. [Magnetic Wake-up Example using NMH1000 Magnetic Switch Sensor](#dm-nmh1000-magnetic-switch-example)
29. [vital signal monitor](#dm-mcxn947-lcd-heart-rate-spo2)
30. [MCXN - how to enable the windowed watchdog on low power](#dm-mcxn-windowed-watchdog)
31. [Using EZH to implement camera interface in lpc55 series mcu](#dm-lpc55s69-camera-interface-by-ezh)
32. [EZH implements Quad encoder function in lpc5516](#dm-lpc55s16-qei-interface-by-ezh)
33. [Pressure and Altimeter Examples using MPL3115 Sensor](#dm-mpl3115-pressure-altimeter-examples)
34. [Using SmartDMA to implement camera interface in MCXN236](#dm-mcxn236-camera-interface-by-smartdma)
35. [This example demonstrates FXLS89xxxF 3-axis accelerometer evaluation GUI using ISSDK and FreeMASTER](#dm-freemaster-fxls89xxxf-evaluation-gui-firmware)
36. [This demo provides APIs to configure and read accurate temperature using P3T1085UK sensor](#dm-p3t1085uk-temperature-sensor-driver-with-demo-app)
37. [PCF2131 : Real Time Clock driver on FRDM-MCXN947.](#dm-pcf2131-real-time-clock-driver-with-demo-app)
38. [P3T1755: I3C temperature sensor demo](#dm-i3c-temperature-sensor)
39. [WiFi CLI M2 FRDM MCXN947](#dm-wifi-cli-frdm-mcxn947)
40. [K32W148 BLDC Motor control FreeRTOS application](#dm-bldc-motor-control-k32w148)
41. [Touch Keypad Tuning on MCXN](#dm-mcxn-touch-keypad-tuning)
42. [NMH1000 magnetic switch sensor evaluation GUI using ISSDK and FreeMASTER](#dm-freemaster-nmh1000-evaluation-gui-firmware)
43. [low power measurement on mcxn236](#dm-low-power-measurement-on-mcxn236)
44. [PCA9957HN led driver with demo app running on FRDM-MCXN947 and FRDM-MCXA153](#dm-pca9957hn-led-driver-with-demo-app)
45. [Multi sensor demo with FRDM-MCXN947 and LDC-PAR-S035](#dm-mcx-accel-and-pressure-monitor)
46. [Accel and Pressure sensor demo with FRDM-MCXA153](#dm-mcxa-accel-and-pressure-logger)
47. [RW612-FRDM Door chime demo with MQTT over Wi-Fi and I2S audio output](#dm-rw612frdm-door-chime-demo)
48. [[OOBE-MCXW71] Controlling LEDS using BLE Wireless UART](#dm-mcx-wireless-uart-leds)
49. [PCA9959HN led driver with demo app running on FRDM-MCXN947 and FRDM-MCXA153](#dm-pca9959hn-led-driver-with-demo-app)
50. [Nafe Industrial Application Examples using API Libraries](#dm-nafex388-application-examples)
51. [Implementation of Motor Control Algorithms to MCIMX93-EVK](#dm-motor-control-demo-for-i-mx93)
52. [EVSE-SIG-BRD using LPC5536/LPC55S36 for electric vehicle chargers](#dm-lpc5536-evse-sigbrd)
53. [PCF85063AT : Tiny Real Time Clock driver on FRDM-MCXN947 and MCXA153.](#dm-pcf85063at-real-time-clock-demo-app)
54. [A simple CAN bootloader project for FRDM-MCXA156](#dm-frdm-mcxa156-can-bootloader)
55. [Tamper detection with low-power wakeup sensor using BLE wireless UART](#dm-tamper-detection-using-low-power-wakeup-sensor-over-ble)
56. [FRDM-RW612 On-board temperature sensor over BLE](#dm-frdmrw612-temperature-sensor-over-ble)
57. [wolfSSL MQTT AWS Test using Zephyr RTOS](#nxp-appcodehub_dm-wolfmqtt-publisher-client-with-zephyr)
58. [wolfSSH RGB Server using Zephyr RTOS](#nxp-appcodehub_dm-wolfssh-rgb-server-with-zephyr)
59. [wolfSSL TLSv1.3 Hello Server using Zephyr RTOS](#nxp-appcodehub_dm-wolftpm-wolfssl-tls-with-zephyr)
60. [FRDM RW612 Kitchen Timer](#dm-frdm-rw612-kitchen-timer)
61. [SmartWatch Zephyr Demo](#apps_zephyr)
62. [Facial Detection Zephyr Demo](#apps_zephyr)
63. [FRDMHB2002ESEVM: Driver and demo app for MC33HB2002ES H-bridge motor controller](#dm-frdmhb2002esevm-motor-control-demo-app)
64. [Integrating EdgeLock® SE05X to FRDM-MCX-N development boards](#nano-package_examples_se05x_crypto_mcxn947)
65. [SJA1124EVB : Quad LIN Commander Transceiver with LIN Commander Controller](#dm-sja1124evb-spi-to-quad-lin-bridge)
66. [FRDM33926PNBEVM: Driver and demo app for MC33926 motor controller](#dm-frdm33926pnbevm-motor-control-driver-demo-app)
67. [Driving LCD-PAR-S035 using LVGL on FRM-MCXW71 board](#dm-mcxw71-driving-lcd-wireless-uart)
68. [Portable Anomaly Detect Demo with FRDM-MCXN947 and FXLS8974CF (ML Vibro Sens Click)](#dm-mcxn-portable-anomaly-detect-demo)
69. [MCXW71 Accelerometer and light sensor over Wireless UART](#dm-mcxw71-accel-and-light-ble)
70. [NAFE13388-UIM Industrial Applications with GUI and CLI support .](#dm-nafe13388-application-examples)
71. [Smart Sensing Inhaler using Pressure and Tilt sensors](#dm-smart-sensing-inhaler)
72. [Precision Inclinometer (Bubble Level) with FXLS8971](#dm-mcxn-bubble-level-demo)
73. [Snoring Detection based on RT1060 powered by AI\ML](#dm-snoring-detection-based-on-rt1060)
74. [matter zigbee bridge rw612](#dm-matter-zigbee-bridge-rw612)
75. [Integrating EdgeLock® SE05X to FRDM-MCX-A development boards](#nano-package_examples_se05x_crypto_mcxa153)
76. [Demo of Mikroe Joystick2Click in FRDM with CMSIS driver and GPIO adapter](#dm-mikroe-joystick2click-frdm)
77. [Demo of mikroe oledBclick in FRDM with CMSIS driver and GPIO adapter](#dm-mikroe-oledbclick-frdm)
78. [Demo of Mikroe Relay5CLick in FRDM with CMSIS driver and GPIO adapter](#dm-mikroe-relay5click-frdm)
79. [PMIC for Low Power Applications on FRDM-MCXN947 and MCXA153](#dm-pca9420uk-evm-pmic-for-low-power-application)
80. [Time Series Studio powered, on-device learning Fan anomaly detection based on FRDM-MCXA156](#dm-tss-powered-on-device-learning-fan-anomaly-based-on-mcxa156)
81. [MCXC444 LCD display and FXLS8974CF accelerometer motion detection](#dm-mcxc444-lcd-and-fxls8974cf-motion-detection)
82. [Wi-Fi connect using LCD interface on FRDM-MCXN947 using Wi-Fi expansion board FRDM-IW416-AW-AM510](#dm-wifi-lcd-connect-frdm-mcxn947)
83. [4x4 Key Click: multi-platform ecosystem.](#dm-mikroe-4x4-key-click-frdm)
84. [Knob G Click: multi-platform ecosystem.](#dm-mikroe-knob-g-click-frdm)
85. [FRDM-MCXN947 Sensorless Anomaly Detection for Motor Control System](#dm-ml-sensorless-anomaly-detection)
86. [Doom-MCX port of popular Doom game to run on NXP MCX microcontrollers](#doom-mcx)
87. [i.MX Driver Monitor System](#nxp-demo-experience-demos-list_scripts_machine_learning_dms)
88. [i.MX Smart Fitness](#nxp-demo-experience-demos-list_scripts_machine_learning_imx_smart_fitness)
89. [i.MX Machine Learning Benchmark Tool](#nxp-demo-experience-demos-list_scripts_machine_learning_ml_benchmark)
90. [NNStreamer Image Classification](#nxp-demo-experience-demos-list_scripts_machine_learning_nnstreamer_classification)
91. [NNStreamer Object Detection](#nxp-demo-experience-demos-list_scripts_machine_learning_nnstreamer_detection)
92. [Selfie Segmenter](#nxp-demo-experience-demos-list_scripts_machine_learning_selfie_segmenter)
93. [i.MX V4L2 Video Test Tool](#nxp-demo-experience-demos-list_scripts_multimedia_gstreamer_video_test)
94. [i.MX Smart Kitchen](#nxp-demo-experience-demos-list_scripts_multimedia_smart_kitchen)
95. [Clea Edgehog IoT devices using Zephyr RTOS](#edgehog-zephyr-device_samples_edgehog_app)
96. [Clea Astarte IoT devices using Zephyr RTOS](#astarte-device-sdk-zephyr_samples_astarte_app)
97. [WiFi provisioning using BLE on RT1170 EVKB using Wi-Fi Module Murata 2EL](#dm-wifi-provisioning-using-ble)
98. [KNX IoT stack examples running on FRDM-MCXW71](#dm-knx-iot-examples-on-nxp-mcxw71)
99. [PCA9422: PCA9422 Ultra Low Power Charger and Gauge PMIC for RT5/6/700 demo application on FRDM-MCXN947 and MCXA153 ](#dm-pca9422-evb-ultra-low-power-charger-gauge-pmic-demo-app)
100. [PCA9846: Four-Channel Ultra-Low Voltage, Fm+ I2C-Bus Switch with Reset demo application ](#dm-pca9846pw-ard-ultra-low-voltage-fm-plus-i2c-bus-switch-demo-app)
101. [PCAL6416AEV-ARD Low-Voltage Translating 16-Bit I²C-Bus/SMBus I/O Expander](#dm-pcal6416aev-low-voltage-translating-16-bit-i2c-bus-smbus-io-expander)
102. [NAFE13388 Universal Analog Sensing Module with Wired Connectivity](#dm-mcxn947-remote-io-with-nafe13388)
103. [Integrating EdgeLock® A30 secure authenticator to FRDM-MCXA153 board](#dm-a30-mcxa153-ecc-example)
104. [KW45: Secure boot scripts based on spsdk](#dm-kw45-secure-boot-scripts)
105. [Motor RPM Grapher in OLED with USB](#dm-ip-frdmmcxa153-oled-motor-graph-usb)
106. [P3H2X4X : I3C hub demo application on FRDM MCXN947 and MCXA153](#dm-p3h2x4x-i3c-hub-demo-application)
107. [FRDM-RW612 GUI Guider integration on Bluetooth LE example](#dm-nxp-rw612-gui-guider-ble)
108. [Motor RPM Control with KnobGClick and RPM Display in Real Time with USB](#dm-ip-frdmmcxc444-rotary-motor-update-usb)
109. [Motor RPM Control with KnobGClick with USB](#dm-ip-frdmmcxc242-rotary-motor-update-usb)
110. [FRDM-RW612 Sensors over Wi-Fi with http server](#dm-frdmrw612-sensors-over-wifi)
111. [eIQ GenAI Flow Demonstrator](#dm-eiq-genai-flow-demonstrator)
112. [Door Lock Cluster integration on a Lighting App Matter Application using K32W061 DK6](#dm-nxp-k32w061-dk6-door-lock-and-lighting-app-matter-application)
113. [PCAL9722: 22-Bit SPI I/O Expander with Agile I/O Features](#dm-pcal9722hn-22-bit-spi-gpio-expander)
114. [i.MX93 Smart Appliance for MATTER](#meta-smart-appliance)
115. [24-Channel SPI Serial Bus 63 mA / 5.5 V Constant-Current LED Driver](#dm-pca9958hn-led-driver-with-spi-demo-app)
116. [NXP Platform Accelerator for RW612 Freedom](#npa-vee-rw612)
117. [NXP Platform Accelerator for MCXN947 Freedom Board](#nxp-vee-mcxn947-frdm)
118. [NXP Platform Accelerator for i.MXRT595 EVK](#nxp-vee-imxrt595-evk)
119. [NXP Platform Accelerator for i.MXRT1170 EVK](#nxp-vee-imxrt1170-evk)
120. [Low-Power Wireless Sensors Examples for MCXW23](#dm-low-power-wireless-sensors-examples-for-mcxw23)
121. [HTTPS LCD LED Demo](#dm-https-lcd-led-demo)
122. [Wi-Fi Scan and Connectivity Demo on RW612BGA](#dm-wifi-set-up-ping)
123. [Demo of MikroE Oled C Click display in FRDM-MCX with CMSIS driver and GPIO adapter](#dm-mikroe-oled-c-click-display-frdm)
124. [DeepPacket: Encrypted network packets classification system](#app-network-ml)
125. [Low-Voltage Translating, 8-Bit I²C-Bus/SMBus I/O Expander](#dm-pcal6408a-8-bit-i2c-gpio-expander)
126. [I²C-Bus , 1 Degree C Accuracy, Digital Temperature Sensor ](#dm-pct2075dp-ard-temperature-sensor)
127. [Matter EdgeLock 2GO secure lock example running on RW612](#dm-matter-secure-lock-on-rw612)
128. [BLE throughput measurement on RT1170 EVKB + IW612](#dm-ble-throughput-measurement-rt1170)
129. [P3T1035xUK - P3T2030xUK - I3C, I2C-bus, 0.5 °C accuracy, digital temperature sensor](#dm-p3t1035xuk-p3t2030xuk-temperature-sensor-i2c-3c-bus-demo-app)
130. [I3C/I²C-Bus ±0.5 °C Accurate Digital Temperature Sensor with over temperature detection](#dm-p3t175xdp-i2c-13c-temperature-sensor-demo-app)
131. [NETC: Ethernet Switch Control on M33 with Management Port Sharing via VSIs with A-cores](#dm-imx943-netc-control-and-sharing-between-m33s-acore)
132. [ MCXA34X  triple motor control demo using HVP board](#dm-mc-pmsm-triple-mcxa34x)
133. [HTTP Client Get and Post JSON Data](#dm-http-client-get-and-post-json-data)
134. [Wireless RFTM Application for Performance Testing of RW612 board](#dm-wireless-rf-test-mode-demo)
135. [demo project to use the module sCan](#dm-loc-apps-kw47)
136. [Bluetooth LE FSCI Host Application running on FRDM-MCXN947 and MCXW236B-Click Board](#dm-ble-fsci-host-application)
137. [i.MX93 Low Power Machine Learning](#nxp-demo-experience-demos-list_scripts_machine_learning_low_power_ml)
138. [Interactive Ping Pong Game Demo Using the MCXN947 Click Shield with OLED C Display and Dual Joystick Click Boards](#dm-mcxn947-click-shield-ping-pong-game)
139. [Golioth Bluetooth Data to the Cloud using Pouch](#nxp-appcodehub_dm-ble-cloud)
140. [wolfSSL TLSv1.3 Hello Server Doing Post-Quantum Cryptography using Zephyr RTOS](#nxp-appcodehub_dm-wolfssl-tls-hello-server-pqc-with-zephyr)

<!-- dm-lvgl-epaper-smartlabel-kw45/. -->
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

<!-- dm-lvgl_cluster_rt1170_evkb_rpi/. -->
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

<!-- dm-lvgl-vit-rt1060/. -->
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

<!-- dm-lvgl_cluster_rt1170_evk/. -->
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

<!-- dm-ml-ir-sensor-people-counting/. -->
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

<!-- dm-lpc55s36-low-end-audio-demo/. -->
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

<!-- dm-lpc55s69-multi-face-detection/. -->
## 7. LPC55S69 Multi Face Detection<a id="dm-lpc55s69-multi-face-detection"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo demonstrates the AI capabilities of the LPC55S69. It displays the image captured by the camera on the LCD screen and performs face detection. 

#### Families:           LPC 
#### Toolchains:         MDK 
#### Peripherals:        I2C, SPI, TIMER 
#### Categories:         AI/ML 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S69](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s69-development-board:LPC55S69-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-lpc55s69-multi-face-detection/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lpc55s69-multi-face-detection

<!-- dm-lpc55s69-fashion-mnist-object-recognition/. -->
## 8. LPC55S69 Fashion Mnist Object Recognition<a id="dm-lpc55s69-fashion-mnist-object-recognition"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo demonstrates the AI capabilities of the LPC55S69. It displays the image captured by the camera on the LCD screen and performs fashion mnist object recognition. 

#### Families:           LPC 
#### Toolchains:         MDK 
#### Peripherals:        I2C, SPI 
#### Categories:         AI/ML 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S69](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s69-development-board:LPC55S69-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-lpc55s69-fashion-mnist-object-recognition/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lpc55s69-fashion-mnist-object-recognition

<!-- dm-lpc860-smart-lighting/. -->
## 9. Smart lighting LED bulb using LPC860<a id="dm-lpc860-smart-lighting"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-rt1170evkb-full-appliance/. -->
## 10. Full Appliance Demo<a id="dm-rt1170evkb-full-appliance"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-nafe_rt1170/. -->
## 11. i.MX RT1170 + NAFE13388 drivers and demos<a id="dm-nafe_rt1170"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-nxp_mcu_easy_bootloader/. -->
## 12. Very simple serial bootloader for NXP MCU<a id="dm-nxp_mcu_easy_bootloader"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-mcxn947-video-playback/. -->
## 13. Raw Video Playback Demo for MCX N947<a id="dm-mcxn947-video-playback"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-mcxn947-npu-vs-tensorflm-benchmark/. -->
## 14. MCXN947 NPU vs Tensorflm Benchmark<a id="dm-mcxn947-npu-vs-tensorflm-benchmark"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-low-power-implementation-mcxa153/. -->
## 15. How to implement low power on MCXA153<a id="dm-low-power-implementation-mcxa153"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-fashion-mnist-recognition-on-mcxn947/. -->
## 16. Fashion MNIST Recognition on MCXN947<a id="dm-fashion-mnist-recognition-on-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-on-device-training-fan-anomaly-on-mcxn947/. -->
## 17. On device training fan anomaly detection on MCXN947<a id="dm-on-device-training-fan-anomaly-on-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-mcxn947-power-manager/. -->
## 18. MCXN94x power manager training lab<a id="dm-mcxn947-power-manager"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-label-cifar10-images-on-mcxn947/. -->
## 19. Label the CIFAR10 images from the camera on FRDM-MCXN947<a id="dm-label-cifar10-images-on-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Label the CIFAR10 images from the camera on FRDM-MCXN947 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        DISPLAY 
#### Categories:         HMI, AI/ML 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-label-cifar10-images-on-mcxn947/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-label-cifar10-images-on-mcxn947

<!-- dm-frdm-mcxa153-freemaster-heart-rate/. -->
## 20. Heart rate (BPM) and SPO2 monitoring on FRDM-MCXA153<a id="dm-frdm-mcxa153-freemaster-heart-rate"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-usb-audio-7-1-channel-speaker-on-mcxn947/. -->
## 21. How to implement USB audio 7.1 channel speaker on MCXN947<a id="dm-usb-audio-7-1-channel-speaker-on-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-multiple-face-detection-on-mcxn947/. -->
## 22. Multiple face detection on mcxn947<a id="dm-multiple-face-detection-on-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-multiple-person-detection-on-mcxn947/. -->
## 23. Multiple Person Detection on MCXN947<a id="dm-multiple-person-detection-on-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-frdm-mcxn947-ebike/. -->
## 24. How to develop an electric bicycle dashboard design on MCXN947<a id="dm-frdm-mcxn947-ebike"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-mcx-streamdeck/. -->
## 25. MCX STREAMDECK<a id="dm-mcx-streamdeck"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-lpc55s16-keyscan-by-ezh/. -->
## 26. EZH implements keyscan function in lpc5516<a id="dm-lpc55s16-keyscan-by-ezh"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 EZH, as a co-processor of LPC55, can quickly access IO. For mechanical repetitive tasks like keyscan, EZH provides high and low levels for each row of the keyboard, then quickly reads the level of each column, and finally determines which button is pressed. It is very suitable for keyboard applications. 

#### Families:           LPC 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        GPIO, UART 
#### Categories:         HMI, Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S16](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s16-development-board:LPC55S16-EVK)

#### Expansion boards
* [ROTARY Y CLICK](https://mcuxpresso.nxp.com/eb-hub/product/rotary y click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-lpc55s16-keyscan-by-ezh/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lpc55s16-keyscan-by-ezh

<!-- dm-industrial-panel-frdm-mcxn947/. -->
## 27. Industrial Panel FRDM-MCXN947<a id="dm-industrial-panel-frdm-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-nmh1000-magnetic-switch-example/. -->
## 28. Magnetic Wake-up Example using NMH1000 Magnetic Switch Sensor<a id="dm-nmh1000-magnetic-switch-example"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-mcxn947-lcd-heart-rate-spo2/. -->
## 29. vital signal monitor<a id="dm-mcxn947-lcd-heart-rate-spo2"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-mcxn-windowed-watchdog/. -->
## 30. MCXN - how to enable the windowed watchdog on low power<a id="dm-mcxn-windowed-watchdog"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-lpc55s69-camera-interface-by-ezh/. -->
## 31. Using EZH to implement camera interface in lpc55 series mcu<a id="dm-lpc55s69-camera-interface-by-ezh"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo introduces a parallel interface for the camera solution for LPC55(S)xx.<br><br>

#### Families:           LPC 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, GPIO, SPI, VIDEO 
#### Categories:         Graphics, HMI 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S69](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s69-development-board:LPC55S69-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-lpc55s69-camera-interface-by-ezh/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lpc55s69-camera-interface-by-ezh

<!-- dm-lpc55s16-qei-interface-by-ezh/. -->
## 32. EZH implements Quad encoder function in lpc5516<a id="dm-lpc55s16-qei-interface-by-ezh"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo introduces a method to implement two input quad encoder function by using EZH in LPC55.EZH, as a co-processor of LPC55, can quickly access IO. For mechanical repetitive tasks like Quad encoder(QEI) signal scan. EZH detect the level and edge changing of phase A and phase B, then calculate the direction and index. 

#### Families:           LPC 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        GPIO 
#### Categories:         Motor Control, Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [LPCXpresso55S16](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/lpcxpresso-boards/lpcxpresso55s16-development-board:LPC55S16-EVK)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-lpc55s16-qei-interface-by-ezh/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-lpc55s16-qei-interface-by-ezh

<!-- dm-mpl3115-pressure-altimeter-examples/. -->
## 33. Pressure and Altimeter Examples using MPL3115 Sensor<a id="dm-mpl3115-pressure-altimeter-examples"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-mcxn236-camera-interface-by-smartdma/. -->
## 34. Using SmartDMA to implement camera interface in MCXN236<a id="dm-mcxn236-camera-interface-by-smartdma"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-freemaster-fxls89xxxf-evaluation-gui-firmware/. -->
## 35. This example demonstrates FXLS89xxxF 3-axis accelerometer evaluation GUI using ISSDK and FreeMASTER<a id="dm-freemaster-fxls89xxxf-evaluation-gui-firmware"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-p3t1085uk-temperature-sensor-driver-with-demo-app/. -->
## 36. This demo provides APIs to configure and read accurate temperature using P3T1085UK sensor<a id="dm-p3t1085uk-temperature-sensor-driver-with-demo-app"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-pcf2131-real-time-clock-driver-with-demo-app/. -->
## 37. PCF2131 : Real Time Clock driver on FRDM-MCXN947.<a id="dm-pcf2131-real-time-clock-driver-with-demo-app"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-i3c-temperature-sensor/. -->
## 38. P3T1755: I3C temperature sensor demo<a id="dm-i3c-temperature-sensor"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Demonstrates MIPI I3C bus operation with P3T1755 temperature sensor and MCX microcontroller.  <br>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I3C 
#### Categories:         Sensor 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-i3c-temperature-sensor/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-i3c-temperature-sensor

<!-- dm-wifi-cli-frdm-mcxn947/. -->
## 39. WiFi CLI M2 FRDM MCXN947<a id="dm-wifi-cli-frdm-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This is an example of cli use with wifi on frdm-mcxn947 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        SDIO, UART 
#### Categories:         RTOS, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-wifi-cli-frdm-mcxn947/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-wifi-cli-frdm-mcxn947

<!-- dm-bldc-motor-control-k32w148/. -->
## 40. K32W148 BLDC Motor control FreeRTOS application<a id="dm-bldc-motor-control-k32w148"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-mcxn-touch-keypad-tuning/. -->
## 41. Touch Keypad Tuning on MCXN<a id="dm-mcxn-touch-keypad-tuning"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-freemaster-nmh1000-evaluation-gui-firmware/. -->
## 42. NMH1000 magnetic switch sensor evaluation GUI using ISSDK and FreeMASTER<a id="dm-freemaster-nmh1000-evaluation-gui-firmware"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-low-power-measurement-on-mcxn236/. -->
## 43. low power measurement on mcxn236<a id="dm-low-power-measurement-on-mcxn236"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-pca9957hn-led-driver-with-demo-app/. -->
## 44. PCA9957HN led driver with demo app running on FRDM-MCXN947 and FRDM-MCXA153<a id="dm-pca9957hn-led-driver-with-demo-app"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-mcx-accel-and-pressure-monitor/. -->
## 45. Multi sensor demo with FRDM-MCXN947 and LDC-PAR-S035<a id="dm-mcx-accel-and-pressure-monitor"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-mcxa-accel-and-pressure-logger/. -->
## 46. Accel and Pressure sensor demo with FRDM-MCXA153<a id="dm-mcxa-accel-and-pressure-logger"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-rw612frdm-door-chime-demo/. -->
## 47. RW612-FRDM Door chime demo with MQTT over Wi-Fi and I2S audio output<a id="dm-rw612frdm-door-chime-demo"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo shows how to implement a wireless door chime with the RW612-FRDM board. <br>The chime is controlled over Wi-Fi with the MQTT application protocol. Chime sound data is streamed on the I2S pins of the RW612-FRDM Arduino header. An external codec and also an amplifier are required to play the sound on an external speaker. 

#### Families:           RW 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2S 
#### Categories:         Audio, RTOS, Networking, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-rw612frdm-door-chime-demo/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-rw612frdm-door-chime-demo

<!-- dm-mcx-wireless-uart-leds/. -->
## 48. [OOBE-MCXW71] Controlling LEDS using BLE Wireless UART<a id="dm-mcx-wireless-uart-leds"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo allows the user to interact with the device through a serial terminal and also it can be possible to change the LCD screen via command sent by the IoT Toolbox using a Smartphone. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        GPIO, UART 
#### Categories:         Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXW7X]()
* [FRDM-MCXW71](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-w71x-wireless-mcus:FRDM-MCXW71)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcx-wireless-uart-leds/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcx-wireless-uart-leds

<!-- dm-pca9959hn-led-driver-with-demo-app/. -->
## 49. PCA9959HN led driver with demo app running on FRDM-MCXN947 and FRDM-MCXA153<a id="dm-pca9959hn-led-driver-with-demo-app"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-nafex388-application-examples/. -->
## 50. Nafe Industrial Application Examples using API Libraries<a id="dm-nafex388-application-examples"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-motor-control-demo-for-i-mx93/. -->
## 51. Implementation of Motor Control Algorithms to MCIMX93-EVK<a id="dm-motor-control-demo-for-i-mx93"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Implementation of motor control algorithms using the MCIMX93-EVK development kit. It includes hardware configuration details, setup instructions, and an overview of the software implementation process. 

#### Families:           i.MX 
#### Toolchains:         IAR 
#### Peripherals:        PWM, GPIO, ADC 
#### Categories:         Motor Control 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MCIMX93-EVK]()

#### Expansion boards
* [FRDM-MC-LVPMSM](https://mcuxpresso.nxp.com/eb-hub/product/frdm-mc-lvpmsm)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-motor-control-demo-for-i-mx93/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-motor-control-demo-for-i-mx93

<!-- dm-lpc5536-evse-sigbrd/. -->
## 52. EVSE-SIG-BRD using LPC5536/LPC55S36 for electric vehicle chargers<a id="dm-lpc5536-evse-sigbrd"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-pcf85063at-real-time-clock-demo-app/. -->
## 53. PCF85063AT : Tiny Real Time Clock driver on FRDM-MCXN947 and MCXA153.<a id="dm-pcf85063at-real-time-clock-demo-app"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-frdm-mcxa156-can-bootloader/. -->
## 54. A simple CAN bootloader project for FRDM-MCXA156<a id="dm-frdm-mcxa156-can-bootloader"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 A simple CAN bootloader project for FRDM-MCXA156 

#### Families:           MCX 
#### Toolchains:         MDK 
#### Peripherals:        CAN 
#### Categories:         Tools 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA156](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a144-5-6-a154-5-6-mcus:FRDM-MCXA156)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-frdm-mcxa156-can-bootloader/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-frdm-mcxa156-can-bootloader

<!-- dm-tamper-detection-using-low-power-wakeup-sensor-over-ble/. -->
## 55. Tamper detection with low-power wakeup sensor using BLE wireless UART<a id="dm-tamper-detection-using-low-power-wakeup-sensor-over-ble"></a> <a href="#top" style="float:right">⤒</a>

### Overview
<ul><li>This example demo describes how to configure low-power motion or magnetic or pressure wake-up sensor for tamper/theft detection and transmit ALERT to connected end user via BLE wireless UART using FRDM-MCXW71.</li><li>Such use-case can find many applications where user would like to completely shut off power supply or put the device in power down mode etc. based on wake up detected by sensors. Examples include, smart meters, shelf labels, reed switch replacement, smart home etc.</li></ul>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, UART, Bluetooth 
#### Categories:         Low Power, Sensor, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXW7X]()
* [FRDM-MCXW71](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-w71x-wireless-mcus:FRDM-MCXW71)

#### Expansion boards
* [FRDMSTBC-P3115](https://mcuxpresso.nxp.com/eb-hub/product/frdmstbc-p3115)
* [FRDM-STBI-NMH1000](https://mcuxpresso.nxp.com/eb-hub/product/frdm-stbi-nmh1000)
* [HALL SWITCH 3 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/hall switch 3 click)
* [ACCEL PRESSURE CLICK](https://mcuxpresso.nxp.com/eb-hub/product/accel pressure click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-tamper-detection-using-low-power-wakeup-sensor-over-ble/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-tamper-detection-using-low-power-wakeup-sensor-over-ble

<!-- dm-frdmrw612-temperature-sensor-over-ble/. -->
## 56. FRDM-RW612 On-board temperature sensor over BLE<a id="dm-frdmrw612-temperature-sensor-over-ble"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo shows how to use the FRDM-RW612's P3T1755&nbsp;on-board temperature sensor. Also, temperature measurements are sent over Bluetooth low energy so they can be seen with the IoT toolbox mobile application.<br><br>

#### Families:           RW 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C 
#### Categories:         Sensor, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-frdmrw612-temperature-sensor-over-ble/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-frdmrw612-temperature-sensor-over-ble

<!-- nxp-appcodehub/dm-wolfmqtt-publisher-client-with-zephyr -->
## 57. wolfSSL MQTT AWS Test using Zephyr RTOS<a id="nxp-appcodehub_dm-wolfmqtt-publisher-client-with-zephyr"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo demostrate capabilities of new FRDM-MCXN947.<br><a href="https://github.com/wolfSSL/nxp-appcodehub/tree/main/dm-wolfmqtt-publisher-client-with-zephyr#demo" target="_blank"></a>Simple connects to an AWS broker subscribes, and publishes a message. 

#### Families:           MCX 
#### Toolchains:         VS Code 
#### Peripherals:        UART, ETHERNET 
#### Categories:         Cloud Connected Devices, Networking, Wireless Connectivity 
#### Application format: Zephyr Project
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/wolfSSL/nxp-appcodehub/tree/main/dm-wolfmqtt-publisher-client-with-zephyr
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-wolfmqtt-publisher-client-with-zephyr

<!-- nxp-appcodehub/dm-wolfssh-rgb-server-with-zephyr -->
## 58. wolfSSH RGB Server using Zephyr RTOS<a id="nxp-appcodehub_dm-wolfssh-rgb-server-with-zephyr"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo demostrates capabilities of new FRDM-MCXN947.<br><a href="https://github.com/wolfSSL/nxp-appcodehub/tree/main/dm-wolfssh-rgb-server-with-zephyr#demo" target="_blank"></a>Creating a simple server using the Zephyr RTOS and wolfSSL to utilize the networking capabilities of the FRDM-MCXN947 through its ethernet port. 

#### Families:           MCX 
#### Toolchains:         VS Code 
#### Peripherals:        ETHERNET, UART 
#### Categories:         Cloud Connected Devices, RTOS, Networking 
#### Application format: Zephyr Project
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/wolfSSL/nxp-appcodehub/tree/main/dm-wolfssh-rgb-server-with-zephyr
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-wolfssh-rgb-server-with-zephyr

<!-- nxp-appcodehub/dm-wolftpm-wolfssl-tls-with-zephyr -->
## 59. wolfSSL TLSv1.3 Hello Server using Zephyr RTOS<a id="nxp-appcodehub_dm-wolftpm-wolfssl-tls-with-zephyr"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Creating a simple server using the Zephyr RTOS and wolfSSL to utilize the networking capabilities of the FRDM-MCXN947 through its ethernet port. 

#### Families:           MCX 
#### Toolchains:         VS Code 
#### Peripherals:        ETHERNET, UART 
#### Categories:         RTOS, Networking 
#### Application format: Zephyr Project
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/wolfSSL/nxp-appcodehub/tree/main/dm-wolftpm-wolfssl-tls-with-zephyr
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-wolfssl-tls-hello-server-with-zephyr

<!-- dm-frdm-rw612-kitchen-timer/. -->
## 60. FRDM RW612 Kitchen Timer<a id="dm-frdm-rw612-kitchen-timer"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- apps_zephyr/. -->
## 61. SmartWatch Zephyr Demo<a id="apps_zephyr"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Wearable example application optimized for the i.MX RT500 MCU.&nbsp; Leverages display driver to MIPI smart wearable display.&nbsp; Power-optimized reference for battery-powered devices. Leverages Zephyr’s Power Management subsystem.&nbsp; Demonstrates power-optimization techniques for applications.&nbsp; UI created with LVGL and NXP’s&nbsp;<a href="https://www.nxp.com/design/software/development-software/gui-guider:GUI-GUIDER" target="_blank">GUI-Guider tool</a>.&nbsp; Professional LVGL graphics with multiple animated watch screens.&nbsp; Leverages GPU acceleration to offload CPU.&nbsp; &nbsp;<br>

#### Families:           i.MX RT 
#### Toolchains:         VS Code 
#### Peripherals:        CLOCKS, DISPLAY, DMA 
#### Categories:         Low Power, Graphics, RTOS, User Interface 
#### Application format: Zephyr Project
#### Compatible boards:
* [VAL-MIMXRT500]()

#### Expansion boards
* [G1120B0MIPI](https://mcuxpresso.nxp.com/eb-hub/product/g1120b0mipi)

#### **Repository URL:** https://github.com/nxp-zephyr/apps_zephyr/tree/SmartWatch
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-smartwatch-zephyr-demo

<!-- apps_zephyr/. -->
## 62. Facial Detection Zephyr Demo<a id="apps_zephyr"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Multiple Face detection based on the machine learning algorithm.  A portable Zephyr application that runs on MCXN947 with ML accelerated by the NPU, and on i.MX RT1060. 

#### Families:           MCX, i.MX RT 
#### Toolchains:         GCC, VS Code 
#### Peripherals:        DISPLAY, DMA, FlexIO, I2C, VIDEO 
#### Categories:         AI/ML, RTOS, Vision 
#### Application format: Zephyr Project
#### Compatible boards:
* [MIMXRT1060-EVKB](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1060-evaluation-kit:MIMXRT1060-EVKB)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [RK043FN66HS-CTG](https://mcuxpresso.nxp.com/eb-hub/product/rk043fn66hs-ctg)
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/nxp-zephyr/apps_zephyr/tree/FacialDetect
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-facialdetect-zephyr-demo

<!-- dm-frdmhb2002esevm-motor-control-demo-app/. -->
## 63. FRDMHB2002ESEVM: Driver and demo app for MC33HB2002ES H-bridge motor controller<a id="dm-frdmhb2002esevm-motor-control-demo-app"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- nano-package/examples/se05x_crypto/mcxn947 -->
## 64. Integrating EdgeLock® SE05X to FRDM-MCX-N development boards<a id="nano-package_examples_se05x_crypto_mcxn947"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo project provides a detailed information on how to integrate the EdgeLock® SE05X series into the FRDM development boards of MCX-N family. Additionally, the project contains several demo applications to showcase how to enable security on the MCX-N family. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C 
#### Categories:         Secure Provisioning, Cloud Connected Devices, Industrial, Security 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [OM-SE050ARD-E](https://mcuxpresso.nxp.com/eb-hub/product/om-se050ard-e)
* [OM-A5000ARD](https://mcuxpresso.nxp.com/eb-hub/product/om-a5000ard)
* [OM-SE051ARD](https://mcuxpresso.nxp.com/eb-hub/product/om-se051ard)
* [OM-SE052ARD](https://mcuxpresso.nxp.com/eb-hub/product/om-se052ard)

#### **Repository URL:** https://github.com/NXPPlugNTrust/nano-package/tree/master/examples/se05x_crypto/mcxn947
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-integrating-se05x-to-frdm-mcx

<!-- dm-sja1124evb-spi-to-quad-lin-bridge/. -->
## 65. SJA1124EVB : Quad LIN Commander Transceiver with LIN Commander Controller<a id="dm-sja1124evb-spi-to-quad-lin-bridge"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-frdm33926pnbevm-motor-control-driver-demo-app/. -->
## 66. FRDM33926PNBEVM: Driver and demo app for MC33926 motor controller<a id="dm-frdm33926pnbevm-motor-control-driver-demo-app"></a> <a href="#top" style="float:right">⤒</a>

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

<!-- dm-mcxw71-driving-lcd-wireless-uart/. -->
## 67. Driving LCD-PAR-S035 using LVGL on FRM-MCXW71 board<a id="dm-mcxw71-driving-lcd-wireless-uart"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 allows the user to interact with the device through a serial terminal and also it can be possible to see the commands pressed in the LCD through the IoT Toolbox using a Smartphone. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY, I2C, SPI, UART 
#### Categories:         Graphics, Industrial, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXW7X]()
* [FRDM-MCXW71](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-w71x-wireless-mcus:FRDM-MCXW71)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcxw71-driving-lcd-wireless-uart/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxw71-driving-lcd-wireless-uart

<!-- dm-mcxn-portable-anomaly-detect-demo/. -->
## 68. Portable Anomaly Detect Demo with FRDM-MCXN947 and FXLS8974CF (ML Vibro Sens Click)<a id="dm-mcxn-portable-anomaly-detect-demo"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 The Portable Anomaly Detect demo shows an on-device trainable anomaly detection platform that is based on the FRDM-MCXN947 board. The demo shows how to train the SVM model on-device with FXLS8974CF accelerometer data and inference SVM model on-device too.<br>During the whole life cycle of a device, learning may need to be done multiple times.<br>The GUI is implemented in LVGL. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        VIDEO, DISPLAY, FLASH, I2C, PWM, UART 
#### Categories:         Graphics, Sensor, Anomaly Detection, AI/ML 
#### Application format: Python (Linux)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)
* [ML Vibro Sens Click](https://mcuxpresso.nxp.com/eb-hub/product/ml vibro sens click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcxn-portable-anomaly-detect-demo/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxn-portable-anomaly-detect-demo

<!-- dm-mcxw71-accel-and-light-ble/. -->
## 69. MCXW71 Accelerometer and light sensor over Wireless UART<a id="dm-mcxw71-accel-and-light-ble"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo serves as guide on enabling FXLS897xxx accelerometer over I2C and light sensor over ADC readings. The ADC conversions are trigger by a hardware timer trigger. The I2C transfers make use of CMSIS-Drives. Interact application through the IoT Toolbox using a Smartphone. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        ADC, I2C, PWM 
#### Categories:         Sensor, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXW71](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-w71x-wireless-mcus:FRDM-MCXW71)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcxw71-accel-and-light-ble/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxw71-accel-and-light-ble

<!-- dm-nafe13388-application-examples/. -->
## 70. NAFE13388-UIM Industrial Applications with GUI and CLI support .<a id="dm-nafe13388-application-examples"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This is a demo application which provides a command line interface&nbsp; and GUI interface for these six applications of NAFE13388 for Analog to Digital Conversion.<br>Current Sensing using SCSR Conversion<br>Voltage Sensing using SCSR Conversion<br>Voltage Sensing using MCMR Conversion<br>RTD 2/4 Wires using SCCR Conversion<br>Weight Scale 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        GPIO, SENSOR, SPI, TIMER, UART, DMA 
#### Categories:         Sensor, Industrial, User Interface 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [NAFE13388-UIM](https://mcuxpresso.nxp.com/eb-hub/product/nafe13388-uim)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-nafe13388-application-examples/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-nafe13388-application-examples

<!-- dm-smart-sensing-inhaler/. -->
## 71. Smart Sensing Inhaler using Pressure and Tilt sensors<a id="dm-smart-sensing-inhaler"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This example use FRDM-MCXW71 and on-board FXLS8974CF accelerometer as Tilt sensor withMPL3115 absolute pressure sensor expansion board FRDM-STBC-P3115 to demonstrate connected smart sensing inhaler application.<br><ul><li>Intelligent dosage trigger function to align dispensation with patient’s tidal breathing pattern using High precision, digital pressure sensor MPL3115.</li><li>Maintains correct inhaler posture to deliver right amount dosage using 3-axis accelerometer FXLS8974CF as Tilt sensor.</li><li>Inform on dosages inhaled over BLE wireless UART&nbsp;allowing remote patient monitoring, helps with patient’s adherence to dosages and compliance.</li></ul>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, UART, SENSOR 
#### Categories:         Sensor, Wireless Connectivity, Tools 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXW7X]()
* [FRDM-MCXW71](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-w71x-wireless-mcus:FRDM-MCXW71)

#### Expansion boards
* [FRDMSTBC-P3115](https://mcuxpresso.nxp.com/eb-hub/product/frdmstbc-p3115)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-smart-sensing-inhaler/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-smart-sensing-inhaler

<!-- dm-mcxn-bubble-level-demo/. -->
## 72. Precision Inclinometer (Bubble Level) with FXLS8971<a id="dm-mcxn-bubble-level-demo"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo shows how to integrate the NXP sensors FXLS8971CF (3-axis accelerometer) with FRDM-MCXN947 platform. In this application the FXLS8971CF is hosted and an I2C peripheral on an “Inclinometer 4 Click” board from Mikroe.&nbsp;The FXLS8971CF is 3-axis accelerometer that is designed to serve inclinometer (and accelerometer) applications. Offset and Sensitivity response across the temperature band (-40°C to 105°C) is near zero, and is best in class.<br>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, SENSOR, UART, VIDEO 
#### Categories:         Graphics, Sensor, RTOS 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)
* [INCLINOMETER 4 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/inclinometer 4 click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcxn-bubble-level-demo/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxn-bubble-level-demo

<!-- dm-snoring-detection-based-on-rt1060/. -->
## 73. Snoring Detection based on RT1060 powered by AI\ML<a id="dm-snoring-detection-based-on-rt1060"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 The snoring detection demo is designed based on the i.MX RT1060. WAV audio files on the SD card can be played through the speaker and processed into a ML model to determine whether there is snoring or not, the results will be displayed on a GUI designed based on LVGL. 

#### Families:           i.MX RT 
#### Toolchains:         MDK 
#### Peripherals:        DISPLAY, SDMMC 
#### Categories:         AI/ML 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [EVK-MIMXRT1060](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1060-evaluation-kit:MIMXRT1060-EVKB)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-snoring-detection-based-on-rt1060/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-snoring-detection-based-on-rt1060

<!-- dm-matter-zigbee-bridge-rw612/. -->
## 74. matter zigbee bridge rw612<a id="dm-matter-zigbee-bridge-rw612"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo provide user how to integrate non-matter device as zigbee nodes to Matter enviroment 

#### Families:           RW 
#### Toolchains:         GCC 
#### Peripherals:        UART 
#### Categories:         RTOS, Wireless Connectivity, Bridge 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [RD-RW612-BGA]()


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-matter-zigbee-bridge-rw612/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-matter-zigbee-bridge-rw612

<!-- nano-package/examples/se05x_crypto/mcxa153 -->
## 75. Integrating EdgeLock® SE05X to FRDM-MCX-A development boards<a id="nano-package_examples_se05x_crypto_mcxa153"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo project provides a detailed information on how to integrate the EdgeLock® SE05X series into the FRDM development boards of MCX-A family. Additionally, the project contains several demo applications to showcase how to enable security on the MCX-A family. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C 
#### Categories:         Secure Provisioning, Industrial, Security 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)

#### Expansion boards
* [OM-SE050ARD-E](https://mcuxpresso.nxp.com/eb-hub/product/om-se050ard-e)
* [OM-A5000ARD](https://mcuxpresso.nxp.com/eb-hub/product/om-a5000ard)
* [OM-SE051ARD](https://mcuxpresso.nxp.com/eb-hub/product/om-se051ard)

#### **Repository URL:** https://github.com/NXPPlugNTrust/nano-package/tree/master/examples/se05x_crypto/mcxa153
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-integrating-se05x-to-frdm-mcxa

<!-- dm-mikroe-joystick2click-frdm/. -->
## 76. Demo of Mikroe Joystick2Click in FRDM with CMSIS driver and GPIO adapter<a id="dm-mikroe-joystick2click-frdm"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Demo is an example for Mikroe Joystick 2 Click module in FRDM boards with CMSIS driver and GPIO adapter. 

#### Families:           RW, MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        GPIO, I2C, UART 
#### Categories:         User Interface 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA156](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a144-5-6-a154-5-6-mcus:FRDM-MCXA156)
* [FRDM-MCXN236](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n23x-mcus:FRDM-MCXN236)
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)
* [FRDM-MCXC444](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c444-mcus:FRDM-MCXC444)
* [FRDM-MCXC041](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c041-mcus:FRDM-MCXC041)
* [FRDM-MCXC242](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c242-mcus:FRDM-MCXC242)
* [FRDM-MCXW71](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-w71x-wireless-mcus:FRDM-MCXW71)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mikroe-joystick2click-frdm/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mikroe-joystick2click-frdm

<!-- dm-mikroe-oledbclick-frdm/. -->
## 77. Demo of mikroe oledBclick in FRDM with CMSIS driver and GPIO adapter<a id="dm-mikroe-oledbclick-frdm"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Demo is an example for Mikroe OLED B click module in FRDM boards with CMSIS driver and GPIO adapter. 

#### Families:           RW, MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        GPIO, I2C, UART 
#### Categories:         Graphics, HMI, User Interface 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA156](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a144-5-6-a154-5-6-mcus:FRDM-MCXA156)
* [FRDM-MCXN236](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n23x-mcus:FRDM-MCXN236)
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)
* [FRDM-MCXC444](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c444-mcus:FRDM-MCXC444)
* [FRDM-MCXC041](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c041-mcus:FRDM-MCXC041)
* [FRDM-MCXC242](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c242-mcus:FRDM-MCXC242)
* [FRDM-MCXW71](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-w71x-wireless-mcus:FRDM-MCXW71)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mikroe-oledbclick-frdm/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mikroe-oledbclick-frdm

<!-- dm-mikroe-relay5click-frdm/. -->
## 78. Demo of Mikroe Relay5CLick in FRDM with CMSIS driver and GPIO adapter<a id="dm-mikroe-relay5click-frdm"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Demo is an example for Mikroe Relay 5 click module in FRDM boards usign CMSIS driver for I2C comunication, and GPIO component. 

#### Families:           RW, MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        I2C, GPIO, UART 
#### Categories:         Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA156](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a144-5-6-a154-5-6-mcus:FRDM-MCXA156)
* [FRDM-MCXN236](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n23x-mcus:FRDM-MCXN236)
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)
* [FRDM-MCXC444](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c444-mcus:FRDM-MCXC444)
* [FRDM-MCXC041](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c041-mcus:FRDM-MCXC041)
* [FRDM-MCXC242](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c242-mcus:FRDM-MCXC242)
* [FRDM-MCXW71](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-w71x-wireless-mcus:FRDM-MCXW71)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mikroe-relay5click-frdm/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mikroe-relay5click-frdm

<!-- dm-pca9420uk-evm-pmic-for-low-power-application/. -->
## 79. PMIC for Low Power Applications on FRDM-MCXN947 and MCXA153<a id="dm-pca9420uk-evm-pmic-for-low-power-application"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 The PCA9420 is a highly integrated Power Management IC (PMIC), targeted to provide a full power management solution for low-power microcontroller applications or other similar applications. The device consists of a linear battery charger capable of charging up to 315 mA current. It has an I²C programmable Constant Current (CC) and Constant Voltage (CV) values for flexible configuration. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C 
#### Categories:         Low Power 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [PCA9420UK-EVM](https://mcuxpresso.nxp.com/eb-hub/product/pca9420uk-evm)
* [PCA9421UK-EVM](https://mcuxpresso.nxp.com/eb-hub/product/pca9421uk-evm)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-pca9420uk-evm-pmic-for-low-power-application/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-pca9420uk-evm-pmic-for-low-power-application

<!-- dm-tss-powered-on-device-learning-fan-anomaly-based-on-mcxa156/. -->
## 80. Time Series Studio powered, on-device learning Fan anomaly detection based on FRDM-MCXA156<a id="dm-tss-powered-on-device-learning-fan-anomaly-based-on-mcxa156"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Time Series Studio powered, on-device learning Fan anomaly detection based on FRDM-MCXA156 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY, I2C 
#### Categories:         Anomaly Detection, AI/ML 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA156](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a144-5-6-a154-5-6-mcus:FRDM-MCXA156)

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)
* [ACCEL 4 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/accel 4 click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-tss-powered-on-device-learning-fan-anomaly-based-on-mcxa156/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-tss-powered-on-device-learning-fan-anomaly-based-on-mcxa156

<!-- dm-mcxc444-lcd-and-fxls8974cf-motion-detection/. -->
## 81. MCXC444 LCD display and FXLS8974CF accelerometer motion detection<a id="dm-mcxc444-lcd-and-fxls8974cf-motion-detection"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This example use FRDM-MCXC444 and on-board FXLS8974CF accelerometer to demonstrate autonomous motion detection of motion and direction, also this demo shows the board direction on the on board LCD display. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        DISPLAY, I2C, SENSOR, UART 
#### Categories:         Sensor 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXC444](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c444-mcus:FRDM-MCXC444)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcxc444-lcd-and-fxls8974cf-motion-detection/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mcxc444-lcd-and-fxls8974cf-motion-detection

<!-- dm-wifi-lcd-connect-frdm-mcxn947/. -->
## 82. Wi-Fi connect using LCD interface on FRDM-MCXN947 using Wi-Fi expansion board FRDM-IW416-AW-AM510<a id="dm-wifi-lcd-connect-frdm-mcxn947"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This is a demo example of Wi-Fi connect using LCD interface on FRDM-MCXN947 using Wi-Fi expansion board FRDM-IW416-AW-AM510. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        UART, SDIO, DISPLAY 
#### Categories:         Graphics, RTOS, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [FRDM-IW416-AW-AM51](https://mcuxpresso.nxp.com/eb-hub/product/frdm-iw416-aw-am51)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-wifi-lcd-connect-frdm-mcxn947/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-wifi-lcd-connect-frdm-mcxn947

<!-- dm-mikroe-4x4-key-click-frdm/. -->
## 83. 4x4 Key Click: multi-platform ecosystem.<a id="dm-mikroe-4x4-key-click-frdm"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Demo is an example for MIKROE 4x4 Key Click module in FRDM boards with CMSIS driver and NXP HAL Software. 

#### Families:           RW, MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        GPIO, SPI 
#### Categories:         HMI, Industrial, Tools 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA156](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a144-5-6-a154-5-6-mcus:FRDM-MCXA156)
* [FRDM-MCXN236](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n23x-mcus:FRDM-MCXN236)
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)
* [FRDM-MCXC444](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c444-mcus:FRDM-MCXC444)
* [FRDM-MCXC041](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c041-mcus:FRDM-MCXC041)
* [FRDM-MCXC242](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c242-mcus:FRDM-MCXC242)
* [FRDM-MCXW71](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-w71x-wireless-mcus:FRDM-MCXW71)

#### Expansion boards
* [4x4 Key Click](https://mcuxpresso.nxp.com/eb-hub/product/4x4 key click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mikroe-4x4-key-click-frdm/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mikroe-4x4-key-click-frdm

<!-- dm-mikroe-knob-g-click-frdm/. -->
## 84. Knob G Click: multi-platform ecosystem.<a id="dm-mikroe-knob-g-click-frdm"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Demo is an example for MIKROE Knob G Click module in FRDM boards with CMSIS driver and NXP HAL Software. 

#### Families:           RW, MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        I2C, UART, TIMER, GPIO 
#### Categories:         Industrial, Tools, User Interface 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA156](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a144-5-6-a154-5-6-mcus:FRDM-MCXA156)
* [FRDM-MCXN236](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n23x-mcus:FRDM-MCXN236)
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXC444](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c444-mcus:FRDM-MCXC444)
* [FRDM-MCXC041](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c041-mcus:FRDM-MCXC041)
* [FRDM-MCXC242](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c242-mcus:FRDM-MCXC242)
* [FRDM-MCXW71](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-w71x-wireless-mcus:FRDM-MCXW71)

#### Expansion boards
* [Knob G Click](https://mcuxpresso.nxp.com/eb-hub/product/knob g click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mikroe-knob-g-click-frdm/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-mikroe-knob-g-click-frdm

<!-- dm-ml-sensorless-anomaly-detection/. -->
## 85. FRDM-MCXN947 Sensorless Anomaly Detection for Motor Control System<a id="dm-ml-sensorless-anomaly-detection"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 This demo showcases machine learning anomaly detection in a motor control system with modern GUI and touch controls. The demo showcases integration of many NXP tools. The demo utilizes MCUXpresso SDK for basic drivers, LVGL support for GUI and PMSM motor control algorithms. Using GUI Guider a modern and easy to navigate user interface is developed. Next, the demo incorporates FreeMASTER real time debugging tool to collect datasets using the Machine Learning Universal Datalogger project, which is also available as a standalone project on the Application Code Hub. This dataset can be used to develop a custom anomaly detection model using the Time Series Studio tool which is a part of eIQ® Toolkit. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY, DMA, PWM, TIMER, UART 
#### Categories:         Graphics, HMI, Motor Control, Anomaly Detection, AI/ML, User Interface 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [FRDM-MC-LVPMSM](https://mcuxpresso.nxp.com/eb-hub/product/frdm-mc-lvpmsm)
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-ml-sensorless-anomaly-detection/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-ml-sensorless-anomaly-detection

<!-- doom-mcx/. -->
## 86. Doom-MCX port of popular Doom game to run on NXP MCX microcontrollers<a id="doom-mcx"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 A port of prBoom to the NXP MCXN947 MCU running on top Zephyr RTOS. 

#### Families:           MCX 
#### Toolchains:         GCC, VS Code 
#### Peripherals:        ADC, DISPLAY, DMA, FLASH, GPIO, I2C, PINCTRL 
#### Categories:         Graphics, HMI, RTOS 
#### Application format: Zephyr Project
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/nxphoverGames/doom-mcx/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-doom-mcx

<!-- nxp-demo-experience-demos-list/scripts/machine_learning/dms -->
## 87. i.MX Driver Monitor System<a id="nxp-demo-experience-demos-list_scripts_machine_learning_dms"></a> <a href="#top" style="float:right">⤒</a>

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


#### **Repository URL:** https://github.com/nxp-imx-support/nxp-demo-experience-demos-list/tree/lf-6.6.52_2.2.0/scripts/machine_learning/dms
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-i-mx-dms

<!-- nxp-demo-experience-demos-list/scripts/machine_learning/imx_smart_fitness -->
## 88. i.MX Smart Fitness<a id="nxp-demo-experience-demos-list_scripts_machine_learning_imx_smart_fitness"></a> <a href="#top" style="float:right">⤒</a>

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


#### **Repository URL:** https://github.com/nxp-imx-support/nxp-demo-experience-demos-list/tree/lf-6.6.52_2.2.0/scripts/machine_learning/imx_smart_fitness
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-i-mx-smart-fitness

<!-- nxp-demo-experience-demos-list/scripts/machine_learning/ml_benchmark -->
## 89. i.MX Machine Learning Benchmark Tool<a id="nxp-demo-experience-demos-list_scripts_machine_learning_ml_benchmark"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 ML Benchmark tool allows to easily compare the performance of TensorFlow Lite models running on CPU (Cortex-A) and NPU, without the need to type in any command. 

#### Families:           i.MX 
#### Toolchains:         VS Code 
#### Peripherals:        DISPLAY 
#### Categories:         AI/ML 
#### Application format: Python (Linux)
#### Compatible boards:
* [EVK-MIMX8MP](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-plus-applications-processor:8MPLUSLPD4-EVK)
* [MCIMX93-EVK]()
* [IMX95LPD5EVK-19]()


#### **Repository URL:** https://github.com/nxp-imx-support/nxp-demo-experience-demos-list/tree/lf-6.6.52_2.2.0/scripts/machine_learning/ml_benchmark
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-ml-benchmark

<!-- nxp-demo-experience-demos-list/scripts/machine_learning/nnstreamer/classification -->
## 90. NNStreamer Image Classification<a id="nxp-demo-experience-demos-list_scripts_machine_learning_nnstreamer_classification"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Image Classification showcases the Machine Learning (ML) capabilities of i.MX SoCs by using a Neural Processing Unit (NPU).  

#### Families:           i.MX 
#### Toolchains:         VS Code 
#### Peripherals:        MIPI-CSI, DISPLAY, USB, VIDEO 
#### Categories:         AI/ML, Vision 
#### Application format: Python (Linux)
#### Compatible boards:
* [EVK-MIMX8MM](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-mini-applications-processor:8MMINILPD4-EVK)
* [MEK-MIMX8QM](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-8quadmax-multisensory-enablement-kit-mek:MCIMX8QM-CPU)
* [EVK-MIMX8MP](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-plus-applications-processor:8MPLUSLPD4-EVK)
* [MCIMX93-EVK]()
* [IMX95LPD5EVK-19]()


#### **Repository URL:** https://github.com/nxp-imx-support/nxp-demo-experience-demos-list/tree/lf-6.6.52_2.2.0/scripts/machine_learning/nnstreamer/classification
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-image-classification

<!-- nxp-demo-experience-demos-list/scripts/machine_learning/nnstreamer/detection -->
## 91. NNStreamer Object Detection<a id="nxp-demo-experience-demos-list_scripts_machine_learning_nnstreamer_detection"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Object Detection showcases the Machine Learning (ML) capabilities ofi.MX SoCs by using a Neural Processing Unit (NPU). Object detection is the ML task that detects instances of objects of a certain class within an image. A bounding box and a class label are found for each detected object. 

#### Families:           i.MX 
#### Toolchains:         VS Code 
#### Peripherals:        MIPI-CSI, DISPLAY, USB, VIDEO 
#### Categories:         AI/ML, Vision 
#### Application format: Python (Linux)
#### Compatible boards:
* [EVK-MIMX8MM](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-mini-applications-processor:8MMINILPD4-EVK)
* [MEK-MIMX8QM](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-8quadmax-multisensory-enablement-kit-mek:MCIMX8QM-CPU)
* [EVK-MIMX8MP](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-plus-applications-processor:8MPLUSLPD4-EVK)
* [MCIMX93-EVK]()
* [IMX95LPD5EVK-19]()


#### **Repository URL:** https://github.com/nxp-imx-support/nxp-demo-experience-demos-list/tree/lf-6.6.52_2.2.0/scripts/machine_learning/nnstreamer/detection
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-object-detection

<!-- nxp-demo-experience-demos-list/scripts/machine_learning/selfie_segmenter -->
## 92. Selfie Segmenter<a id="nxp-demo-experience-demos-list_scripts_machine_learning_selfie_segmenter"></a> <a href="#top" style="float:right">⤒</a>

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


#### **Repository URL:** https://github.com/nxp-imx-support/nxp-demo-experience-demos-list/tree/lf-6.6.52_2.2.0/scripts/machine_learning/selfie_segmenter
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-selfie-segmenter

<!-- nxp-demo-experience-demos-list/scripts/multimedia/gstreamer/video_test -->
## 93. i.MX V4L2 Video Test Tool<a id="nxp-demo-experience-demos-list_scripts_multimedia_gstreamer_video_test"></a> <a href="#top" style="float:right">⤒</a>

### Overview
 Voice test shows an example GStreamer video pipeline on screen. 

#### Families:           i.MX 
#### Toolchains:         VS Code 
#### Peripherals:        DISPLAY, VIDEO 
#### Categories:         Graphics, Tools 
#### Application format: Python (Linux)
#### Compatible boards:
* [EVK-MCIMX7ULP](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-7ulp-applications-processor:MCIMX7ULP-EVK)
* [EVK-MIMX8MM](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-mini-applications-processor:8MMINILPD4-EVK)
* [EVK-MIMX8MN](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-nano-applications-processor:8MNANOD4-EVK)
* [MEK-MIMX8QX](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-8quadxplus-multisensory-enablement-kit-mek:MCIMX8QXP-CPU)
* [MEK-MIMX8QM](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-8quadmax-multisensory-enablement-kit-mek:MCIMX8QM-CPU)
* [EVK-MIMX8MP](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-plus-applications-processor:8MPLUSLPD4-EVK)
* [EVK-MIMX8ULP](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-8ulp-evaluation-kit:MCIMX8ULP-EVK)
* [MCIMX93-EVK]()


#### **Repository URL:** https://github.com/nxp-imx-support/nxp-demo-experience-demos-list/tree/lf-6.6.52_2.2.0/scripts/multimedia/gstreamer/video_test
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-video-test

<!-- nxp-demo-experience-demos-list/scripts/multimedia/smart_kitchen -->
## 94. i.MX Smart Kitchen<a id="nxp-demo-experience-demos-list_scripts_multimedia_smart_kitchen"></a> <a href="#top" style="float:right">⤒</a>

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


#### **Repository URL:** https://github.com/nxp-imx-support/nxp-demo-experience-demos-list/tree/lf-6.6.52_2.2.0/scripts/multimedia/smart_kitchen
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=dm-i-mx-smart-kitchen

<!-- edgehog-zephyr-device/samples/edgehog_app -->
## 95. Clea Edgehog IoT devices using Zephyr RTOS<a id="edgehog-zephyr-device_samples_edgehog_app"></a> <a href="#top" style="float:right">⤒</a>

### Overview
Fleet manage your IoT device through opensource Edgehog device management platform. Enable remote updates and system configuration.

#### Families:           i.MX RT 
#### Toolchains:         VS Code 
#### Peripherals:        ETHERNET 
#### Categories:         Cloud Connected Devices, Networking 
#### Application format: Zephyr Project
#### Compatible boards:
* [EVK-MIMXRT1064](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1064-evaluation-kit:MIMXRT1064-EVK)


#### **Repository URL:** https://github.com/edgehog-device-manager/edgehog-zephyr-device/tree/release-0.7/samples/edgehog_app
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=edgehog-iot-devices-using-zephyr-rtos

<!-- astarte-device-sdk-zephyr/samples/astarte_app -->
## 96. Clea Astarte IoT devices using Zephyr RTOS<a id="astarte-device-sdk-zephyr_samples_astarte_app"></a> <a href="#top" style="float:right">⤒</a>

### Overview
Transform your board in an IoT device. Connect to the cloud using Astarte and start transferring data.

#### Families:           i.MX RT 
#### Toolchains:         VS Code 
#### Peripherals:        ETHERNET 
#### Categories:         Cloud Connected Devices 
#### Application format: Zephyr Project
#### Compatible boards:
* [EVK-MIMXRT1064](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1064-evaluation-kit:MIMXRT1064-EVK)


#### **Repository URL:** https://github.com/astarte-platform/astarte-device-sdk-zephyr/tree/release-0.7/samples/astarte_app
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=astarte-iot-devices-using-zephyr-rtos

<!-- dm-wifi-provisioning-using-ble/. -->
## 97. WiFi provisioning using BLE on RT1170 EVKB using Wi-Fi Module Murata 2EL<a id="dm-wifi-provisioning-using-ble"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This is a demo example of Wi-Fi connection using BLE on RT1170 EVKB using Wi-Fi module Murata 2EL.

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        SDIO 
#### Categories:         RTOS, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MIMXRT1170-EVKB](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1170-evaluation-kit:MIMXRT1170-EVKB)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-wifi-provisioning-using-ble/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=wifi-provisioning-using-ble

<!-- dm-knx-iot-examples-on-nxp-mcxw71/. -->
## 98. KNX IoT stack examples running on FRDM-MCXW71<a id="dm-knx-iot-examples-on-nxp-mcxw71"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This repository contains the light switched actuator basic (LSAB) and light switched sensor basic (LSSB) example running on NXP FRDM-MCXW71

#### Families:           MCX 
#### Toolchains:         GCC 
#### Peripherals:        UART 
#### Categories:         Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXW71](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-w71x-wireless-mcus:FRDM-MCXW71)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-knx-iot-examples-on-nxp-mcxw71/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=knx-iot-examples-on-nxp-mcxw71

<!-- dm-pca9422-evb-ultra-low-power-charger-gauge-pmic-demo-app/. -->
## 99. PCA9422: PCA9422 Ultra Low Power Charger and Gauge PMIC for RT5/6/700 demo application on FRDM-MCXN947 and MCXA153 <a id="dm-pca9422-evb-ultra-low-power-charger-gauge-pmic-demo-app"></a> <a href="#top" style="float:right">⤒</a>

### Overview
The PCA9422 is a highly integrated Ultra Low Power Management IC (PMIC), targeted to provide a full power management solution for low power microcontroller applications or other similar applications with small batterie<br />Feature provided:<br />Three Step-Down DC/DC Converters<br />One Buck-Boost Converter<br />Four Low Dropout Regulators ( LDOs )<br />Linear Battery Charger for Charging Single Cell Li-Ion Battery

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C 
#### Categories:         Low Power 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [PCA9422-EVB](https://mcuxpresso.nxp.com/eb-hub/product/pca9422-evb)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-pca9422-evb-ultra-low-power-charger-gauge-pmic-demo-app/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=pca9422-evb-ultra-low-power-charger-gauge-pmic-demo-app

<!-- dm-pca9846pw-ard-ultra-low-voltage-fm-plus-i2c-bus-switch-demo-app/. -->
## 100. PCA9846: Four-Channel Ultra-Low Voltage, Fm+ I2C-Bus Switch with Reset demo application <a id="dm-pca9846pw-ard-ultra-low-voltage-fm-plus-i2c-bus-switch-demo-app"></a> <a href="#top" style="float:right">⤒</a>

### Overview
The PCA9846 is an ultra-low voltage, quad bidirectional translating switch controlled via the I2C-bus. The SCL/SDA upstream pair fans out to four downstream pairs, or channels. Any or all SCx/SDx channels can be selected, determined by the programmable control register. This feature allows multiple devices with the same I2C-bus address to reside on the same bus. The switch device can also separate a heavily loaded I2C-bus into separate bus segments, eliminating the need for a bus buffer.<br />Features Provided :<br /><pre>Ultra-low voltage operation, down to 0.8 V to interface with next-generation CPUs
- 1-of-4 bidirectional translating switch
- Fm+ I2C-bus interface logic; compatible with SMBus standards
- Active LOW reset input
- 2 address pins allowing up to 16 devices on the I2C-bus
- Channel selection via I2C-bus
- Power-up with all switch channels deselected
- Low Ron switches
- Allows voltage level translation between 0.8 V, 1.8 V, 2.5 V and 3.3 V buses
- Reset via I2C-bus software command
- I2C Device ID function
- No glitch on power-up
- Supports hot insertion since all channels are de-selected at </pre>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C 
#### Categories:         Low Power 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)
* [FRDM-MCXC444](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c444-mcus:FRDM-MCXC444)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-pca9846pw-ard-ultra-low-voltage-fm-plus-i2c-bus-switch-demo-app/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=pca9846pw-ard-ultra-low-voltage-fm-plus-i2c-bus-switch-demo-app

<!-- dm-pcal6416aev-low-voltage-translating-16-bit-i2c-bus-smbus-io-expander/. -->
## 101. PCAL6416AEV-ARD Low-Voltage Translating 16-Bit I²C-Bus/SMBus I/O Expander<a id="dm-pcal6416aev-low-voltage-translating-16-bit-i2c-bus-smbus-io-expander"></a> <a href="#top" style="float:right">⤒</a>

### Overview
The PCAL6416AEV-ARD Arduino Shield allows easy integration with Arduino EVKs to evaluate 16-bit general-purpose I/O expander features for interfacing to sensors, push buttons, keypad, etc. A graphical interface allows the user to easily explore the different functions of the GPIO expander to create an evaluation system.<ul><li>I/O connector for external access to IC input-output pins</li><li>Eight user switches connected to I/O pins of the IC</li><li>Eight user LEDs connected to I/O pins of the IC</li><li>Equipped with Arduino Uno R3 port for direct connection with Arduino devices</li><li>Fully compliant with IMXRT1050 EVK board</li><li>Fully compliant with LPCXpresso55S69 dev. board</li><li>Compliant with i.MX Mini LPDDR4 EVK board.</li></ul>

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C 
#### Categories:         Industrial, User Interface 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)
* [FRDM-MCXC444](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c444-mcus:FRDM-MCXC444)

#### Expansion boards
* [PCAL6416AEV-ARD](https://mcuxpresso.nxp.com/eb-hub/product/pcal6416aev-ard)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-pcal6416aev-low-voltage-translating-16-bit-i2c-bus-smbus-io-expander/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=pcal6416aev-low-voltage-translating-16-bit-i2c-bus-smbus-io-expander

<!-- dm-mcxn947-remote-io-with-nafe13388/. -->
## 102. NAFE13388 Universal Analog Sensing Module with Wired Connectivity<a id="dm-mcxn947-remote-io-with-nafe13388"></a> <a href="#top" style="float:right">⤒</a>

### Overview
Software-configurable analog input solution for high-precision sensing with wired connectivity via CAN FD, Ethernet and USB

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, GCC 
#### Peripherals:        ETHERNET, USB, CAN 
#### Categories:         Sensor, Industrial, Analog Front End 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [NAFE13388-UIM](https://mcuxpresso.nxp.com/eb-hub/product/nafe13388-uim)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcxn947-remote-io-with-nafe13388/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=mcxn947-remote-io-with-nafe13388

<!-- dm-a30-mcxa153-ecc-example/. -->
## 103. Integrating EdgeLock® A30 secure authenticator to FRDM-MCXA153 board<a id="dm-a30-mcxa153-ecc-example"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This
demo project provides a detailed information on how to integrate the EdgeLock®
A30 Secure Authenticator into the FRDM-MCXA153 development board. The example
code shows how to use A30 to generate a 256-bit ECC key pair and perform an ECDSA
sign/verify operation. 

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C 
#### Categories:         Security 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)

#### Expansion boards
* [EdgeLock A30 Secure Authenticator](https://mcuxpresso.nxp.com/eb-hub/product/edgelock a30 secure authenticator)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-a30-mcxa153-ecc-example/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=a30-mcxa153-ecc-example

<!-- dm-kw45-secure-boot-scripts/. -->
## 104. KW45: Secure boot scripts based on spsdk<a id="dm-kw45-secure-boot-scripts"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This is scripts package is used for KW45 secure boot, including generating keys, programming fuse, signing image, generating sb3 file, debugging authentication, advancing lifecycle.<br /><a href="https://spsdk.readthedocs.io/en/latest/">https://spsdk.readthedocs.io/</a>

#### Families:           MCX, KW45 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        UART, Bluetooth 
#### Categories:         Secure Provisioning, Security, Wireless Connectivity, Tools 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [KW45B41Z-EVK]()
* [KW45B41Z-LOC]()
* [FRDM-MCXW71](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-w71x-wireless-mcus:FRDM-MCXW71)
* [MCX-W71-EVK]()


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-kw45-secure-boot-scripts/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=kw45-secure-boot-scripts

<!-- dm-ip-frdmmcxa153-oled-motor-graph-usb/. -->
## 105. Motor RPM Grapher in OLED with USB<a id="dm-ip-frdmmcxa153-oled-motor-graph-usb"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This demo is part of Industrial Panel V2, the MCXA153 have usb connection with main panel and uses the mikroe OledBClick module to graph RPM in real time.

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        GPIO, I2C, USB 
#### Categories:         Graphics, HMI, Industrial 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)

#### Expansion boards
* [OLED B click](https://mcuxpresso.nxp.com/eb-hub/product/oled b click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-ip-frdmmcxa153-oled-motor-graph-usb/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=ip-frdmmcxa153-oled-motor-graph-usb

<!-- dm-p3h2x4x-i3c-hub-demo-application/. -->
## 106. P3H2X4X : I3C hub demo application on FRDM MCXN947 and MCXA153<a id="dm-p3h2x4x-i3c-hub-demo-application"></a> <a href="#top" style="float:right">⤒</a>

### Overview
I3C-Hub connects to a host CPU via I3C/I2C/SMBus bus on one side and connect to multiple peripheral devices on the other side. The hub device generally have two controller ports and up to eight target ports to expand bus connectivity to multiple devices

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, I3C 
#### Categories:         Bridge 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-p3h2x4x-i3c-hub-demo-application/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=p3h2x4x-i3c-hub-demo-application

<!-- dm-nxp-rw612-gui-guider-ble/. -->
## 107. FRDM-RW612 GUI Guider integration on Bluetooth LE example<a id="dm-nxp-rw612-gui-guider-ble"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This software shows how to integrate GUI Guider and LVGL code in a Bluetooth LE example.

#### Families:           RW 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY 
#### Categories:         Graphics, HMI, RTOS, Wireless Connectivity, User Interface 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-nxp-rw612-gui-guider-ble/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=nxp-rw612-gui-guider-ble

<!-- dm-ip-frdmmcxc444-rotary-motor-update-usb/. -->
## 108. Motor RPM Control with KnobGClick and RPM Display in Real Time with USB<a id="dm-ip-frdmmcxc444-rotary-motor-update-usb"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This demo is part of Industrial Panel V2, the MCXC444 have usb connection with main panel and uses the mikroe KnobGClick module for change RPM and LCD for show real time RPM.

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        GPIO, I2C, USB 
#### Categories:         HMI, Industrial, User Interface 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXC444](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c444-mcus:FRDM-MCXC444)

#### Expansion boards
* [Knob G Click](https://mcuxpresso.nxp.com/eb-hub/product/knob g click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-ip-frdmmcxc444-rotary-motor-update-usb/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=ip-frdmmcxc444-rotary-motor-update-usb

<!-- dm-ip-frdmmcxc242-rotary-motor-update-usb/. -->
## 109. Motor RPM Control with KnobGClick with USB<a id="dm-ip-frdmmcxc242-rotary-motor-update-usb"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This demo is part of Industrial Panel V2, the MCXC242 have usb connection with main panel and uses the mikroe KnobGClick module for change RPM.

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        GPIO, I2C, USB 
#### Categories:         HMI, Industrial, User Interface 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXC444](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c444-mcus:FRDM-MCXC444)

#### Expansion boards
* [Knob G Click](https://mcuxpresso.nxp.com/eb-hub/product/knob g click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-ip-frdmmcxc242-rotary-motor-update-usb/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=ip-frdmmcxc242-rotary-motor-update-usb

<!-- dm-frdmrw612-sensors-over-wifi/. -->
## 110. FRDM-RW612 Sensors over Wi-Fi with http server<a id="dm-frdmrw612-sensors-over-wifi"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This demo shows how to use and send the data from the built-in temperature sensor in the FRDM-RW612 board as well as the Accel 4 click and the HeartRate 4 click mikro-e boards over wifi to an http server that displays their information.

#### Families:           RW 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        GPIO, I2C, SENSOR, UART, Wi-Fi 
#### Categories:         Sensor, RTOS, Wireless Connectivity, Tools 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:

#### Expansion boards
* [HEART RATE 4 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/heart rate 4 click)
* [ACCEL 4 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/accel 4 click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-frdmrw612-sensors-over-wifi/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=frdmrw612-sensors-over-wifi

<!-- dm-eiq-genai-flow-demonstrator/. -->
## 111. eIQ GenAI Flow Demonstrator<a id="dm-eiq-genai-flow-demonstrator"></a> <a href="#top" style="float:right">⤒</a>

### Overview
The eIQ GenAI Flow Demonstrator is a Conversational AI Pipeline application designed for NXP i.MX95 devices. This Demonstrator Demo enables t following pipeline components:<br /><br />    VIT: "Hey NXP" Wake word, or custom<br />    ASR: Whisper Small English, moonshine-tiny, moonshine-base<br />    RAG: Embedding model + example database<br />    LLM: Danube<br />    TTS: 16kHz English

#### Families:           i.MX 
#### Toolchains:         VS Code 
#### Peripherals:        ADC, DAC, I2S, SDIO, UART 
#### Categories:         Voice, Audio, AI/ML 
#### Application format: Python (Linux)
#### Compatible boards:
* [EVK-MIMX8MM](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-mini-applications-processor:8MMINILPD4-EVK)
* [EVK-MIMX8MN](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-nano-applications-processor:8MNANOD4-EVK)
* [EVK-MIMX8MQ](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-applications-processor:MCIMX8M-EVK)
* [EVK-MIMX8MP](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-plus-applications-processor:8MPLUSLPD4-EVK)
* [MCIMX93-EVK]()
* [MCIMX93-QSB]()
* [IMX95LPD5EVK-19]()
* [IMX943-EVK]()
* [IMX95LP4XEVK-15]()
* [FRDM-IMX95]()


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-eiq-genai-flow-demonstrator/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=llm-pipeline-demonstrator

<!-- dm-nxp-k32w061-dk6-door-lock-and-lighting-app-matter-application/. -->
## 112. Door Lock Cluster integration on a Lighting App Matter Application using K32W061 DK6<a id="dm-nxp-k32w061-dk6-door-lock-and-lighting-app-matter-application"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This example demo describes the process of adding and executing a Door Lock Cluster to an already existing Matter Lighting App running on the NXP K32W061 DK6 development kit. It highlights the changes added to the Matter Lighting application, while also showing the required cluster configuration using the ZAP Platform.  Both examples are based on the <a href="https://github.com/projectchip/connectedhomeip/tree/v1.4.0.0">https://github.com/projectchip/connectedhomeip/tree/v1.4.0.0</a> repository, so the user will need to go over the whole process of cloning and setting up the environment as described in the original README. This demo only contains the folders and files that must replace the original ones from the lighting app example. <br />

#### Families:           K32W 
#### Toolchains:         GCC 
#### Peripherals:        Bluetooth, USB 
#### Categories:         Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-nxp-k32w061-dk6-door-lock-and-lighting-app-matter-application/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=nxp-k32w061-dk6-door-lock-and-lighting-app-matter-application

<!-- dm-pcal9722hn-22-bit-spi-gpio-expander/. -->
## 113. PCAL9722: 22-Bit SPI I/O Expander with Agile I/O Features<a id="dm-pcal9722hn-22-bit-spi-gpio-expander"></a> <a href="#top" style="float:right">⤒</a>

### Overview
Ultra low-voltage translating 22-bit SPI I/O expander with Agile I/O features, interrupt output and reset evaluation board

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        GPIO, SPI 
#### Categories:         Industrial 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)
* [FRDM-MCXC444](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c444-mcus:FRDM-MCXC444)

#### Expansion boards
* [PCAL9722HN](https://mcuxpresso.nxp.com/eb-hub/product/pcal9722hn)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-pcal9722hn-22-bit-spi-gpio-expander/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=pcal9722hn-22-bit-spi-gpio-expander

<!-- meta-smart-appliance/. -->
## 114. i.MX93 Smart Appliance for MATTER<a id="meta-smart-appliance"></a> <a href="#top" style="float:right">⤒</a>

### Overview
i.MX93 Smart Appliance Demo <br />Features:<br /><ul><li>Board level power &lt; 400mW in DSM</li><li>Fast boot from power on to GUI </li><li>GUI design by LVGL_V8.3.5</li><li>Vision inference
for recognize the fruits and check
freshness by NPU </li><li>MATTER Controller to control smart device</li><li>Temperature sensor (Zigbee)</li><li>Bulb control (Zigbee/WIFI)</li><li>Low power voice wakeup (wakeup ok, but high power)</li><li>VIT for voice control</li><li>External USB current metering for
board power measurement</li></ul>

#### Families:           i.MX 
#### Toolchains:         GCC 
#### Peripherals:        802.15.4, Bluetooth, Wi-Fi, USB 
#### Categories:         Low Power, AI/ML, Wireless Connectivity, Vision 
#### Application format: Yocto Project
#### Compatible boards:
* [MCIMX93-QSB]()


#### **Repository URL:** https://github.com/nxp-imx-support/meta-smart-appliance/tree/Q2_release
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=short-title-i-mx93-smart-appliance

<!-- dm-pca9958hn-led-driver-with-spi-demo-app/. -->
## 115. 24-Channel SPI Serial Bus 63 mA / 5.5 V Constant-Current LED Driver<a id="dm-pca9958hn-led-driver-with-spi-demo-app"></a> <a href="#top" style="float:right">⤒</a>

### Overview
The PCA9958 is a 24-channel SPI serial bus 63 mA LED driver with a supply voltage range of 2.7 V to 5.5 V. This device is optimized for dimming and blinking RGBA LEDs.

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        SPI 
#### Categories:         User Interface 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)
* [FRDM-MCXC444](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c444-mcus:FRDM-MCXC444)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-pca9958hn-led-driver-with-spi-demo-app/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=pca9958hn-led-driver-with-spi-demo-app

<!-- npa-vee-rw612/. -->
## 116. NXP Platform Accelerator for RW612 Freedom<a id="npa-vee-rw612"></a> <a href="#top" style="float:right">⤒</a>

### Overview
NXP Platform Accelerator provides a development environment to run virtualised applications developed in Java. It is built upon MicroEJ technology.<br />This release runs on FRDM-RW612 with an LCD_PAR_S035 display panel.<br />This implementation supports:<br /><ul><li>Wi-Fi 6 connectivity </li><li>Display enablement through LCD integration</li></ul>

#### Families:           RW 
#### Toolchains:         GCC, VS Code 
#### Peripherals:        Wi-Fi, DISPLAY, ETHERNET, PINCTRL, UART 
#### Categories:         Security, RTOS, Networking, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/nxp-mcuxpresso/npa-vee-rw612/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=rw612-microej-vee-port-wifi

<!-- nxp-vee-mcxn947-frdm/. -->
## 117. NXP Platform Accelerator for MCXN947 Freedom Board<a id="nxp-vee-mcxn947-frdm"></a> <a href="#top" style="float:right">⤒</a>

### Overview
NXP Platform Accelerator provides a development environment to run
virtualized applications developed in Java. It is built upon MicroEJ
technology.

This release runs on FRDM-MCXN947 with an LCD_PAR_S035 display panel.

#### Families:           MCX 
#### Toolchains:         GCC, VS Code 
#### Peripherals:        DISPLAY, ETHERNET, VIDEO, UART 
#### Categories:         Graphics, AI/ML, Security, RTOS, Networking, User Interface 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [LCD-PAR-S035](https://mcuxpresso.nxp.com/eb-hub/product/lcd-par-s035)

#### **Repository URL:** https://github.com/nxp-mcuxpresso/nxp-vee-mcxn947-frdm/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=nxp-platform-accelerator-for-mcxn947-freedom-board

<!-- nxp-vee-imxrt595-evk/. -->
## 118. NXP Platform Accelerator for i.MXRT595 EVK<a id="nxp-vee-imxrt595-evk"></a> <a href="#top" style="float:right">⤒</a>

### Overview
NXP Platform Accelerator provides a development environment to run
virtualized applications developed in Java. It is built upon MicroEJ
technology.

This release runs on EVK-MIMXRT595 with an <a href="https://www.nxp.com/part/G1120B0MIPI#/">G1120B0MIPI</a> display panel.

#### Families:           i.MX RT 
#### Toolchains:         GCC, VS Code 
#### Peripherals:        UART, VIDEO, DISPLAY 
#### Categories:         AI/ML, Security, RTOS, User Interface 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [EVK-MIMXRT595](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt595-evaluation-kit:MIMXRT595-EVK)

#### Expansion boards
* [G1120B0MIPI](https://mcuxpresso.nxp.com/eb-hub/product/g1120b0mipi)

#### **Repository URL:** https://github.com/nxp-mcuxpresso/nxp-vee-imxrt595-evk/tree/round
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=nxp-platform-accelerator-for-i-mxrt595-evk

<!-- nxp-vee-imxrt1170-evk/. -->
## 119. NXP Platform Accelerator for i.MXRT1170 EVK<a id="nxp-vee-imxrt1170-evk"></a> <a href="#top" style="float:right">⤒</a>

### Overview
NXP Platform Accelerator provides a development environment to run
virtualized applications developed in Java. It is built upon MicroEJ
technology.

This release runs on FRDM-RW612 with an LCD_PAR_S035 display panel.

#### Families:           i.MX RT 
#### Toolchains:         GCC, VS Code 
#### Peripherals:        DISPLAY, ETHERNET, UART, VIDEO 
#### Categories:         Graphics, AI/ML, RTOS, Networking, User Interface 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MIMXRT1170-EVKB](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1170-evaluation-kit:MIMXRT1170-EVKB)

#### Expansion boards
* [RK055HDMIPI4MA0](https://mcuxpresso.nxp.com/eb-hub/product/rk055hdmipi4ma0)

#### **Repository URL:** https://github.com/nxp-mcuxpresso/nxp-vee-imxrt1170-evk/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=nxp-platform-accelerator-for-i-mxrt1170-evk

<!-- dm-low-power-wireless-sensors-examples-for-mcxw23/. -->
## 120. Low-Power Wireless Sensors Examples for MCXW23<a id="dm-low-power-wireless-sensors-examples-for-mcxw23"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This demo project provides low-power sensors examples ported on FRDM-MCXW23. Additionally, the project contains several demo applications to showcase how to configure an accelerometer, magnetic switch sensor and pressure/altimeter sensor in various modes.

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE, VS Code 
#### Peripherals:        I2C, Bluetooth 
#### Categories:         Low Power, Sensor, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXW23]()

#### Expansion boards
* [FRDMSTBC-P3115](https://mcuxpresso.nxp.com/eb-hub/product/frdmstbc-p3115)
* [FRDM-STBI-NMH1000](https://mcuxpresso.nxp.com/eb-hub/product/frdm-stbi-nmh1000)
* [HALL SWITCH 3 CLICK](https://mcuxpresso.nxp.com/eb-hub/product/hall switch 3 click)
* [ACCEL PRESSURE CLICK](https://mcuxpresso.nxp.com/eb-hub/product/accel pressure click)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-low-power-wireless-sensors-examples-for-mcxw23/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=low-power-sensors-examples-for-mcxw23

<!-- dm-https-lcd-led-demo/. -->
## 121. HTTPS LCD LED Demo<a id="dm-https-lcd-led-demo"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This is a demo example of HTTPS client-server communication using LCD interface on FRDM-MCXN947 using Wi-Fi expansion board FRDM-IW416-AW-AM510.

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        DISPLAY, Wi-Fi, SDIO 
#### Categories:         Touch Sensing, RTOS, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [FRDM-IW416-AW-AM510](https://mcuxpresso.nxp.com/eb-hub/product/frdm-iw416-aw-am510)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-https-lcd-led-demo/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=https-lcd-led-demo

<!-- dm-wifi-set-up-ping/. -->
## 122. Wi-Fi Scan and Connectivity Demo on RW612BGA<a id="dm-wifi-set-up-ping"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This is a demo example of Wi-Fi scan, connect and ping with nearby access point using RW612BGA.

#### Families:           RW 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        SDIO, Wi-Fi 
#### Categories:         RTOS, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [RD-RW612-BGA]()


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-wifi-set-up-ping/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=wifi-set-up-ping

<!-- dm-mikroe-oled-c-click-display-frdm/. -->
## 123. Demo of MikroE Oled C Click display in FRDM-MCX with CMSIS driver and GPIO adapter<a id="dm-mikroe-oled-c-click-display-frdm"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This demo uses MikroE Oled C Click display with FRDM MCX boards using SPI CMSIS driver and GPIO component

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        GPIO, SPI, DISPLAY 
#### Categories:         Graphics 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXA156](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a144-5-6-a154-5-6-mcus:FRDM-MCXA156)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mikroe-oled-c-click-display-frdm/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=mikroe-oled-c-click-display-frdm

<!-- app-network-ml/. -->
## 124. DeepPacket: Encrypted network packets classification system<a id="app-network-ml"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This is an encrypted traffic packets classification demo, which can tell us which service types are being carried by passing packets. Currently supported categories are file transfer, Web browsing, VoIP, Email and Microsoft Office.

#### Families:           i.MX 
#### Toolchains:         VS Code 
#### Peripherals:        ETHERNET 
#### Categories:         AI/ML, Networking 
#### Application format: Python (Linux)
#### Compatible boards:
* [MCIMX93-EVK]()
* [IMX95LPD5EVK-19]()
* [MCIMX93AUTO-EVK]()


#### **Repository URL:** https://github.com/nxp-imx-support/app-network-ml/tree/deepPacket
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=deeppacket

<!-- dm-pcal6408a-8-bit-i2c-gpio-expander/. -->
## 125. Low-Voltage Translating, 8-Bit I²C-Bus/SMBus I/O Expander<a id="dm-pcal6408a-8-bit-i2c-gpio-expander"></a> <a href="#top" style="float:right">⤒</a>

### Overview
The PCAL6408A is an 8-bit general purpose I/O expander that provides remote I/O expansion for many microcontroller families via the I²C-bus interface.

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        SPI, GPIO, I2C, DMA 
#### Categories:         Low Power, Industrial 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)
* [FRDM-MCXC444](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-c444-mcus:FRDM-MCXC444)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-pcal6408a-8-bit-i2c-gpio-expander/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=pcal6408a-8-bit-i2c-gpio-expander

<!-- dm-pct2075dp-ard-temperature-sensor/. -->
## 126. I²C-Bus , 1 Degree C Accuracy, Digital Temperature Sensor <a id="dm-pct2075dp-ard-temperature-sensor"></a> <a href="#top" style="float:right">⤒</a>

### Overview
The PCT2075 is a temperature-to-digital converter featuring ±1 °C accuracy over -25 °C<br />
to +100 °C range. It uses an on-chip band gap temperature sensor and Sigma-Delta Ato-<br />
D conversion technique with an overtemperature detection output

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C 
#### Categories:         Sensor 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-pct2075dp-ard-temperature-sensor/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=pct2075dp-ard-temperature-sensor

<!-- dm-matter-secure-lock-on-rw612/. -->
## 127. Matter EdgeLock 2GO secure lock example running on RW612<a id="dm-matter-secure-lock-on-rw612"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This is a demo application run on the FRDM-RW612 board, which provides an example on how to securely provision a Matter device using the EdgeLock 2GO service.

#### Families:           RW 
#### Toolchains:         GCC 
#### Peripherals:        Wi-Fi, 802.15.4, Bluetooth, UART 
#### Categories:         Security, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-matter-secure-lock-on-rw612/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=matter-secure-lock-on-rw612

<!-- dm-ble-throughput-measurement-rt1170/. -->
## 128. BLE throughput measurement on RT1170 EVKB + IW612<a id="dm-ble-throughput-measurement-rt1170"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This application demonstrates BLE Throughput measurement on RT1170 using wireless module IW612.

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        Bluetooth 
#### Categories:         Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MIMXRT1170-EVKB](https://www.nxp.com/design/design-center/development-boards-and-designs/i-mx-evaluation-and-development-boards/i-mx-rt1170-evaluation-kit:MIMXRT1170-EVKB)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-ble-throughput-measurement-rt1170/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=ble-throughput-rt1170-evkb

<!-- dm-p3t1035xuk-p3t2030xuk-temperature-sensor-i2c-3c-bus-demo-app/. -->
## 129. P3T1035xUK - P3T2030xUK - I3C, I2C-bus, 0.5 °C accuracy, digital temperature sensor<a id="dm-p3t1035xuk-p3t2030xuk-temperature-sensor-i2c-3c-bus-demo-app"></a> <a href="#top" style="float:right">⤒</a>

### Overview
The <a href="https://www.nxp.com/products/P3T1035xUK">P3T1035xUK</a> or <a href="https://www.nxp.com/products/P3T2030xUK">P3T2030xUK</a> is a temperature-to-digital converter from -40 °C to +125 °C range. It uses an on-chip band gap temperature sensor and A-to-D conversion technique with an overtemperature detection.

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I3C, I2C 
#### Categories:         Sensor 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-p3t1035xuk-p3t2030xuk-temperature-sensor-i2c-3c-bus-demo-app/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=p3t1035xuk-p3t2030xuk-temperature-sensor-i2c-3c-bus-demo-app

<!-- dm-p3t175xdp-i2c-13c-temperature-sensor-demo-app/. -->
## 130. I3C/I²C-Bus ±0.5 °C Accurate Digital Temperature Sensor with over temperature detection<a id="dm-p3t175xdp-i2c-13c-temperature-sensor-demo-app"></a> <a href="#top" style="float:right">⤒</a>

### Overview
P3T1755DP is a ±0.5°C accurate temperature-to-digital converter with a -40 °C to +125 °C range. It uses an on-chip band gap temperature sensor and A-to-D conversion technique with overtemperature detection which can be configured for different operation conditions like continues conversion, one-shot mode or shutdown mode.<br /><br />

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, I3C 
#### Categories:         Sensor 
#### Application format: CMSIS Pack
#### Compatible boards:
* [FRDM-MCXA153](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-a14x-a15x-mcus:FRDM-MCXA153)
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-p3t175xdp-i2c-13c-temperature-sensor-demo-app/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=p3t175xdp-i2c-13c-temperature-sensor-demo-app

<!-- dm-imx943-netc-control-and-sharing-between-m33s-acore/. -->
## 131. NETC: Ethernet Switch Control on M33 with Management Port Sharing via VSIs with A-cores<a id="dm-imx943-netc-control-and-sharing-between-m33s-acore"></a> <a href="#top" style="float:right">⤒</a>

### Overview
<strong>NETC switch control PoC</strong> is an application designed to demonstrate the functionality of the NETC switch on the iMX943 platform.<br />It also showcases the <strong>PCIe SR-IOV</strong> capabilities of NETC by sharing the host <strong>ENETC3</strong>, which is connected to the switch management port, with the A-cores through <strong>Virtual Station Interfaces (VSIs)</strong>.The switch is configured using the <strong>MCU SDK driver API</strong>.<br />A <strong>command-line interface (CLI)</strong> is included, offering a set of commands to enable various switch features. Additional commands can be added to extend support for other NETC switch capabilities.The application uses <strong>FreeRTOS tasks</strong> to handle multiple operations in parallel, including:<ul><li>CLI command processing</li><li>RPMSG communication for PCIe virtualization</li><li>PSI-VSI messaging</li></ul>

#### Families:           i.MX 
#### Toolchains:         IAR, GCC 
#### Peripherals:        ETHERNET 
#### Categories:         Industrial, Time Sensitive Networking, Networking 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [IMX943-EVK]()


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-imx943-netc-control-and-sharing-between-m33s-acore/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=imx943-netc-control-and-sharing-between-m33s-acore

<!-- dm-mc-pmsm-triple-mcxa34x/. -->
## 132.  MCXA34X  triple motor control demo using HVP board<a id="dm-mc-pmsm-triple-mcxa34x"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This demo describes the implementation of sensorless triple motor FOC on NXP MCXA346 MCU. Application note AN14805

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        ADC, PWM, UART 
#### Categories:         Motor Control 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [HVP-MC3PH-LITE]()


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mc-pmsm-triple-mcxa34x/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=hvp-mcxa34x-3mc

<!-- dm-http-client-get-and-post-json-data/. -->
## 133. HTTP Client Get and Post JSON Data<a id="dm-http-client-get-and-post-json-data"></a> <a href="#top" style="float:right">⤒</a>

### Overview
The HTTP(S) client JSON demo application demonstrates how to perform GET and POST requests to a remote API endpoint, handling JSON data payloads over both non-secure (HTTP) and secure (HTTPS) channels.

#### Families:           i.MX RT 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        Wi-Fi 
#### Categories:         Security, RTOS, Networking, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [MIMXRT1060-EVKC]()

#### Expansion boards
* [IW612 - muRata Type-2EL Module](https://mcuxpresso.nxp.com/eb-hub/product/iw612 - murata type-2el module)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-http-client-get-and-post-json-data/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=http-client-get-and-post-json-data

<!-- dm-wireless-rf-test-mode-demo/. -->
## 134. Wireless RFTM Application for Performance Testing of RW612 board<a id="dm-wireless-rf-test-mode-demo"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This software demonstrates a Custom Wireless RF Test Mode (RFTM) application running on an NXP development board.  <br />
Upon powering the board, it starts in Access Point (AP) mode, allowing configuration via a web interface.  <br />
Users can connect to the AP, enter configuration commands one at a time, and start RFTM mode for wireless testing.  <br />
The device logs results in flash memory, which can be retrieved later by reconnecting to the AP and using the provided "Read the Results" feature.  <br />
This example is useful for validating wireless performance, range, and stability in custom RF test scenarios. 

#### Families:           RW 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        Wi-Fi, Bluetooth 
#### Categories:         Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [RD-RW612-BGA]()


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-wireless-rf-test-mode-demo/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=wireless-rf-test-mode-demo

<!-- dm-loc-apps-kw47/. -->
## 135. demo project to use the module sCan<a id="dm-loc-apps-kw47"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This is demo project about how to use the module sCan. sCan is a middleware software used to simplify CAN communication, it is easy to configure and provides simple sending and receiving functions and the format for transmitting data was specified. It has some defined commands such as reset, data transmission, OTA, Bluetooth settings, the users can extend these commands according to your needs. 

#### Families:           KW45 
#### Toolchains:         IAR 
#### Peripherals:        Bluetooth, CAN, GPIO 
#### Categories:         Low Power, RTOS, Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [KW47-EVK]()
* [KW47-LOC]()


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-loc-apps-kw47/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=loc-apps-kw47

<!-- dm-ble-fsci-host-application/. -->
## 136. Bluetooth LE FSCI Host Application running on FRDM-MCXN947 and MCXW236B-Click Board<a id="dm-ble-fsci-host-application"></a> <a href="#top" style="float:right">⤒</a>

### Overview
The Bluetooth LE FSCI Host application demonstrates a host-side implementation for the Health Thermometer use case. It is designed to work alongside the Bluetooth LE FSCI Blackbox application, which runs on platforms such as the MCXW236 Click Board, FRDM-MCXW236, or other compatible Bluetooth LE wireless MCUs. 

#### Families:           MCX 
#### Toolchains:         VS Code 
#### Peripherals:        UART, TIMER, Bluetooth, CLOCKS, GPIO 
#### Categories:         Wireless Connectivity 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)
* [FRDM-MCXW7X]()
* [FRDM-MCXW23]()


#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-ble-fsci-host-application/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=ble-fsci-host-application

<!-- nxp-demo-experience-demos-list/scripts/machine_learning/low_power_ml -->
## 137. i.MX93 Low Power Machine Learning<a id="nxp-demo-experience-demos-list_scripts_machine_learning_low_power_ml"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This Low Power Machine Learning (ML) application showcases the i.MX 93's machine learning capabilities in low power use case by using Cortex-M33 core to run ML model inference with tflite-micro framework. When running the application, the Cortex-A55 core, which runs Linux, will be put into suspend mode to save power consumption. NPU is not used in this application for the same reason.

#### Families:           i.MX 
#### Toolchains:         GCC 
#### Peripherals:        SAI 
#### Categories:         Low Power, Audio, AI/ML 
#### Application format: Python (Linux)
#### Compatible boards:
* [MCIMX93-EVK]()


#### **Repository URL:** https://github.com/nxp-imx-support/nxp-demo-experience-demos-list/tree/lf-6.12.3_1.0.0/scripts/machine_learning/low_power_ml
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=i-mx93-low-power-ml

<!-- dm-mcxn947-click-shield-ping-pong-game/. -->
## 138. Interactive Ping Pong Game Demo Using the MCXN947 Click Shield with OLED C Display and Dual Joystick Click Boards<a id="dm-mcxn947-click-shield-ping-pong-game"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This application showcases the MCXN947 MCU integrated with the MikroE Click Shield, featuring three Click Board slots. The demo utilizes an OLED C Click display and two Joystick Click Boards, with MCXN947 pins configured to route signals precisely to each slot. The final implementation delivers an interactive ping pong game, where players control paddles using the joysticks and view gameplay on the OLED screen. This project highlights the MCXN947’s flexibility in handling multiple peripherals and provides a fun, hands-on example of embedded graphics and input handling using NXP’s development ecosystem.

#### Families:           MCX 
#### Toolchains:         MCUXpresso IDE 
#### Peripherals:        I2C, SPI 
#### Categories:         Graphics 
#### Application format: Project File (MCUX/MDK/IAR)
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)

#### Expansion boards
* [Click Shield for FRDM-MCXN947](https://mcuxpresso.nxp.com/eb-hub/product/click shield for frdm-mcxn947)

#### **Repository URL:** https://github.com/NXP-APPCODEHUB/dm-mcxn947-click-shield-ping-pong-game/tree/main
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=mcxn947-click-shield-ping-pong-game

<!-- nxp-appcodehub/dm-ble-cloud -->
## 139. Golioth Bluetooth Data to the Cloud using Pouch<a id="nxp-appcodehub_dm-ble-cloud"></a> <a href="#top" style="float:right">⤒</a>

### Overview
This is a standalone repository with the Pouch BLE GATT example. It also requires a Click Weather board to demonstrate how to create a Pouch-base application and send up data on the BLE GATT transport.

#### Families:           MCX 
#### Toolchains:         VS Code 
#### Peripherals:        Bluetooth, I2C, SENSOR, Wi-Fi, ETHERNET 
#### Categories:         Secure Provisioning, Sensor, Cloud Connected Devices, Networking, Wireless Connectivity 
#### Application format: Zephyr Project
#### Compatible boards:
* [FRDM-MCXW71](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-w71x-wireless-mcus:FRDM-MCXW71)

#### Expansion boards
* [Weather Click](https://mcuxpresso.nxp.com/eb-hub/product/weather click)

#### **Repository URL:** https://github.com/golioth/nxp-appcodehub/tree/main/dm-ble-cloud
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=bluetooth-pouch-standalone-frdm-mcxw71

<!-- nxp-appcodehub/dm-wolfssl-tls-hello-server-pqc-with-zephyr -->
## 140. wolfSSL TLSv1.3 Hello Server Doing Post-Quantum Cryptography using Zephyr RTOS<a id="nxp-appcodehub_dm-wolfssl-tls-hello-server-pqc-with-zephyr"></a> <a href="#top" style="float:right">⤒</a>

### Overview
It starts with running our benchmarks for the wolfCrypt library and getting performance numbers for all enable algorithms which in this case includes ML-KEM and ML-DSA. Once the benchmarks are done, a TLS 1.3 server is started. Importantly, this server is configured to support the post-quantum algorithms ML-KEM and ML-DSA.

#### Families:           MCX 
#### Toolchains:         VS Code 
#### Peripherals:        ETHERNET 
#### Categories:         Security 
#### Application format: Zephyr Project
#### Compatible boards:
* [FRDM-MCXN947](https://www.nxp.com/design/design-center/development-boards-and-designs/general-purpose-mcus/frdm-development-board-for-mcx-n94-n54-mcus:FRDM-MCXN947)


#### **Repository URL:** https://github.com/wolfSSL/nxp-appcodehub/tree/main/dm-wolfssl-tls-hello-server-pqc-with-zephyr
#### **ACH URL:**        https://mcuxpresso.nxp.com/appcodehub?search=wolfssl-tls-1-3-example-using-pqc-on-zephyr


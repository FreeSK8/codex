---
layout: default
title: Smart BMS
nav_order: 1
parent: Realtime Status
grand_parent: FreeSK8 Mobile
---

## Smart BMS

Additional real time telemetry can be streamed if a compatible smart BMS device is connected to the CAN bus. Select the "Show Flexi/DieBieMS" option in the hamburger menu to request battery telemetry.

#### Notes:
* FreeSK8 requests BMS telemetry from CAN ID 10
* If a second BMS is installed the CAN ID can quickly be toggled to ID 11

#### Tested BMS devices:

* [DieBieMS](https://github.com/DieBieEngineering)
* [FlexiBMS](https://github.com/SimosMCmuffin)

![SmartBMS Main View]({{ '/' | absolute_url }}assets/images/mobileapp/smart-bms/bms1.jpg)

![SmartBMS Alternate View]({{ '/' | absolute_url }}assets/images/mobileapp/smart-bms/bms2.jpg)
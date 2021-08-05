---
layout: default
title: Realtime Status
nav_order: 2
parent: FreeSK8 Mobile
has_children: true
---

## Connected Vehicle Status Screen

With the real time data tab visible FreeSK8 requests telemetry from the primary ESC at a high rate. Information currently displayed:

* Duty Cycle
* Speed
* Power Remaining Estimate
* Battery Voltage
* Energy Efficiency 
* Motor Current
* Battery Current
* Mosfet Temperature
* Motor Temperature
* Distance Traveled
* Watt Hours Consumed
* Watt Hours Regerated
* Amp Hours Consumed
* Amp Hours Regerated
* ID of the connected ESC
* Fault Code
* Current location of mobile device

![Realtime Status Screen]({{ '/' | absolute_url }}assets/images/mobileapp/realtime.png)

Additional real time telemetry can be streamed if a compatible smart BMS device is connected to the CAN bus. Select the "Show Flexi/DieBieMS" option in the hamburger menu to request battery telemetry. See the [Smart BMS]({{ '/' | absolute_url }}docs/freesk8-mobile/real-time-data/smart-bms) section for more information.
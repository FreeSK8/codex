---
layout: default
title: Input Configuration
nav_order: 5
parent: FreeSK8 Mobile
---

## Input Configuration

Input configuration allows you to change the Application Mode in the ESC. FreeSK8 supports the following modes:

* None
* PPM + UART
* UART
* Balance

A PPM calibration routine is provided to determine the minimum and maximum signal values from a PPM based remote.

![PPM Calibration]({{ '/' | absolute_url }}assets/images/mobileapp/ppm-calibrate.gif)

Instructions are provided at the start of the routine. The expected result is the red dot resting in the center and moving in conjunction with your remote's throttle. If the calibration fails to produce meaningful values you have the option to Reject the proposed settings.

Other common input parameters provided are the control type and input deadband.

![Input Configuration]({{ '/' | absolute_url }}assets/images/mobileapp/inputconfig.png)

Advanced tuning parameters are available such as:

* Smart Reverse
* Throttle Exponential
* Traction Control

![Input Configuration]({{ '/' | absolute_url }}assets/images/mobileapp/inputconfig2.png)

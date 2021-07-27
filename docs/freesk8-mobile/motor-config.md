---
layout: default
title: Motor Configuration
nav_order: 3
parent: FreeSK8 Mobile
has_children: true
---

## Motor Configuration

The Motor Configuration can be accessed via the hamburger menu. Here you can change how the ESC interacts with your motor(s). If CAN devices are detected upon connecting you'll see the CAN ID's listed at the top. Tapping a CAN ID will switch the active device in the editor and request the current motor configuration for the selected ID.

![Motor Configuration]({{ '/' | absolute_url }}assets/images/mobileapp/motorconfig.png)
![Motor Configuration]({{ '/' | absolute_url }}assets/images/mobileapp/motorconfig2.png)


## [FOC Detection Wizard]({{ '/' | absolute_url }}docs/freesk8-mobile/foc-wizard/)

The [FOC Wizard]({{ '/' | absolute_url }}docs/freesk8-mobile/foc-wizard/) at the bottom of the Motor Configuration initiates a detection routine in the ESC. This detection is specificly geared towards medium sized outrunner motors commonly used in electric skateboards.

---
layout: default
title: Alerts
nav_order: 5
parent: OSRR
---

## OSRR Alerts

### Motion Sensing
>  1. Must be unplugged
>  2. Can be muted (Piezo off)

After 5 minutes of being powered on and motionless the OSRR will play an audio alert. Any amount of motion will reset the 5 minute timer.

### Input Sensing
>  1. Must be unplugged
>  2. Cannot be muted (Piezo setting has no effect)

After 10 minutes without pressing the User Button or Throttle the OSRR will play an audio alert. Pressing the User Button or a light amount of Throttle input is required to reset the 10 minute timer.

### ESC Faults
>  1. May occur at any time
>  2. Can be muted (Pizeo off)
>  3. Displayed on screen

Any time the ESC reports a fault condition (under voltage, DRV, over temp, etc) the OSRR will play an audio alert. The display will show a Fault was received and ESC values from the time of the event. Pressing the User Button will dismiss the alert dialog. 

Values displayed:

>  - ESC ID
>  - Fault Code
>  - Battery Voltage
>  - ESC Amps / Motor Amps
>  - ESC Temperature / Motor Temperature

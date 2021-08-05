---
layout: default
title: Connection & Status
nav_order: 1
parent: FreeSK8 Mobile
---

## Connected Vehicle Status Screen

Upon connection to a previously saved device you'll see a status screen similar to this picture.

![Connected Vehicle Status Screen]({{ '/' | absolute_url }}assets/images/mobileapp/status.png)

## Status Bar
Robogotchi users will see an extra bar across the top with Logging, Faults, Alerts and GPS status information. 

#### Logging
The logging column shows if data is currently being saved, the number of files on the device and how much storage space is remaining. Tapping this section will navigate to [Ride Logging]({{ '/' | absolute_url }}docs/freesk8-mobile/ride-logging/)

#### Faults
The faults column displays how many times a fault was observed by the Robogotchi as well as the Robogotchi firmware version.

#### Alerts
The next column allows you to temporarily disable audio alerts for a custom duration by tapping the bell icon. When snooze is active the remaining time is displayed in the status bar. To disable snooze tap the bell icon again and audio alerts will immediately resume.

![Connected Vehicle Status Screen]({{ '/' | absolute_url }}assets/images/mobileapp/audio-snooze.png)

Sometimes the Robogotchi beeps because you've connected and it's happy but if it's beeped because it's not happy one of the following reasons will be listed below the bell:

* Robogotchi Fault
* ESC Fault
* Robogotchi Storage Limit Reached
* ESC Over Temperature
* Motor Over Temperature
* Battery Voltage Low

#### GPS

The GPS signal acquisition and satellite count can be observed in real time. Typically, position accuracy increases with the satellite count. Being indoors can increase the time it takes to see a fix. If you are outdoors and have waited more than 5 minutes there is likely something interfering with the GPS reception. Carbon decks and carbon enclosures are the #1 cause of low satellite count. Consult a doctor today if you have less than 5 satellites.

## Connection Information

Below the vehicle avatar data about the connected device is made available for reference:

* Bluetooth Device Name
* Distance Logged (Robogotchi Only)
* Average Consumption (Robogotchi Only)
* ESC Hardware
* ESC Firmware

## Next Steps: 

Once connected there is much you can do. Here are a few good topics to get you going...

### [Realtime Status Screen]({{ '/' | absolute_url }}docs/freesk8-mobile/real-time-data/)
### [Motor Configuration]({{ '/' | absolute_url }}docs/freesk8-mobile/motor-config/)
### [Input Configuration]({{ '/' | absolute_url }}docs/freesk8-mobile/input-config/)
### [Ride Logging]({{ '/' | absolute_url }}docs/freesk8-mobile/ride-logging/)

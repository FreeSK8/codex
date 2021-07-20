---
layout: default
title: Operation & Status
nav_order: 4
parent: Robogotchi
---

### Robogotchi Status Screen

![Robogotchi OLED Status Screen](https://github.com/FreeSK8/FreeSK8-Robogotchi-Hardware/blob/main/Docs/Robotochi-Screen-Status.jpg)

### Bluetooth Status and PIN code

![](https://github.com/FreeSK8/FreeSK8-Robogotchi-Hardware/blob/main/Docs/LED-Status.PNG)

### Display PIN code

When there is no active Bluetooth connection pressing button B1 will toggle the display of Robogotchi’s PIN code.

### Revoke Access to all previously connected devices

When there is no active Bluetooth connection holding button B1 for 5 seconds will display CLEARD. At this time Robogotchi will have revoked access to all previously connected mobile devices. You must remove that FreeSK8 Robogotchi profile from your mobile device and then reconnect using the PIN code to create a new profile. 

**iOS users:**
* Navigate to Settings -> Bluetooth
* Tap the (i) next to FreeSK8 Robogotchi under MY DEVICES
* Select Forget This Device

**Android users:**
* Navigate to Settings -> Connected devices
* Tap the (Gear Icon) next to FreeSK8 Robogotchi
* Select Forget

### ESC Packet Status

As ESC data is received by Robogotchi the circle icon will move left and right. If a circle does not appear or is not moving there is trouble communicating with the ESC.

Robogotchi automatically determines if the TX and RX wires are switched and will adjust every 3 seconds. 

### GPS Data Status

The value after GPS is updated with the seconds of the minute as seen from the GPS module. The uBlox module shipping with the beta units may report a value of 247 until a satellite signal is acquired. 

Typically you would expect to see this update once a second with the current second of the minute.

### GPS Signal Status

Two digits after the S represent the GPS status being valid and of good quality. 
The first digit can be a 0 or a 1 with 1 meaning the GPS status is valid.
The second digit can be 0,1,2 with 1 and 2 meaning the GPS fix is valid.

If this reads S00 make sure your GPS has a clear view of the sky and wait a few minutes for the signal to be acquired.

Robogotchi will play audio tones when the GPS signal becomes valid or is lost.

### ESC Fault Indicator

This displays the number of fault types Robogotchi has received from the ESC(s) this session. A value of F00 indicates all is well.

A history of fault codes received are stored in memory while all faults are saved to the log files.

Robogotchi will play audio tones when a fault is observed.

### Filesystem free space %

As log files are saved to Robogotchi the available storage space is monitored.

Robogotchi will play audio tones when storage reaches a user defined limit.

### Logging in progress indicator

This will display Log active when Robogotchi is saving data to it’s internal storage.

### Number of files saved on Robogotchi

Each log is counted as 1 file and will remain on Robogotchi until a Sync operation is performed in the FreeSK8 Mobile companion application.

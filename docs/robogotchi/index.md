---
layout: default
title: Robogotchi
nav_order: 3
has_children: true
---

# FreeSK8 Robogotchi

The [FreeSK8 Robogotchi](https://derelictrobot.com/collections/production/products/freesk8-robogotchi) is an advanced BLE Receiver, Datalogger, and core component of the FreeSK8 System.

Think of it like a blackbox flight recorder for your esk8 or LEV. 

The Robogotchi brings Always-On Logging as a core feature with an asynchronous logging integration with our FreeSK8 Mobile App. 

Ride now, Sync later.

![Robogotchi v1.5](https://codex.freesk8.org/assets/images/robogotchi/robogotchi.jpg)

# Quick Start

1. Plug in your Robogotchi into your ESC using supplied UART Cable. 
2. Plug in your GPS Module. 
![Robogotchi Hardware Layout](https://codex.freesk8.org/assets/images/robogotchi/Robogotchi-pinout.png)

3. Turn on board & connect with FreeSK8 Mobile & Pair your Robogotchi using supplied PIN code. 
![Select & Connect to Supported Device](https://codex.freesk8.org/assets/images/mobileapp/scan2.png)

4. Create Board Profile & set user preferences. Remember to save!
![Board Profile](https://codex.freesk8.org/assets/images/mobileapp/saveprofile.png)

5. Setup your Robogotchi Configuration, found in the side menu. Remember to save!
![Gotchi Config](https://codex.freesk8.org/assets/images/mobileapp/gotchiconfig.png)
If you are running Dual or Quad ESC configuration, remember to select the auxillary CAN IDs. 
![Gotchi Config](https://codex.freesk8.org/assets/images/mobileapp/gotchiconfig2.png)

6. Your Robogotchi will automatically start logging based on the ERPM threshold set in your config, and ends automatically after a specified time (user set). You can also manually start/sync/stop logs on the Logging Tab of the Mobile App. 
![Logging Tab](https://codex.freesk8.org/assets/images/mobileapp/logcalendar.png)

7. When you would like to sync your ride logs, connect to your Robogotchi & click the "Sync Logs" button on the Logging Tab. This will initiate a sync transfer and copy the logs from Robogotchi to the Mobile App for viewing. 
![Log Sync](https://codex.freesk8.org/assets/images/mobileapp/logsync.png)

8. Tap on any log to launch it in the ride log viewer. 
![Ride Log](https://codex.freesk8.org/assets/images/mobileapp/ridelog.png)

You got it! Ride Safe!
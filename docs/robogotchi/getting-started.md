---
layout: default
title: Getting Started
nav_order: 1
parent: Robogotchi
---

# Installation Guide
1. You will want to connect, configure, & test your Robogotchi before you finish installation into an eBoard, eBike, or LEV.
2. Plug the Robogotchi into your ESC's UART port using the supplied 150mm 4pin to 8pin UART Cable. If you use dual ESCs, it can be connected to either ESC but the primary is preferred. 
3. Plug the GPS Module into the Robogotchi's GPS port, using the supplied 300mm 4-pin to 4-pin Cable.
4. Power on your ESC. You should hear a startup Not-Mario-Melody & the status screen will turn on. More information on the [Status Screen can be found here.](https://github.com/FreeSK8/FreeSK8-Robogotchi-Hardware/wiki/Operation-&-Status#robogotchi-status-screen)
5. Press B1 to display your PIN code. Write this 5-digit number down and/or take a picture of it in your phone for future reference. This PIN code is unique to your Robogotchi and acts as a security measure to prevent unauthorized access. 
6. Launch the FreeSK8 Mobile App & Scan for nearby devices. You should see the Robogotchi broadcasting as "FreeSK8 Robogotchi", connect to it and enter your PIN code when prompted. 
7. You should hear the Keyboard Cat melody from the Robogotchi upon successful bluetooth connection, and you will be prompted to create a Board Profile on the FreeSK8 Mobile App.
8. Next, on the FreeSK8 Mobile App, press the hamburger menu button in the upper left, and select 'Robogotchi Config'. Here you can configure the Robogotchi & setup single/dual/quad ESC datalogging over canbus. 
9. Connect your remote and with your board in a safe position, engage the throttle and the Robogotchi should automatically start logging. 
10. Logging will stop automatically, or you can manually stop it via the FreeSK8 Mobile App on the Logging Page. Once the log has stopped, press the Sync button to transfer the test log from the Robogotchi to the Mobile App. 
11. If you are using a GPS Module, it will have to be mounted with Line-of-Sight to the sky.

## GPS Module Setup & Use

1. Once mounted & plugged in, the GPS module is supplied power from the Robogotchi. You should see a green LED turn on solid to indicate power. The Robogotchi will also display Satellite Status on it's screen. Please see the [Status Screen documentation](https://github.com/FreeSK8/FreeSK8-Robogotchi-Hardware/wiki/Operation-&-Status#robogotchi-status-screen) for more details. 
2. The GPS module needs to calibrate & lock on initially, and sometimes this first calibration can take longer than normal operation. In good weather conditions and with clear line of sight to the sky, an initial satellite lock should usually take less than a minute, and in most circumstances subsequent startups take 5-30 seconds. 
3. You will hear a melody played when the Robogotchi gains or loses a satellite lock. 
4. That's it! Once the Robogotchi has a satellite lock, it will automatically record GPS coordinate data in time sync with your ESC telemetry data. 


## System Overview

![Robogotchi GPS System Overview](https://github.com/FreeSK8/FreeSK8-Robogotchi-Hardware/blob/main/Docs/Robogotchi-GPS-Diagram.png)
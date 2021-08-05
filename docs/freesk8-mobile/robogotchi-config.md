---
layout: default
title: Robogotchi Configuration
nav_order: 6
parent: FreeSK8 Mobile
---

## Robogotchi Configuration

The Robogotchi configuration lets you change the settings saved in the Robogotchi. These are good to adjust when setting up a new Robogotchi or moving one to a new vehicle. 

You can access the Robogotchi Configuration from the hambuger menu.

![Hamburger Menu]({{ '/' | absolute_url }}assets/images/mobileapp/sidemenu.png)

### Parameters

#### Log Auto Stop/Idle Board Timeout
  > This is the number of seconds that can pass before the Robogotchi stops logging automatically. A value of 300 (5 minutes) is common and if you happen to take a 10 minute break you can always [merge]({{ '/' | absolute_url }}docs/freesk8-mobile/ride-logging/#ride-merging) the pieces together.

#### Log Auto Stop Low Voltage Threshold
  > When this voltage is reached the Robogotchi will automatically stop logging. The default value is 20V which works for most PEVs. The intended function is to stop logging and save your data when the Robogotchi detects a power outage. It's recommended to set this value at least 5V below your minimum pack voltage.

#### Log Auto Start Sensitivity
  > The Robogotchi will automatically start logging when the wheel eRPM reaches this speed. The default value of 2000 works for most vehicles.

#### Log Entries per Second
  > The number of ESC entries saved every second. Something to keep in mind, as this value increases so do the Bluetooth transfer times. 
  > * Common values:
  >   * 1Hz for Single ESC
  >   * 2Hz for Dual ESC
  >   * 4Hz for Quad ESC

#### GPS Baud Rate
  > The default value of 9600 baud is most common.

#### Single, Dual, Quad ESC Mode
   > In Single ESC Mode telemetry is logged from the connected ESC.
   > * In Dual or Quad ESC Modes telemetry is requested and logged from the specified ESC ID(s) over CAN bus.

#### Alert Low Voltage
  > Robogotchi will play an audio alert any time the vehicle's battery voltage drops below this level.

#### Alert ESC Temperature
  > Robogotchi will play an audio alert any time the ESC Temperature is above this value.

#### Alert Motor Temperature

  > Robogotchi will play an audio alert any time the Motor Temperature is above this value.

#### Alert when Storage is at Capacity
  > Robogotchi will play an audio alert when it's internal storage has used more than this percentage.

![Robogotchi Configuration]({{ '/' | absolute_url }}assets/images/mobileapp/gotchiconfig.png)
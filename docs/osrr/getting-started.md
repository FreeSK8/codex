---
layout: default
title: Getting Started
nav_order: 1
parent: OSRR
---

## Installation

* Install Receiver
  * UART Configuration
    1. Connect the supplied cable from the Receiver directly to your ESC

  * PPM + UART Configuration

    > In situations where multiple devices are needed on a single UART it is highly recommended you do not attempt to operate your vehicle through a multiplexer. 
    
    The FreeSK8 Receiver can be configured to output PPM by connecting GPS RX to GND. In this mode the PPM signal is sent to your ESC via the GPS TX wire and only telemetry is requested via UART. The [uSplit](https://solidcircuits.net/usplit-documentation/) is a recommended device for this task.

    1. Connect GPS RX to GND
    2. Connect GPX TX to ESC PPM Input
    3. Connect the supplied cable from the Receiver to your UART device

* Configure OSRR

  1. Acess the [Setup Menu](../setup-menu) by holding full brake or full throttle and powering on the OSRR. 
  2. Navigate the menu with throttle input.
  3. Press the User Button to toggle the current selection.
  4. Power off to exit. Settings are automatically saved.

* Pair Receiver and OSRR

  1. Activate [Pairing](../pairing) by holding down the User Button while powering on the remote.
  2. Power on your Receiver.
  3. Review the on screen status. Typically paired in under 10 seconds.

## Next steps

* Testing
  > Once installed and paired it's time to make sure everything is working as expected. Power on the OSRR and your board to make sure the wheels are spinning in the correct direction and you still have brakes.

* Tuning
  > Using FreeSK8 Mobile you can adjust settings like reverse modes and throttle curves to make things work exactly how you like them. Learn more about adjusting your [Input Configuration](../../freesk8-mobile/input-config/) here.
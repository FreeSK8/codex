---
layout: default
title: Advanced
nav_order: 7
parent: FreeSK8 Mobile
---

# Advanced

### TCP Bridge

The TCP Bridge can be enabled in the menu once connected to an ESC. This will allow you to connect to your ESC from other applications like vesc-tool via FreeSK8 Mobile’s Bluetooth connection. Your phone must be connected to WiFi and have an IPv4 address to use this feature. When enabled your IP will be presented.

### Data Backups

Data backups are a great way to keep an archive of the trips you've taken. You'll find them in the Advanced drop down of the Configuration tab.

The Export routine is quite safe. Depending on how much data you have there may be a delayed response while it creates a zip file of your board avatars, settings, database and ride logs. You’ll be prompted to share this file and you can save it to Google Drive or iCloud as a backup of your FreeSK8 data.

The Import routine on the other hand is marked with Caution as it will ask you for the location of a FreeSK8 Data Backup and then replace your database, avatars, and logs with those from the backup. There is no merging of old data here. Meaning whatever you had before the Import will be removed and replaced with the contents of the backup.

### Vehicle Manager

The vehicle manager displays a list of board profiles you've created (previous connections) allowing you to modify or remove vehicles from your phone.

#### Retire Vehicle
If you are connected to your device you’ll have the option to Retire the vehicle. This will retain all the data the Robogotchi has collected and allow you to setup a new vehicle profile with the connected device.

#### Adopt Vehicle
This option is available if the connected device is not currently associated with a vehicle (usually after retirement). By adopting a vehicle the profile and ride logs saved will belong to the connected device.

#### Erase Vehicle
This option will remove the vehicle and all of the rides you’ve logged. You can't undo this action but you remember that bit about doing a backup, right?

---
layout: default
title: Ride Logging
nav_order: 7
parent: FreeSK8 Mobile
#has_children: true
---

# Ride Logging

The features in this section of the app require the use of a Robogotchi or a Data Backup from a phone that's Sync'd with a Robogotchi.

### Calendar and List View

Tapping the robot at the top of the Ride Logging tab will switch from Calendar to List View. The Calendar view is most notable for organizing your trips by date. They'll add up, it's a lot of fun. 

The List view is a sortable table of entries. From here you'll have the ability to swipe left to delete rides or swipe right to Merge or Share your data.

### Quick Statistics

A long press on any ride entry will display the board name and few extra details about your trip.

![Quick Statistics Dialog]({{ '/' | absolute_url }}assets/images/mobileapp/ride-logging/quick-stats.jpg)

### Ride Merging

Ride Merging. That’s right, you asked for it. Or maybe you didn’t but you might really like it anyway 😉 From the List View on the Ride Logging tab you can swipe right to Merge with the previous ride. You'll be promted with a dialog that displays the vehicle name, timestamps and durations so you have one last chance to make sure everything is good to go.

![Merge Confirmation]({{ '/' | absolute_url }}assets/images/mobileapp/ride-logging/merge.jpg)

Pretty simple, yeah? Cool. As with the Vehicle Manager, this is new feature and it would be a good idea to do a backup before merging anything important to you.



### Sync'ing Ride Logs

The current sync mechanism is via Bluetooth Low Energy. We've optimized our file sizes and transmission rates to get the best performance possible.

The sync time will vary depending on your ride duration, [logging rate]({{ '/' | absolute_url }}docs/freesk8-mobile/robogotchi-config/#log-entries-per-second), signal quality and other active Bluetooth devices on your phone.

![Ride Sync]({{ '/' | absolute_url }}assets/images/mobileapp/logsync.png)

### Sharing Data

Rides in human readable CSV format can be shared from the List View by swiping right

![as demonstrated]({{ '/' | absolute_url }}assets/images/mobileapp/ride-logging/share.jpg)

or by swiping up in the Ride Log Viewer

![as demonstrated]({{ '/' | absolute_url }}assets/images/mobileapp/ride-logging/share2.jpg)


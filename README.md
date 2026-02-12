# QGroundControl Ground Control Station

This project is clone the official QGroundControl repository, specifically based on the `Stable_V4.4` branch:
[https://github.com/mavlink/qgroundcontrol/tree/Stable_V4.4](https://github.com/mavlink/qgroundcontrol/tree/Stable_V4.4)

*QGroundControl* (QGC) is an intuitive and powerful ground control station (GCS) for UAVs.

The primary goal of QGC is ease of use for both first time and professional users.
It provides full flight control and mission planning for any MAVLink enabled drone, and vehicle setup for both PX4 and ArduPilot powered UAVs. Instructions for *using QGroundControl* are provided in the [User Manual](https://docs.qgroundcontrol.com/en/) (you may not need them because the UI is very intuitive!)

All the code is open-source, so you can contribute and evolve it as you want.
The [Developer Guide](https://dev.qgroundcontrol.com/en/) explains how to [build](https://dev.qgroundcontrol.com/en/getting_started/) and extend QGC.

For Android development

1. You need to manually download and extract GStreamer 1.18.6:
   
   1.1  Download the Android package for GStreamer 1.18.6 from:
    [https://gstreamer.freedesktop.org/data/pkg/android/1.18.6/](https://gstreamer.freedesktop.org/data/pkg/android/1.18.6/)
    (e.g., `gstreamer-1.0-android-universal-1.18.6.tar.xz`)
   
   1.2  Extract the downloaded archive.
   
   1.3  Place the extracted `gstreamer-1.0-android-universal-1.18.6` folder directly into the project root directory (`qgroundcontrol/`).

2. If you don't want to buid system app, you must remove android:sharedUserId="android.uid.system" in AndroidManifest.xml

Key Links:
* [Website](http://qgroundcontrol.com) (qgroundcontrol.com)
* [User Manual](https://docs.qgroundcontrol.com/en/)
* [Developer Guide](https://dev.qgroundcontrol.com/en/)
* [Discussion/Support](https://docs.qgroundcontrol.com/en/Support/Support.html)
* [Contributing](https://dev.qgroundcontrol.com/en/contribute/)
* [License](https://github.com/mavlink/qgroundcontrol/blob/master/COPYING.md)

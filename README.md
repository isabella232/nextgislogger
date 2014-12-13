NextGIS Logger
==========

Productive data logger for Android
***
#### version 1.2.1 (13.12.2014)
* Added sharing logs to menu
* Added deleting logs to menu
* Added Russian localization

#### version 1.2 (09.12.2014)
* Added [sessions](https://github.com/nextgis/nextgislogger/wiki/About)
* Added [separate activity for marks](https://github.com/nextgis/nextgislogger/wiki/About)
* Added data from [sensors](https://github.com/nextgis/nextgislogger/wiki/Overview): orientation, magnetic_field, gyroscope
* Added device info in [device_info.txt](https://github.com/nextgis/nextgislogger/wiki/Overview) for each session
* Added marks count and records count info for each session.
* Changed minimum Android version to 3.0 - Honeycomb (API 11), maximum 5.0 - Lollipop (API 21)
* Changed package name to "NextGIS Logger" (com.nextgis.logger). Please reconfigure your preferences.
* Changed cell data: "Power" in header instead RSSI, "-1" instead Integer.MAX_VALUE on API 17+
* Сode refactoring

#### version 1.1.4 (04.12.2014)
* Fixed signal strength for 3G network below API 17 method (RSCP shows instead 0)
* Fixed results directory visibility on external storage through MTP
* Portrait orientation only in main activity 
* Improved categories file storage (may require reload file)

#### version 1.1.3.1 (29.11.2014)
* Fixed app crash while delete characters fast in Mark Name edit
* Possibly fixed GSM log headers

#### version 1.1.3 (20.11.2014)
* Added "Identification string" to settings
* Added current network type/generetaion, psc for UMTS and identification string to log
* Improved current network type info. Now generation and type show in main screen as separate line
* Fixed app crash on Samsung and Nexus (perhaps others) devices when using API 17+ option
* Changed "Try use API 17+" to true by default

#### version 1.1.2 (13.11.2014)
* Added preset categories for mark name (choose preset file in options)

#### version 1.1.1 (10.11.2014)
* Fixed LAC and CID (were swapped in csv)
* Fixed "Type" column in accelerometer log (now indicates "Linear"/"Raw")
* Fixed linear acceleration. Now uses build in sensor (available on Gingerbread 2.3 or above and if device has linear sensor)
* Added new method to find nearby cells on devices for Adnroid >=4.2 (check it in options)
* Added WakeLock to Service (data saves continuously when screen is off)
* Logger period moved to settings

#### version 1.1 (09.11.2014)
* Added accelerometer data to logger
* Added settings screen for accelerometer
# Aura Mobile Application

The Aura mobile application is a smartphone application that connects epileptic patients to Aura Solution.

Currently the application is available on Android with OS 4.3 or newer.

It runs in background of the smartphone in a transparent way for the user. It works in the same time as receiving phone calls or using others applications.

It allows to:
  * connect with Aura devices and collect physiological data in real time
  * transfer collected data to a secure cloud
  * notify a past seizure


#### Collect physiological data in real-time

At launch, mobile application try to automatically pair with Aura devices.

Once connected, physiological parameters are streamed to Aura mobile application through Bluetooth LE.
The data are stored locally during the monitoring interval (8 hours)

<img src="/assets/splash-screen.png" width="230"> <img src="/assets/monitoring-screen.png" width="230">

#### Transfer to secure Cloud
When the monitoring session is over, we can connect the mobile app to Wifi and data are transfered by packets to an InfluxDB on a secure Cloud.

#### Seizure notification
The user can notify a past seizure by using the mobile interface. It will help us to label the seizure onset.

<img src="/assets/seizure-report-screen.png" width="230">

#### About security
What we do in our app [here](best-practice-mobile-security-application.md)

## Source Code

The Aura mobile app source code is open source, distributed under GPL v3 license and available on [Github](https://github.com/clecoued/Aura_mobile_app).

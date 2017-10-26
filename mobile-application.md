# Aura Mobile Application

The Aura mobile application is a smartphone application that connects epileptic patient to Aura Solution.

It can work in two distinct modes:

* **nomad mode:** The Aura mobile app is used for outdoors activities. It monitors directly physiological data from armwrist sensors to alert user of an upcoming seizure
* **home-based mode:** The Aura mobile application is used at home as an end point of the Aura Gateway. It alerts patients and close relatives of an upcoming seizure

## Pre-requisites

The Aura mobile application requires a smartphone working on Android OS with active Bluetooth/Wifi connection

## User Experience

#### Application Start

First, the user is requested to authentificate with credentials or via an external Identity provider\(Facebook/ Google account\)  to access his private monitoring session.

Once authentification succeed, the mobile application will automatically pair with Aura devices and Aura gateway in order to start seizure monitoring.![](/assets/epi_ux_flowchart_loading.jpg)

#### User Interactions

During the monitoring session, the user can quickly report a past epilepsy seizure, a past aura or a false epilepsy seizure alert.

This information will help to improve Aura personnalized algorithms and allows the user to review his seizure history and share it with his specialist.

The user can also decide when to sync his encrypted personnal data with the Cloud in order to limit data comsumption.![](/assets/epi_ux_flowchart_buttonmenu_v2.jpg)

#### Seizure alert

During monitoring sessions, physiological parameters are streamed to embed Aura algorithm.

When Aura algorithm predicts an epilepsy seizure, it triggers an alert on mobile application. The mobile application automatically notifies the user with a buzz, sound and visual alert and indicates the approximate remaining time before the seizure.

The user can then start a customized Safety protocol to anticipate the seizure. ![](/assets/epi_ux_seizure_alert_flowchart %281%29.png)

## Source Code

The Aura mobile app source code is open source, distributed under GPL license and available on [Github](https://github.com/clecoued/Aura_mobile_app).
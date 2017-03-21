# Aura Mobile Application

The Aura mobile application is the epileptic patient interacting interface.

It can work in two distinct modes:

* **nomad mode:** The Aura mobile app is used for outdoors activities. It monitors directly physiological data from armwrist sensors to alert user of an upcomming seizure
* **home-based mode:** The Aura mobile application is used at home as an end point of the Aura Gateway. It alerts patient close relatives of an upcoming seizure.

## Pre-requisites

The Aura mobile application requires a smartphone working on Android OS with active Bluetooth/Wifi connection

## User Experience

#### Application Start

First, the user is requested to authentificate with credentials or via an external Identity provider\(Facebook/ Google account\)  to access his private monitoring session.

Once authentification succeed, the mobile application will automatically pair with Aura devices and Aura gateway in order to start seizure monitoring.![](/assets/epi_ux_flowchart_loading.jpg)

#### User Interactions 

During the monitoring session, the user can quickly report a 

This information will help to ![](/assets/epi_ux_flowchart_buttonmenu_v2.jpg) 

## Functionnalities

The Aura mobile application allows:

1. User to be notified few minutes in advance of an epileptic seizure
2. User to securely access to a private monitoring session
3. User to store anonymized and encrypted personnal physiological data on Cloud
4. User to pair automatically with Aura devices and Aura Gateway
5. User to report an epilepsy seizure
6. User to report a detailled aura
7. User to report a false seizure alert 
8. User to review personnal epilepsy seizure history 

## Architecture

To Simplify![](/assets/auraapparchitecture.jpg)

## Source Code

The Aura mobile app source code is open source, distributed under GPL license and available on [Github](https://github.com/clecoued/Aura_mobile_app).


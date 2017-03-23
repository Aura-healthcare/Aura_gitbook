# Aura Gateway

## Pre-requisites

In order to communicate with the Aura Server, the Gateway needs an internet connection with at least one of the following communication link :

* Wifi and/or Ethernet over FAI box ; and/or
* 2G/3G/4G over mobile network \(mobile operator data subscription requiered\).

If several links are used, the Gateway will be able to manage failure of one of them by switching to another link \(enhanced reliability of the communication link\).

## User Experience

#### Gateway configuration

The Gateway requiers a configuration step before beeing totally autonomous. During this phase the user will :

* Configure wifi access to the FAI box if used ;
* Configure access to 2G/3G/4G network if used ;
* Link the owned Aura Devices to the Gateway ;
* Link the Gateway to the user session on the Cloud. 

## Functionnalities

The Aura Gateway is a platform dedicated to management of the communication between each Aura Device and the Aura Server in safe/reliable/secured manner. This Gateway shall :

* be configurable as previously explained ;
* manage reliable BLE connections with all the registered Aura Devices \(including link loss management\) ;
* manage reliable multi-supports communication with the Aura Server ;
* keep a non volatile copy of data over several days \(for loss of communication management\) ;
* be robust to power failure.

## Architecture

## Source Code

The Aura mobile app source code is open source, distributed under GPL license and available on **Github**.


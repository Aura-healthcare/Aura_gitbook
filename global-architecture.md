# Global Architecture

### Phases

We have to consider two differents phases in the Aura Solution lifecycle:

* **training phase**: A first short phase where patient physiological data are sent to the Cloud in order to train a machine learning algorithms. The personnalized resulting configuration is then updated on an Aura device embed algorithm.
* **monitoring phase: **A second phase where patient physiological data are received by the Aura device embed algorithm and processed without external connection.

### Design

The Aura project is an IoT project.

It can be split in 4 main modules:

* **Aura Devices:** A serie of autonomous wearable devices that record and tranfert patient physiological data.

* **Aura Gateway: **A hadware module that enforces communication between Aura devices, Aura mobile applications and Database. It also embed a trained Aura Algorithm to process, on the fly, physiological data in order to alert patient and relatives of an upcoming seizure.

* **Aura Mobile application: **A smartphone application that allows patients and relatives to be alerted of an upcoming seizure and to interact with Aura Solution.

* **Aura Algorithms: **They can be split in 2 categories

  * Learning algorithms which are processing patients data on Cloud during **Training phase **to set up monitoring algorithms personnalization

  * Monitoring algorithms which are embed in Aura Mobile application and Aura Gateway to detect in advance upcoming seizures

![](/assets/auraglobalarchitectureproto.png)


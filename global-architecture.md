# Global Architecture

### Phases

We have to consider two differents phases in the product lifecycle:

* **training phase**: A first short phase where patient physiological data are sent to the Cloud in order to train a machine learning algorithms. The personnalized resulting configuration is then updated on an Aura device embed algorithm.
* **monitoring phase: **A second phase where patient physiological data are received by the Aura device embed algorithm and processed without remote connection.

### Design

The Aura project is an IoT project.

It can be split in 4 main modules:

* **Aura Devices:** A serie of autonomous wearable devices that record and tranfert patient physiological data. They embed a trained Aura Algorithm to process, on the fly, physiological data in order to alert patient of an upcoming seizure.

* **Aura Gateway: **A hardware module that enforce communication to database

* **Aura Mobile application: **A smartphone application that allows user to be alerted o and to report seizure

* **Aura Algorithms:**

![](/assets/auraglobalarchitecture %282%29.png)


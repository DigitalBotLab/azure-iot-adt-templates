# azure-iot-adt-templates
**Azure IoT and Azure Digital Twin Deployment Templates** 

These templates help you deploy infrastructure to support our Nvidia Omniverse & IoT / Digital Twins solution.  

**Azure Digital Twins**

[1. Azure Digital Twins with Function and Private Link service](https://https://github.com/DigitalBotLab/azure-iot-adt-templates/digitaltwins-with-function-private-link/README.md)

This template creates an Azure Digital Twins service configured with a Virtual Network connected Azure function that can communicate through a Private Link Endpoint to Digital Twins. It also creates a Private DNS Zone to allow seamless hostname resolution of the Digital Twins endpoint from the Virtual Network to the Private Endpoint internal subnet IP address.

[2. Azure Digital Twins with Time Data History Connection]()

This template creates an Azure Digital Twins instance with a time series data history connection. Other resources are also created such as an Event Hubs namespace, an event hub, an Azure Data Explorer cluster, and a database. 


**Azure IoT**

[1. Create an IOT Hub and Ubuntu edge simulator]()

The purpose of this ARM Template is deploy an IoT Hub with an Ubuntu Edge Simulator. The Linux Ubuntu virtual machine is configured to be an IoT Edge device

[2. Use ARM template to create IoT Hub, route and view messages.]()

This template creates an IoT Hub instance and a storage account, and shows how to auto-route messages to storage.

[3. Create an IoT Hub Device Provisioning Service]()

This template creates an IoT hub and an IoT Hub Device Provisioning Service, and link the two services together.

[4. Create an IoT Hub and a Device to Cloud Consumer Group]()

This template creates an IoT Hub instance with device to cloud and cloud to device messaging configurations and a device to cloud consumer group.
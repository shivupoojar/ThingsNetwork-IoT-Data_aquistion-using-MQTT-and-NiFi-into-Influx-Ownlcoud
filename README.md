# ThingsNetwork IoT Data aquistion using MQTT and NiFi into Influx database and Ownlcoud

This project mainly focused on data archiving from ThingsNetwork in to Influxdb time series database and owncloud using MQTT ThingsNetwork topic subscritption.
An archived data is visulaized using grafana.

** Setting up application adn device in ThingsNetwork**
- Create an account in ThingsNetwork(https://www.thethingsnetwork.org/)
- Create an application in ThingsNetwork(https://www.thethingsnetwork.org/docs/applications/add.html)
- Register device in to an application(https://www.thethingsnetwork.org/docs/devices/registration.html)

**Simulating devcie and decoding the payload in ThingsNetwork**

Instead of using real devices and LORAWAN gateway, We wil simulate the device to send some sample payload and decode, when data is recieved in thingsnetwork application.\
Now in the section **Simulate Uplink**, add Hexadecimal payload of your own size(Ex. AA FF AA FF AA CC DD AA FA CA 12 bytes),\ 
![payload](/Payload_added.JPG)

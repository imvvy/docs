---
description: >-
  MQTT is M2M communication protocol that has become quite popular for IoT
  purposes due to its simplicity and lightness.
---

# MQTT DEVICES

It uses a pub-sub messaging paradigm in which the devices, also called "clients" maintain a TCP/IP connection with the server. This enables them to perform two different types of communication: -

* **Publish** messages with an identificatory which is called "topic". In this way, the devices can send data to the server.
* **Subscribe** to a specific topic, to receive data from the server. The server, also called "broker", keeps all the registered devices connected to the server and their pub-sub type, allowing fast and efficient data transmission to all subscribed devices; when it arrives to a specific topic in an asynchronous way.

### Integration of MQTT devices

Imvvy Platform has been provided with MQTT broker, that can be used to integrate devices with this protocol in a very simple way. This allows devices to publish and subscribe communications. In the next sections it is explained in detailed how to work with both, and how to work with its data. 

This process is carried out in two parts. Platform server that acts as Broker, and on the other hand, the configuration of an MQTT Client creates the communication with the server.


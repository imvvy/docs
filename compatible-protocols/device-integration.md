---
description: >-
  After provisioning the device on the  Imvvy IoT Platform you need to configure
  the hardware devices. There are many different hardware communication
  technologies available however we support HTTP,MQTT
---

# Device integration

## HTTP Devices

* Create an HTTP device profile by selecting the “Device Type” when creating the device.
* Create an Auth Access Token to authorize the device to send data to the platform.
* Introduce the HTTP request \(API+Auth Key\) in your device code or third-party platform and start sending JSON data to the Imvvy IoT Platform.

## MQTT Devices

* Create a new device profile and by selecting the "MQTT" device type.
* Configure device credentials through a secret password.
* Configure the MQTT client to send data to the embedded broker.

## Devices & Data management

Each device can be managed through the "Device Dashboard". This interface shows connection data and also allows the checking of "device API" with raw device data representation.

## Store, Show & Share Data

Imvvy IoT Platform provides three essential tools to work with the device's data that are the basis for creating any IoT project. The following tabs show the introduction to each tool. 

* Data Download 
* EndPoints/ Webhook 
* Data Access API




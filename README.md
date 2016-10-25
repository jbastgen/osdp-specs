# OSDP - Open Smart Device Protocol

OSDP is a simple and open protocol used to control smart devices through your network.
The protocol is based on TCP/IP and UDP and defines a generic way to control your devices.

The origin of this project was that I wanted to build a smart lamp that can be controlled via WiFi but the standard approach over MQTT messages looked awful and not very nice or interoperable.
Research showed that there was no suitable protocol available for public use on own devices. Protocols have been closed source and/or without suitable documentation.

The OSDP protocol can be used by everybody free of charge and can be implemented in nearly any device that can communicate over TCP/IP and/or UDP. OSDP is designed to be as generic and simple as possible.

This repository contains the specifications related to a certain version of the protocol.

Please refer to the [wiki](https://github.com/NeoP5/osdp-specs/wiki) for the specifications.

## Implementations
The following list contains links to available implementations of the OSDP protocol.

| Platform  | Project | Link | 
| ------------- | ------------- | ------------- |
| Arduino  | osdp-arduino  | (https://github.com/NeoP5/osdp-arduino) |
| ESP8266 (Arduino)  | osdp-esp8266-arduino  | (https://github.com/NeoP5/osdp-esp8266-arduino) |
| Java | osdp-java | (https://github.com/NeoP5/osdp-java) |

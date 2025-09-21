## MQTT
--> HTTP is costly large
--> HTTP Request and response mode
--> 1-1 Communicatuiin

MQTT:
  --> Hub and Sub Model
  --> Telecommunication
  --> Pub/Sub model

--> Central hub called MQTT broker, any data type --> Different priority --> Retransmitted
--> IBM --> 2010 -->


MQTT:
-> TCP/IP model
--> MQTTv3.1.0
--> MQTTv3.1.1
--> MQTTv5.0 (Not backward compaitable)

MQTTSN:


The lecture "MQ Telemetry Transport: The Origin Story" covers the foundational aspects of the MQTT protocol. Here are the main points:

Origins: MQTT was developed in 1999 by Andy Stanford-Clark and Arlen Nipper at IBM to address monitoring challenges for oil pipelines via satellite, requiring an efficient protocol due to limited internet connectivity.

Core Requirements: The development was guided by five key requirements: simple implementation, quality of service for data delivery, lightweight and efficient bandwidth usage, data agnosticism, and continuous session awareness, which were crucial for satellite communication.

Publish-Subscribe Model: MQTT uses a Publish-Subscribe model with a central broker, facilitating simpler client implementations, smaller packets, and support for various data types.

Quality of Service: The protocol features three levels of Quality of Service, session persistence, and reduced reconnection needs, aiding cost management in satellite contexts.

Evolution: Initially used internally by IBM, MQTT was released as a royalty-free standard in 2010 and became an OASIS Standard in 2014. It includes two variants: the standard MQTT for TCP/IP and MQTT-SN for sensor networks using UDP.

Adoption in IoT: The lecture highlights the transition of MQTT from proprietary use to becoming a key player in the Internet of Things landscape, driven by the increase of mobile devices and internet connectivity, making it suitable for machine-to-machine communication.

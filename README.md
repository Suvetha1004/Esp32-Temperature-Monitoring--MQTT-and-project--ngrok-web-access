
Team Members:
Suvetha K (24ECR216)
Sriram Kannan S (24ECR198)
Sujitha B (24ECR211) 

IoT Temperature Monitoring using ESP32 and Raspberry Pi (MQTT):

 Project Overview:

This project demonstrates an IoT-based temperature monitoring system using ESP32 and Raspberry Pi with the MQTT protocol.
The ESP32 acts as a publisher that sends simulated temperature data, while the Raspberry Pi works as an MQTT broker and subscriber to receive and display the data.
The system enables wireless communication between devices and shows how MQTT can be used for real-time IoT data transfer.

 Objective
To establish MQTT communication between ESP32 and Raspberry Pi
To monitor temperature data wirelessly
To demonstrate IoT message publishing and subscribing

 Components Required
Hardware:
ESP32 Development Board
Raspberry Pi
USB Cable
Laptop / PC
WiFi Connection

Software:
Arduino IDE
Mosquitto MQTT Broker
Python 3
Paho MQTT Library

System Architecture:
ESP32 → Publishes temperature data
⬇
MQTT Broker (Raspberry Pi)
⬇
Python Subscriber receives and displays data

 Procedure:

Install Mosquitto MQTT broker on Raspberry Pi.
Start the Mosquitto service.
Find the Raspberry Pi IP address.
Install the MQTT library in Arduino IDE.
Upload the ESP32 publisher code.
Install the Paho MQTT library in Python.
Create and run the Python subscriber program.
Verify that temperature data is received successfully.

What is MQTT Broker?

An MQTT Broker is a central server that receives messages from publishing devices and forwards them to subscribed devices based on specific topics.

How MQTT Works?

A device (Publisher) sends data to a topic.
The MQTT Broker receives the message.
The broker distributes the message to all Subscribers subscribed to that topic.

Web Access using Ngrok:
To access the system remotely:
Login to ngrok
Install ngrok on Raspberry Pi
Add authentication token
Start the local server
Run
ngrok http 80
Use the generated public URL to access the web interface.

Example Web URL:
https://semiyearly-anglea-unburdensome.ngrok-free.dev/

 Output
ESP32 publishes simulated temperature data.
Raspberry Pi receives the data using MQTT.
Data is displayed on the Python subscriber terminal.
Continuous wireless communication is established between devices.

Result:
The ESP32 successfully published temperature data and Raspberry Pi received it using the MQTT protocol.
This project demonstrates efficient wireless IoT communication using MQTT.


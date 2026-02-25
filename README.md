# Samsung-SIC--IOT-Major-Project--SERICULTURE-SMART-SYSTEM
The Sericulture Smart Control System is an IoT-based environmental monitoring and automation solution developed using Raspberry Pi and Blynk Cloud.

This system is designed to maintain optimal environmental conditions required for sericulture (silk farming) by continuously monitoring temperature and humidity and automatically controlling cooling and irrigation mechanisms.

The project was developed as part of the Samsung Innovation Campus (SIC) program.

🎯 Objective

To design and implement an intelligent, cloud-connected environmental control system that:

Monitors temperature and humidity in real time

Maintains optimal conditions for silkworm cultivation

Reduces manual intervention

Enables remote monitoring and control

✨ Key Features

🌡 Real-time temperature monitoring

💧 Real-time humidity monitoring

🔄 Automatic fan activation when temperature exceeds 25°C

🚿 Automatic water pump activation when humidity drops below 50%

📱 Manual device control via Blynk mobile application

☁ Cloud-based IoT monitoring and control

💡 LED status indication for system condition

📊 Live data visualization through mobile dashboard



🚀 How to Run the Project
1️⃣ Hardware Requirements

Raspberry Pi (with Raspberry Pi OS installed)

DHT11 Sensor

Relay Module (2 Channel)

Fan

Water Pump

LED

Jumper Wires

Power Supply

2️⃣ Software Requirements

Python 3.11

Required Libraries:

RPi.GPIO

BlynkLib

adafruit_dht

board

3️⃣ Install Required Libraries
sudo apt update
pip3 install blynklib
pip3 install adafruit-circuitpython-dht
pip3 install RPi.GPIO
4️⃣ Set Blynk Authentication Token

Replace this line in main.py:

BLYNK_AUTH = "YOUR_AUTH_TOKEN"

With your Blynk Cloud token.

5️⃣ Run the Project
python3 main.py
6️⃣ Open Blynk Mobile App

Add widgets connected to Virtual Pins:

V0 → Temperature

V1 → Humidity

V4 → Fan Control

V5 → Pump Control

Monitor system in real-time.

🌍 Applications

Smart Sericulture Farms

Agricultural Automation Systems

IoT-based Environmental Monitoring

Precision Farming Solutions

Academic IoT Demonstration Projects

🧠 Skills Demonstrated

IoT System Design

Embedded Systems Programming

Cloud Integration

Sensor Interfacing

Automation Logic Development

Real-time Monitoring Systems

👩‍💻 Author

Nithyashree S
Computer Science Engineering
Samsung Innovation Campus (SIC)
Cambridge Institute of Technology – North Campus

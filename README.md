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

🛠 Hardware Components

Raspberry Pi

DHT11 Temperature & Humidity Sensor

Relay Module

DC Fan

Water Pump

LED Indicator

Jumper Wires

💻 Software & Technologies

Python 3.11

Blynk IoT Platform (Cloud)

Raspberry Pi OS

Libraries Used

BlynkLib

adafruit_dht

RPi.GPIO

board

⚙️ System Architecture & Working

The DHT11 sensor continuously captures temperature and humidity readings.

The Raspberry Pi processes the sensor data in real time.

If:

Temperature > 25°C → Fan turns ON automatically

Humidity < 50% → Pump turns ON automatically

Live sensor readings and device status are transmitted to Blynk Cloud.

Users can monitor environmental data and manually override device controls through the Blynk mobile application.

📲 Blynk Virtual Pin Configuration
Virtual Pin	Function
V0	Temperature
V1	Humidity
V2	Fan Status
V3	Pump Status
V4	Fan Control
V5	Pump Control
V6	System Status
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

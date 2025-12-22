🌱 Greenhouse Automation using Arduino

An Arduino-based Greenhouse Automation System developed as part of the ECE-279 course project.
This project automatically monitors and controls key greenhouse parameters to reduce manual effort and improve plant growth efficiency.

📌 Project Overview

In traditional greenhouses, temperature, humidity, irrigation, and lighting are often managed manually.
This can lead to delays, human errors, and inconsistent growing conditions.

Our system uses sensors and automated control logic to continuously monitor environmental conditions and maintain optimal parameters in real time, ensuring healthier plant growth with minimal human intervention.

⚙️ Features
🔍 Automatic Monitoring

🌡️ Temperature

💧 Humidity

🌱 Soil moisture

💡 Light intensity

🔄 Automatic Control

Cooling fan for ventilation

Water pump for irrigation

Grow lights for artificial lighting

🖥️ System Capabilities

Live sensor data display on 16×2 LCD

Relay-based safe switching of high-power devices

Reduced manual intervention

Improved energy efficiency

🧰 Components Used

Arduino Uno R3

DHT22 Temperature & Humidity Sensor

Soil Moisture Sensor

LDR (Light Dependent Resistor)

4-Channel Relay Module

DC Fan

Water Pump

LED Grow Lights

16×2 LCD (with I2C module)

External 12V Power Supply

Jumper wires & breadboard

🔁 Working Principle

Sensors continuously collect data for temperature, humidity, soil moisture, and light intensity.

Arduino compares sensor readings with predefined threshold values.

Based on conditions:

Fan turns ON/OFF for temperature & humidity control

Pump turns ON/OFF based on soil moisture

Grow lights turn ON/OFF based on ambient light

Live sensor readings and device status are displayed on the LCD.

📊 LCD Display Format

T: Temperature (°C)

H: Humidity (%)

S: Soil moisture value

F / P / L: Fan, Pump, Light status (ON/OFF)

🧠 Learning Outcomes

This project provided hands-on experience in:

Embedded systems fundamentals

Sensor interfacing with Arduino

Relay-based actuator control

Automation logic implementation

Hardware wiring and debugging

Team-based project collaboration

🚀 Future Scope

IoT-based remote monitoring

Mobile app or web dashboard

Cloud-based data logging & analytics

SMS / push notification alerts

PID-based climate control system

👨‍💻 Team Members

Satyam Kumar

Prince Patel

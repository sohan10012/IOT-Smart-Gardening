# Smart Plant Watering System with ESP8266

## Overview
This project utilizes an ESP8266 (NodeMCU), a soil moisture sensor, and an LCD display to create a smart plant watering system. The system monitors soil moisture levels and visualizes real-time data in a Blynk app. Users can also activate a water pump to irrigate plants remotely.

![Project Overview](IOT-Smart-Gardening-REPORT.pdf)

## Table of Contents
1. [Introduction](#introduction)
2. [Materials](#materials)
3. [Circuit Diagram](#circuit-diagram)
4. [Arduino code](#arduino-code)
5. [Setup and Configuration](#setup-and-configuration)
6. [Usage](#usage)
7. [Contributing](#contributing)
   

## Introduction
In this project, we'll build a smart watering system that ensures your plants receive the right amount of water. The ESP8266 collects soil moisture data, displays it on an LCD, and allows control via a Blynk app.

## Materials
You'll need the following components:
- NodeMCU ESP8266
- Soil moisture sensor
- 16x2 LCD display
- Water pump
- Jumper wires
- Relay module
- Power supply

## Circuit Diagram
Connect the components as shown in the circuit diagram below:

![Circuit Diagram](https://github.com/sohan10012/IOT-Smart-Gardening/blob/main/Circuit-diagram.jpg)

## Arduino Code
   Use the following link to accesss the code :
   ![Arduino code](https://github.com/sohan10012/IOT-Smart-Gardening/tree/main/Arduino-code)

## Setup and Configuration
1. **Install Arduino IDE:**
   - Make sure you have the Arduino IDE installed.
   - Add the ESP8266 board support via the Board Manager.

2. **Library Installation:**
   - Install the necessary libraries:
     - Blynk (for app communication)
     - LiquidCrystal (for the LCD display)
     - Adafruit Unified Sensor (for the soil moisture sensor)

3. **Blynk App Setup:**
   - Create a new project in the Blynk app.
   - Add a Gauge widget to display soil moisture.
   - Add a Button widget to control the water pump.
   - Connect the phone and device with same mobile data and hotspot.
   
4. **Code Configuration:**
   - Upload the provided Arduino sketch (`smart_plant_watering.ino`) to your NodeMCU.
   - Configure your Wi-Fi credentials and Blynk authentication token.

5. **Assemble the Hardware:**
   - Connect the components according to the circuit diagram .
   - Place the soil moisture sensor in the plant's soil.

## Usage
1. Power up your NodeMCU.
2. Open the Blynk app and monitor soil moisture levels.
3. Press the button in the app to activate the water pump.

## Contributing
Contributions are welcome! Fork this repository, make improvements, and submit a pull request.
Contribution by - @sohan10012 <br>
                - @bharath_b_d_<br>
                - @tusharr0613<br>
                - @_vikashl<br>

---

Feel free to add more details, images, or troubleshooting tips to enhance your README. Happy gardening! 🌱💧

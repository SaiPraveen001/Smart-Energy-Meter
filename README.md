# 🔋 Smart Energy Meter using ESP32

This project is a smart energy monitoring and control system built using an ESP32 microcontroller. It measures real-time voltage and current, displays the values on an LCD, and sends the data to the Blynk IoT app. Additionally, it uses a relay module to control two connected bulbs remotely.

## 🛠️ Features
- Real-time voltage and current monitoring
- Energy data displayed on 16x2 LCD
- Wi-Fi-based IoT dashboard using Blynk
- Dual relay module to switch 2 bulbs ON/OFF
- Remote monitoring and control via smartphone

## 📷 Project Images
🔗 [View Full Album on Google Photos](https://photos.app.goo.gl/PedPN4UQQjrWGc3SA)

## 🔧 Hardware Components
- ESP32 Dev Module
- Voltage Sensor Module
- Current Sensor (ACS712 or similar)
- 2-Channel Relay Module
- 2 Bulbs
- 16x2 LCD with I2C module
- Jumper wires, breadboard

## 🧠 Software Used
- Arduino IDE
- Blynk IoT Platform
- C/C++

## 🔌 Circuit Connections (sample)
| Component          | ESP32 Pin  |
|-------------------|------------|
| Voltage Sensor     | A0         |
| Current Sensor     | A1         |
| LCD (via I2C)      | SDA - D21, SCL - D22 |
| Relay 1 (Bulb 1)   | D4         |
| Relay 2 (Bulb 2)   | D5         |

## 🚀 How It Works
1. ESP32 reads voltage and current from the sensors.
2. Values are shown on the 16x2 LCD.
3. Data is pushed to the Blynk app over Wi-Fi.
4. The user can turn ON/OFF two bulbs using relay switches through the Blynk interface.

## 📲 Mobile Interface
![Blynk UI Screenshot](images/blynk_ui.jpg) *(optional)*

## 👨‍💻 Author
[Sai Praveen](https://www.linkedin.com/in/YOUR-LINKEDIN/)  
B.Tech – Electrical & Electronics Engineering

## 📃 License
This project is open-source under the MIT License.

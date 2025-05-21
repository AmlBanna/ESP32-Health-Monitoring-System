# ESP32 Health Monitoring System

This project is a smart health monitoring system that uses the ESP32 microcontroller to measure and transmit vital health signs such as body temperature and ECG (heart rate) to a mobile dashboard using the Blynk IoT platform.

## 📷 Demo
![System Demo](media/system_demo.jpg)

## 📹 Video
A full demonstration video is available in the `media` folder.

## 🧰 Hardware Components
- **ESP32 Microcontroller** – core processing unit
- **MLX90614** – non-contact infrared temperature sensor
- **ECG Analog Sensor** – heart rate monitoring
- **Buzzer** – alert mechanism for flatline or heartbeat detection
- **WiFi** – built-in module in ESP32 for internet connectivity
- **Blynk IoT Platform** – remote real-time monitoring via smartphone

## 🔧 Software and Libraries
- Arduino IDE
- Blynk Library
- Adafruit_MLX90614 Library
- WiFi.h, Wire.h, BlynkSimpleEsp32.h

## 🚀 Features
- Real-time temperature and ECG monitoring
- Pulse detection algorithm with threshold calibration
- Emergency buzzer alerts for flatline
- Real-time remote monitoring via Blynk App (Temperature, ECG, BPM)

## 🧪 Challenges & Solutions
| Challenge               | Solution                                  |
|------------------------|-------------------------------------------|
| ECG signal noise        | Averaging and threshold calibration       |
| WiFi disconnection      | Auto-reconnect logic added                |
| False alarms            | Tuning thresholds and adding delay logic  |

## 🔮 Future Work
- Integrate with AI for health prediction (e.g., TensorFlow Lite)
- Add mobile push notifications
- Expand to support multi-patient monitoring
- Enable cloud storage using Firebase or Google Sheets
- Create a wearable version with rechargeable battery


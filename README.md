# Smart Fire Detection System 🔥

## 📌 Project Overview
This project is an IoT-based Smart Fire Detection and Alert System built using ESP32.  
It detects hazardous gases and temperature rise using sensors and sends real-time alerts through Blynk IoT platform.

---

## 🚀 Components Used
- ESP32
- MQ2 Gas Sensor
- DHT11 Temperature Sensor
- Buzzer
- Jumper Wires
- Breadboard

---

## 💻 Software Used
- Arduino IDE
- Blynk IoT Platform
- GitHub

---

## ⚙️ Working Principle
1. MQ2 gas sensor continuously monitors flammable gases like LPG, methane, and smoke.
2. DHT11 sensor monitors temperature changes.
3. ESP32 reads sensor data every 2 seconds.
4. If gas level or temperature crosses a threshold:
   - Buzzer turns ON
   - Alert is sent to Blynk app
5. Data is displayed in real-time on Blynk dashboard.

---

## 🔌 Pin Connections

| Component | ESP32 Pin |
|------------|------------|
| MQ2 (Analog Output) | GPIO34 |
| DHT11 (Data) | GPIO4 |
| Buzzer | GPIO5 |

---

## 🌡 Sensor Details

### MQ2 Gas Sensor
Detects:
- LPG
- Methane
- Hydrogen
- Propane
- Smoke

### DHT11 Temperature Sensor
- Temperature Range: 0°C to 50°C
- Accuracy: ±2°C

---

## 📱 IoT Integration
The system uses Blynk IoT to:
- Monitor sensor data remotely
- Send alerts
- Display real-time readings

---

## 🔮 Future Improvements
- Add flame sensor
- Add GSM module for SMS alerts
- Automatic sprinkler activation

---

## 📷 Circuit Diagram
![Circuit Diagram](<img width="507" height="376" alt="esp32_wiring" src="https://github.com/user-attachments/assets/fd2e2eb9-7194-4429-b2f3-4277d4c09822" />
)

---

## 👨‍💻 Author
Vineet K V

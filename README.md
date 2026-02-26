# 🔥 Smart Fire Detection & Alert System (IoT Based)

An IoT-enabled fire detection system built using ESP32 that monitors gas leakage and temperature changes in real time and sends alerts through the Blynk IoT platform.

---

## 📌 Project Objective

To design and implement a reliable fire detection prototype capable of:
- Detecting flammable gases and smoke
- Monitoring ambient temperature
- Sending real-time alerts remotely
- Triggering an audible alarm during emergencies

---

## 🧠 System Architecture

MQ2 Gas Sensor + DHT11 Temperature Sensor  
            ↓  
         ESP32  
            ↓  
        WiFi Network  
            ↓  
       Blynk IoT Dashboard  
            ↓  
     User Notification & Monitoring  

---

## ⚙️ Technologies Used

**Hardware**
- ESP32
- MQ2 Gas Sensor
- DHT11 Temperature Sensor
- Buzzer

**Software**
- Arduino IDE
- Embedded C++
- Blynk IoT
- GitHub

---

## 🔌 Pin Configuration

| Component | ESP32 Pin | Purpose |
|------------|------------|----------|
| MQ2 (Analog Out) | GPIO34 | Gas level reading |
| DHT11 (Data) | GPIO4 | Temperature reading |
| Buzzer | GPIO5 | Emergency alert |

---

## 🔍 Working Principle

- The MQ2 sensor continuously detects combustible gases such as LPG, methane, hydrogen, and smoke.
- The DHT11 sensor measures ambient temperature.
- ESP32 reads sensor data every 2 seconds.
- If gas concentration or temperature exceeds predefined threshold:
  - Buzzer activates
  - Alert is sent to Blynk dashboard
- Sensor readings are displayed in real time via WiFi.

---

## 🌡 Sensor Specifications

### MQ2 Gas Sensor
- Detects: LPG, Methane, Hydrogen, Propane, Smoke
- Output: Analog signal proportional to gas concentration
- Preheating required before stable readings

### DHT11 Temperature Sensor
- Temperature Range: 0°C to 50°C
- Accuracy: ±2°C
- Digital output signal

---

## 📲 IoT Integration

The system uses Blynk IoT to:
- Display live temperature and gas readings
- Send remote alerts
- Enable monitoring from anywhere with internet access

---

## 🚀 Future Enhancements

- Replace DHT11 with DHT22 for higher temperature range
- Add flame sensor for direct fire detection
- Integrate GSM module for SMS alerts
- Add automatic sprinkler activation system

---

## 💡 Key Learning Outcomes

- Embedded system programming
- GPIO configuration on ESP32
- Sensor calibration and threshold logic
- Cloud-based IoT dashboard integration
- Real-time data monitoring

---

## 📷 Circuit Diagram 

![Circuit Diagram](Circuit_Diagram/esp32_wiring.png)

---

## 👤 Author

Vineet K V
Computer Science Student  

# 🌾 IoT🌐 Based Agriculture🍃 Monitoring💻 System Using Arduino & Node MCU | WiFi📶

## 📌 Overview
This project showcases an **Internet of Things (IoT)** based smart agriculture monitoring system. It utilizes **Arduino UNO**, **NodeMCU (ESP8266)**, and various environmental sensors to monitor key agricultural parameters such as **soil moisture**, **temperature🌡️**, and **humidity💧**. The collected data is transmitted via **WiFi📶** to a cloud-based platform, allowing remote monitoring and management.

---

## 🧰 Components Used

- 🔌 **Arduino UNO**
- 🌐 **NodeMCU (ESP8266)**
- 🌱 **Soil Moisture Sensor**
- 🌡️ **DHT11 Sensor (Temperature & Humidity)**
- ⚡ **5V Relay Module**
- 💡 **LED/Bulb (for pump simulation)**
- 🔌 **Power Supply**
- 🔧 **Jumper Wires & Breadboard**

---

## 🔗 Connectivity

- The **NodeMCU** handles WiFi📶 communication and pushes data to **Thingspeak** or **Blynk Cloud**.
- The **Arduino UNO** interfaces with the sensors and controls the output.
- Data flow:  
  `Sensor Data 📤 → Arduino UNO 🧠 → NodeMCU 🌐 → Cloud ☁️`

---

## 📊 Features

- Real-time monitoring of:
  - 🌱 Soil Moisture
  - 🌡️ Temperature
  - 💧 Humidity
- Remote access via smartphone 📱 or PC 💻
- Automated irrigation control based on soil moisture
- Visual data display on Thingspeak 📈

---

## ⚙️ How it Works

1. Sensors collect environmental data 📡.
2. Arduino processes the input and sends it to NodeMCU.
3. NodeMCU uploads the data to the cloud ☁️.
4. The system can trigger a relay (pump simulation) based on soil moisture levels.
5. Users can monitor and control the system from anywhere 🌍.

---

## 🚀 Getting Started

### 🛠️ Setup Instructions

1. Connect sensors to the Arduino.
2. Connect Arduino to NodeMCU (via serial or logic level shifter).
3. Upload code to both microcontrollers using Arduino IDE.
4. Set up a Thingspeak or Blynk project.
5. Connect NodeMCU to WiFi and link to your cloud project.



---



---

## 🧠 Credits

- Special thanks to the open-source community ❤️

---

## 📝 License

This project is licensed under the MIT License. Feel free to use, modify, and distribute with attribution.

---


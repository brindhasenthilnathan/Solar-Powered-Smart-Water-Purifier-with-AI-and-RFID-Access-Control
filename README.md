# Solar-Powered-Smart-Water-Purifier-with-AI-and-RFID-Access-Control
A solar-powered smart water purification system using AI for quality monitoring and RFID for secure user access.
# AI-Enhanced Solar-Powered Smart Water Purification System
### with RFID-Based Access Control for Rural Communities

This project aims to build an **affordable, intelligent, solar-powered water purification kiosk** for rural regions. It uses **AI/TinyML**, **ESP32**, **RFID access control**, and **IoT-based monitoring** to ensure clean, safe drinking water.

---

## 🚀 Features

### 🔹 Water Purification
- Multi-stage filtration (sediment → carbon → UF/RO)
- UV-C LED microbial disinfection
- Flow + level monitoring

### 🔹 Sensor-Based Quality Monitoring
- Turbidity (NTU)
- TDS (ppm)
- pH
- Temperature
- Flow/usage logging

### 🔹 AI/TinyML Intelligence
- Water-quality anomaly detection
- Filter clogging prediction
- Contamination forecasting
- Energy optimization for solar usage

### 🔹 RFID-Based Access Control
- MFRC522 module
- User authentication
- Credit/quota management
- Usage history (volume, time, quality)

### 🔹 Solar Power System
- PV panels + MPPT + LiFePO4 battery
- Off-grid continuous operation
- Smart energy scheduling

### 🔹 Cloud/Local Dashboard
- Sensor visualization
- Alerts & notifications
- User management
- Remote firmware updates

---

## 🧱 System Architecture
![Block Diagram](docs/block_diagram.png)

---

## 🛠️ Technologies Used

### Hardware  
- ESP32 / ESP32-S3  
- RC522 RFID module  
- pH, TDS, Turbidity sensors  
- UV-C LED purifier  
- DC pump  
- Solar PV, MPPT, Battery  

### Software  
- Arduino / ESP-IDF  
- TensorFlow Lite Micro  
- Python (model training)  
- Flask/FastAPI backend  
- React/Vue dashboard (optional)

---

## 📂 Repository Structure
See folder layout in the root of this project for firmware, AI models, schematics, and docs.

---

## 📊 AI Model Pipeline
1. Collect sensor logs  
2. Clean + label dataset  
3. Train anomaly detection model  
4. Convert to **TensorFlow Lite Micro**  
5. Deploy to ESP32  

---

## ⚙️ Setup Instructions

### 1️⃣ Clone repo


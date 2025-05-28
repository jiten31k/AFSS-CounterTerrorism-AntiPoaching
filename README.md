# Autonomous Forest Surveillance System (AFSS)
### A Real-Time IoT-Based Solution for Counter-Terrorism and Anti-Poaching in Dense Forests

## 🔍 Problem Statement
Dense forest environments present significant challenges for detecting and tracking unauthorized individuals such as terrorists and poachers. In regions like Jammu and Kashmir, thick vegetation, rugged terrain, and limited connectivity provide natural cover for hostile actors. Incidents like the April 2025 Pahalgam attack highlight the urgent need for an autonomous, real-time monitoring solution to improve forest surveillance and safety.

## 🎯 Project Objective
The **Autonomous Forest Surveillance System (AFSS)** aims to develop a robust, real-time surveillance device that:
- Detects human presence in dense forest areas.
- Differentiates between humans and wildlife using smart sensors.
- Pinpoints exact GPS locations.
- Sends real-time alerts to authorities via GSM/LoRa networks.
- Functions autonomously in remote, low-connectivity environments.

## ⚙️ Key Features
- ✅ Real-time human detection using PIR and other sensors.
- ✅ GPS-based location tracking.
- ✅ Wireless data transmission using GSM/LoRa modules.
- ✅ Differentiation between humans and animals to reduce false alarms.
- ✅ Designed for harsh, outdoor, forest environments.
- ✅ Use case modeled on real-world incidents for high-impact relevance.

## 🛠️ Technology Stack & Components
### 🔌 Hardware:
- Arduino UNO/ESP32
- PIR Motion Sensor
- GPS Module (Neo-6M or equivalent)
- GSM Module (SIM800L) / LoRa Module
- Power Supply (Battery + Solar Backup)
- Buzzer or Alert System (Optional)
- Relay Modules (Optional)

### 💻 Software:
- Arduino IDE
- Embedded C/C++
- IoT Communication Protocols (UART, GSM, LoRa)
- Blynk (Optional for remote dashboard)
- Python (for backend processing if applicable)

## 🧩 System Architecture
- Sensors → microcontroller → GPS → wireless module → alert system.

## 🖼️ Use Case Scenario
- **Location:** Forest regions like Pir Panjal, Jammu & Kashmir.
- **Threat:** Hidden terrorist camps, poachers harming wildlife.
- **Solution:** AFSS devices deployed across entry points and vulnerable locations transmit real-time alerts upon human detection, allowing rapid military or forest officer response.

## 🚀 How to Set Up
1. **Clone the Repository**
   ```bash
   git clone https://github.com/jiten31k/AFSS-CounterTerrorism-AntiPoaching.git
   cd AFSS-CounterTerrorism-AntiPoaching

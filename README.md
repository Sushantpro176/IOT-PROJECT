# IOT-PROJECT
# 💧 Smart Irrigation System using Cisco Packet Tracer

## 📌 Aim
To develop a smart irrigation system capable of monitoring soil moisture levels and automatically triggering water sprinklers to optimize water usage in agricultural fields, using Cisco Packet Tracer.

---

## 📝 Problem Statement
Traditional irrigation methods often lead to inefficient water usage due to the lack of real-time data. This system addresses the issue by using IoT-based components to detect low soil moisture and activate sprinklers accordingly, minimizing water wastage and ensuring proper crop hydration.

---

## 🔭 Scope of the Solution
- Real-time monitoring of soil water levels using sensors
- Automated control of sprinklers based on water level data
- Mobile-based control via smartphone
- Scalable and customizable for different farm layouts
- Fully simulated using Cisco Packet Tracer

---

## 🧠 Overview/Architecture of the Solution

### Components Used:
- **2 x Water Level Monitor (Moisture Sensors)**
- **4 x Lawn Sprinklers (Actuators)**
- **1 x Home Gateway (DLC100)**
- **1 x Smartphone (for monitoring/control)**
- **Wireless connectivity for all devices**

### Architecture Flow:
1. Water Level Monitors detect moisture levels in the soil.
2. Sensors send data to the **DLC100 Home Gateway**.
3. If moisture is below threshold, the Home Gateway activates the corresponding **Lawn Sprinklers**.
4. Once the soil moisture is sufficient, the sprinklers automatically turn off.
5. A **Smartphone** is connected for remote control and monitoring of the irrigation process.

---

## 🧰 Required Components
- Smart Water Level Monitor x2  
- Smart Lawn Sprinkler x4  
- Home Gateway (DLC100) x1  
- Smartphone (for control interface)  
- Wireless network (simulated)

---

## 🧪 Simulated Circuit
![Simulation Screenshot](![Screenshot 2025-07-06 163306](https://github.com/user-attachments/assets/f68f7bde-0f02-43db-b4bf-f7b2eaaf319a)
)

The image above shows the logical layout of the irrigation system:
- Two water level monitors are placed in the field.
- Four lawn sprinklers are positioned to cover different zones.
- All components are wirelessly connected to the Home Gateway.
- The smartphone acts as a remote controller.


## 📂 Folder Structure
```bash
Smart-Irrigation-System/
├── README.md
├── Screenshot 2025-07-06 163306.png
├── demo_video.mp4
├── simulation.pkt

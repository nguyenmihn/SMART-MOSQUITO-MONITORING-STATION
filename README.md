# 🦟 SMART MOSQUITO MONITORING STATION

**An IoT-integrated hardware system for environmental and mosquito activity monitoring. Developed to meet the technical and functional requirements of Partner A (as specified in the demo prototype).**

> ⏱ Duration: Feb 2025 – Present  
> 🤝 In collaboration with **Vietan Group** and **IoT Vision**  
> 🛠️ Role: Hardware Design, Embedded Firmware Development, Cloud Integration

---

## 📌 Objectives

The project focuses on the **research, development, and deployment** of a smart mosquito monitoring station, including:

1. **Designing electronic schematics, PCB layout**, and **embedded firmware** for sensor integration and IoT connectivity.
2. **Developing mechanical enclosures** with IP-rated protection for outdoor deployment in high-humidity environments.
3. **Prototyping and testing** to meet the full functional scope as specified in the demo system provided by Partner A.

---

## 🧩 Functional & Technical Requirements

### 🔋 Power Supply
- Operates on **12VDC**
- Supports **multiple power sources**: direct supply, lithium battery, **solar panel**

### 🌧 Durability
- **IP67 rating**: water- and dust-proof, suitable for **outdoor environments** with high humidity

### ⚡ Energy Efficiency
- Low-power design with **adjustable data transmission intervals** (minimum every 15 minutes)
- Optimized firmware for power saving

### 📡 Data Communication
- **4G SIM-based communication** for cloud transmission
- Configurable data transmission interval to balance reporting frequency and energy usage

### 🌡️ Environmental Sensing
- Real-time acquisition of:
  - **Temperature**
  - **Humidity**
  - **Dew Point**
  - **Ambient Light**
  - **GPS Location**
  - **Power source status** & **battery voltage**
  - **Mosquito count**, **small insect count**, **large insect count**

---

## 🦟 Mosquito Detection Mechanism

- Utilizes **infrared signal analysis** to detect and **classify insects based on body size and wingbeat pattern**  
- Distinguishes between:
  - Small insects
  - Large insects
  - Adult mosquitoes  
- Signal classification based on unique **infrared signatures** of different insect sizes and species

---

## 🧪 Additional Features

- **CO2 baiting compatibility**:
  - Supports integration with **CO2 attractant systems**, mosquito attractant lures, and collection chambers
- **Modular insect container**:
  - Allows mosquito entrapment for physical count or lab analysis
- **Custom expandability**:
  - Compatible with demo unit and additional modules provided by Partner A

---

## 🔧 Technical Stack

- **Microcontroller**: ESP32 with FreeRTOS for multitasking
- **Firmware**: C/C++, RTOS-based task scheduling
- **PCB Design**: Altium Designer
- **Mechanical CAD**: SolidWorks
- **Connectivity**: 4G SIM module, GPS, I2C, UART sensors
- **Cloud**: IoT Vision platform or custom endpoint

---

## 📍 Applications

- Public health monitoring (e.g., dengue, malaria surveillance)
- Entomological research and vector control
- Smart environmental sensing systems
- Outdoor agricultural and municipal pest monitoring

---

## 📄 License

This project was developed under partnership with **Vietan Group** and **IoT Vision**. Certain hardware schematics and signal processing algorithms may be proprietary or confidential.

---

## ✉ Contact

Lead Developer: **Nguyen Minh**  
📧 Nminh59001@gmail.com  
🔗 https://github.com/nguyenmihn

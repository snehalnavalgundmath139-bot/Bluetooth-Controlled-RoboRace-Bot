# 🚗 Bluetooth Controlled RoboRace Bot
### Command-Based Robotic Control System using Arduino Mega

---

## 🧠 Overview
A wireless robotic system designed for RoboRace applications, where movement is controlled in real-time through Bluetooth commands.  
The system demonstrates **structured decision-making logic**, forming a foundational layer for intelligent robotic control.

---

## ⚙️ System Flow

User Input → Bluetooth (HC-05) → Arduino Mega → Decision Logic → Motor Drivers → Robot Movement

---

## 🧩 Hardware

- Arduino Mega 2560  
- HC-05 Bluetooth Module  
- 2 × L298N Motor Drivers  
- 4 × DC Gear Motors (12V, 500 RPM)  
- 4S2P Li-ion Battery (~14.8V)  
- Buck Converter (5V)  

---

## 🧠 Control Logic

The robot operates on a **command-driven decision system**:

| Input | Action |
|------|--------|
| F | Forward |
| B | Backward |
| L | Left |
| R | Right |
| S | Stop |

Each command is processed using conditional logic and mapped to motor actions, enabling real-time response.

---

## 🔄 Working

1. User sends command via mobile app  
2. HC-05 receives Bluetooth signal  
3. Arduino reads input (Serial1)  
4. Decision logic selects movement  
5. Motor driver actuates motors  

---

## 💻 Implementation Highlights

- Real-time serial communication  
- Modular motor control functions  
- Continuous command execution loop  
- Stable 4-motor drive system  

---

## 🚀 Features

- Wireless control  
- Instant response  
- Simple and scalable design  
- Reliable movement control   

---

## 🔮 Future Scope

- Computer vision-based navigation  
- Obstacle detection  
- AI-based decision systems  

---

## 📷 Project Assets

- Circuit Diagram  
- Flowchart  
- App Interface  
- Robot Images  
- Demo Video  

---

## 🏁 Conclusion
A clean and efficient **decision-based robotic control system** that serves as a strong base for developing AI-enabled autonomous robots.

---


---
---

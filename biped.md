# 🤖 Biped Robot

## 📌 Overview
This project presents the design and development of a **bipedal walking robot** actuated using six servo motors and controlled wirelessly via a Bluetooth communication module (HC-05). The system is built using the **ESP32 microcontroller**, enabling efficient real-time control and communication.

The mechanical structure is designed using **SolidWorks**, ensuring precise alignment, structural stability, and optimized weight distribution. The robot mimics basic human walking through coordinated servo movements and predefined gait sequences.

---

## 🎯 Objectives
- Design a **bipedal robot** capable of walking  
- Implement **wireless control using Bluetooth**  
- Utilize **ESP32 for real-time processing and control**  
- Develop a **CAD-based mechanical design using SolidWorks**  
- Study **gait generation and stability** in biped systems  

---

## 🛠️ Hardware Components
- **ESP32 Microcontroller**  
- **HC-05 Bluetooth Module**  
- **6 × Servo Motors (MG90S)**  
- **Power Supply (Battery Pack)**  
- **Custom Mechanical Frame (SolidWorks Designed)**  

---

## 🧠 Software & Tools
- **Arduino IDE** (for programming ESP32)  
- **SolidWorks** (for mechanical design)  

---

## ⚙️ System Architecture
1. User sends commands via smartphone (Bluetooth)
2. HC-05 receives data and transmits to ESP32 via UART
3. ESP32 processes commands and executes gait logic
4. PWM signals control servo angles
5. Coordinated servo motion produces walking

---

## 🚶 Working Principle
- The robot uses **6 servo motors** for joint movement:
  - Hip joints → balance and lateral motion  
  - Knee joints → stepping motion  

- Walking is achieved through:
  - Alternating leg movement  
  - Center of gravity shifting  
  - Predefined gait sequences  

---

## 🔍 Gait Design
- One leg lifts while the other supports the body  
- Hip servos shift weight for balance  
- Knee servos control step height  
- Precise timing ensures smooth locomotion  

---

## ✨ Features
- Wireless Bluetooth control  
- Real-time response using ESP32  
- CAD-optimized structure (SolidWorks)  
- Modular and scalable design  
- Lightweight and compact  

---

## ⚠️ Challenges Faced
- Maintaining balance in biped structure  
- Synchronizing multiple servos  
- Power fluctuations due to servo load  
- Mechanical alignment issues  

---

## 🚀 Applications
- Humanoid robotics research  
- Educational robotics projects  
- Motion and gait analysis  
- Embedded and IoT robotics systems  

---

## 🔮 Future Enhancements
- Add **IMU (Gyroscope + Accelerometer)** for balance  
- Implement **Inverse Kinematics**  
- Use **ESP32 built-in Bluetooth** (remove HC-05)  
- Add **AI-based gait optimization**  
- Autonomous navigation using sensors  

---

## 📸 Project Preview
<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/7f6d8db8-2421-4e39-8351-041036bc8a3f" />


---

## 🏁 Conclusion
This project successfully demonstrates a **Bluetooth-controlled biped robot using ESP32**, capable of executing walking motions through coordinated servo control. It provides strong insights into robotics, embedded systems, and mechanical design, forming a solid base for advanced humanoid systems.

---

## 👩‍💻 Authors
- Nishkala  
- (Add your team members here)

---

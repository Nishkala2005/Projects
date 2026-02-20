# 🤖 High-Speed Line Following Robot using Arduino Nano  
### 16-IR Sensor Array | 600 RPM N20 Motors | Encoder Feedback | PID Control

---

## 📌 Overview

This project implements a high-speed autonomous Line Following Robot designed for precision tracking and competition-level performance.

The robot uses a 16-element IR sensor array for fine position detection and 600 RPM N20 geared motors with encoders for accurate speed feedback. A PID control algorithm is implemented to ensure stable and smooth tracking at high speeds.

---

## 🛠️ Hardware Components

- Arduino Nano (ATmega328P)
- 16-Channel IR Sensor Array
- TB6612FNG Dual Motor Driver
- 2 × 600 RPM N20 Geared Motors
- Quadrature Encoders (Motor-mounted)
- Li-ion Battery Pack
- Robot Chassis
- Custom PCB / Wiring Layout

---

## 🔍 Sensor Array Configuration

The robot uses a 16-element IR array arranged linearly:

S1 S2 S3 S4 S5 S6 S7 S8 S9 S10 S11 S12 S13 S14 S15 S16

- Each sensor detects black (LOW) or white (HIGH)
- A weighted average method is used to determine line position
- Higher resolution tracking compared to 3 or 5 sensor systems

---

## ⚙️ Working Principle

1. IR array reads surface reflectance.
2. A weighted position value is calculated.
3. Error = Desired Position – Current Position
4. PID controller computes correction.
5. Motor speeds are adjusted using PWM.
6. Encoder feedback ensures speed stability.

---

## 🧠 Control Strategy

### Line Position Calculation

A weighted average algorithm is used:

Position = Σ (SensorValue × Weight) / Σ (SensorValue)

This provides high-resolution deviation detection.

---

### PID Controller

Correction is calculated using:

Correction = (Kp × Error) + (Ki × Integral) + (Kd × Derivative)

Where:
- Kp → Proportional gain
- Ki → Integral gain
- Kd → Derivative gain

The correction value dynamically adjusts left and right motor speeds.

---

## 🔄 Motor Control with Encoder Feedback

- Quadrature encoders measure wheel rotation.
- Closed-loop speed control maintains consistent velocity.
- Reduces drift during high-speed turns.
- Improves repeatability and accuracy.

---

## 🔌 Pin Configuration (Example)

### IR Array
Connected via digital input pins or multiplexed configuration.

### Motor Driver
| TB6612FNG | Arduino |
|-----------|---------|
| PWMA | PWM Pin |
| PWMB | PWM Pin |
| AIN1 | Digital Pin |
| AIN2 | Digital Pin |
| BIN1 | Digital Pin |
| BIN2 | Digital Pin |
| STBY | Digital Pin |

### Encoders
| Encoder | Arduino |
|----------|----------|
| Left A | Interrupt Pin |
| Left B | Digital Pin |
| Right A | Interrupt Pin |
| Right B | Digital Pin |

---

## 🚀 Features

- 16-sensor high-resolution tracking
- PID-based dynamic correction
- Closed-loop motor speed control
- High-speed operation (600 RPM motors)
- Competition-ready design
- Expandable to maze solving or path memory

---

## 📈 Performance Highlights

- Smooth cornering at high speed
- Minimal oscillation
- Stable line recovery
- Accurate tracking on sharp curves

---

## 📷 Project Images

(Add robot image here)

---

## 📹 Demo Video

(Add YouTube or Drive link here)

---

## 📚 Skills Demonstrated

- Embedded C Programming
- PID Control Systems
- Encoder Interfacing
- Real-Time Feedback Systems
- PWM Motor Control
- Sensor Array Data Processing
- Closed-Loop Control
- Robotics System Integration

---

## 👩‍💻 Author

Nishkala Bhat  
Electronics and Communication Engineering

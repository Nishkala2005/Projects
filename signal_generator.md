# Analog Signal Generator with PCB Implementation

## 📌 Project Overview

This project focuses on the design and implementation of a high-performance analog signal generator capable of producing multiple waveform outputs, including sine, square, and triangular waves. The system is built using a **TL084 operational amplifier**, leveraging its high input impedance, low noise, and wide bandwidth characteristics for stable signal generation.

The signal generator is designed to operate over a **wide frequency range of 0.1 Hz to 200 kHz**, with adjustable amplitude control, making it suitable for laboratory testing, signal conditioning, and educational applications.

---

## 🎯 Objectives

* Design a multi-waveform analog signal generator using discrete analog components
* Achieve wide frequency tunability with stable waveform output
* Implement amplitude control for flexible signal conditioning
* Validate the design through simulation and hardware testing
* Develop a compact and noise-optimized PCB for practical deployment

---

## ⚙️ System Architecture

The signal generator is based on a classic **integrator + Schmitt trigger feedback loop**, implemented using the TL084 op-amp.

### Key Functional Blocks:

* **Schmitt Trigger (Comparator with Hysteresis)**
  Generates a stable square wave output

* **Integrator Circuit**
  Converts square wave into a triangular waveform

* **Waveform Shaping Circuit**
  Converts triangular waveform into an approximate sine wave

* **Amplitude Control Stage**
  Allows user-defined output voltage levels

---

## 🔧 Components Used

* TL084 Quad Operational Amplifier
* Resistors (precision for stability)
* Capacitors (for timing and filtering)
* Potentiometers (frequency and amplitude control)
* Power supply circuit (regulated DC supply)

---

## 📊 Features

* Multi-waveform output: **Sine, Square, Triangular**
* Wide frequency range: **0.1 Hz – 200 kHz**
* Adjustable amplitude control
* Stable and low-noise output
* Compact PCB design for real-world usability

---

## 🧪 Simulation & Validation

* The circuit was initially designed and tested using **LTspice**
* Waveform accuracy, frequency response, and stability were verified
* Iterative optimization was performed before hardware implementation

---

## 🖥️ PCB Design

* Designed using **KiCad**
* Focused on:

  * Signal integrity
  * Noise reduction
  * Proper grounding techniques
* Compact layout ensuring minimal interference between analog stages

---

## 🔬 Hardware Implementation & Testing

* Assembled the circuit on a custom PCB
* Tested output waveforms using an oscilloscope
* Debugged issues related to:

  * Noise and distortion
  * Frequency drift
* Achieved stable and reliable waveform generation across the target frequency range
<img width="2160" height="3840" alt="image" src="https://github.com/user-attachments/assets/bbe0fb7d-256e-435b-a5e4-7760589cc97b" />


---

## 🚀 Applications

* Signal testing and debugging in electronic circuits
* Educational tool for understanding waveform generation
* Input source for analog signal conditioning systems
* Laboratory function generator alternative

---

## 📈 Key Achievements

* Successfully implemented a **wideband analog signal generator**
* Demonstrated effective use of **op-amp based waveform synthesis**
* Achieved reliable hardware performance matching simulation results
* Developed an industry-relevant **PCB-based analog system**

---

## 🔮 Future Improvements

* Improve sine wave accuracy using advanced shaping techniques
* Add digital control for frequency tuning (hybrid system)
* Integrate display/interface for user interaction
* Extend frequency range and output stability

---

## 👩‍💻 Author

**Nishkala Bhat**
Electronics and Communication Engineering

---

## 📎 Tools & Software

* LTspice (Simulation)
* KiCad (PCB Design)

---

# EEG-Based Seizure Detection using Wavelet Transform and CNN

## 📌 Project Overview

This project focuses on the development of an advanced **EEG-based seizure detection system** by combining traditional **Digital Signal Processing (DSP)** techniques with modern **Machine Learning (ML)** approaches. Initially, seizure detection was performed using **Discrete Wavelet Transform (DWT)** and statistical feature extraction. The system was later enhanced using a **Convolutional Neural Network (CNN)** model to improve detection accuracy, robustness, and automation.

The system utilizes EEG data from the **CHB-MIT Scalp EEG Database**, enabling reliable detection of abnormal brain activity associated with epileptic seizures. The hybrid approach ensures both interpretability (via DSP) and high performance (via CNN-based learning).

---

## 🎯 Objectives

* Develop a reliable system for early detection of epileptic seizures using EEG signals
* Apply **DWT-based multi-resolution analysis** for effective signal decomposition
* Extract meaningful statistical features from EEG signals
* Enhance detection performance using a **CNN-based deep learning model**
* Validate the system against clinically annotated EEG datasets

---

## ⚙️ Methodology

### 🔹 Data Acquisition

* Dataset: **CHB-MIT Scalp EEG Database**
* EEG recordings segmented into **10-second windows** for analysis

### 🔹 Signal Processing (DSP Approach)

* Applied **Discrete Wavelet Transform (DWT)** for time-frequency analysis

* Extracted key statistical features:

  * Energy
  * Variance
  * Entropy

* Implemented an **adaptive threshold-based detection mechanism**

* Used **logical AND rule** for identifying abnormal EEG segments

### 🔹 Machine Learning Enhancement

* Developed a **Convolutional Neural Network (CNN)** model for automated seizure classification
* Input: Preprocessed EEG signals / feature representations
* CNN Capabilities:

  * Automatic feature learning
  * Improved classification accuracy
  * Robust detection under noisy conditions

---

## 🧠 System Architecture

1. EEG Data Input
2. Preprocessing (Filtering & Segmentation)
3. DWT-Based Decomposition
4. Feature Extraction
5. CNN-Based Classification
6. Seizure Detection Output

---

## 📊 Results & Performance

* Analyzed multiple EEG recordings including **Patient 3 (chb01-03.edf)**
* Detected seizure interval: **3020–3030 seconds**
* Clinically annotated interval: **2996–3036 seconds**
* Achieved close alignment with ground truth annotations

### ✅ Key Outcomes:

* Accurate seizure detection using hybrid DSP + CNN approach
* Improved robustness compared to threshold-only methods
* Effective handling of non-stationary EEG signals

---

## 🚀 Features

* Hybrid model combining **signal processing and deep learning**
* Multi-resolution EEG analysis using DWT
* Automated feature learning via CNN
* High detection accuracy with reduced false positives
* Scalable and adaptable for real-time applications

<img width="716" height="696" alt="image" src="https://github.com/user-attachments/assets/3f503fc2-13b2-4ba5-a71e-f8d475097f89" />

---

## 🧪 Tools & Technologies

* MATLAB 
* EEG Dataset: CHB-MIT Scalp EEG Database

---

## 🔬 Applications

* Clinical decision support systems
* Epilepsy monitoring and diagnosis
* Real-time patient monitoring systems
* Brain-computer interface (BCI) research

---

## 📈 Key Achievements

* Successfully integrated **DWT-based DSP techniques with CNN**
* Demonstrated high accuracy in seizure detection
* Validated model performance against real clinical EEG data
* Developed an industry-relevant intelligent healthcare solution

---

## 🔮 Future Enhancements

* Real-time seizure detection using embedded systems
* Integration with wearable EEG devices
* Deployment on edge devices for portable healthcare solutions
* Use of advanced deep learning models (LSTM, Transformer-based models)

---

## 👩‍💻 Author

**Nishkala Bhat**
Electronics and Communication Engineering

---

## 📎 Keywords

EEG, Seizure Detection, Wavelet Transform, DWT, CNN, Deep Learning, Feature Extraction, Digital Signal Processing

---

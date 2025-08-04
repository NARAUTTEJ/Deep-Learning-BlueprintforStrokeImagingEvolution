# Innovations in Stroke Identification  
### A Machine Learning-Based Diagnostic Model Using Neuroimages  

## 📌 Overview
This project presents a deep learning-based diagnostic system to identify stroke conditions using neuroimages. By combining the robust feature extraction of **ResNet** and the lightweight efficiency of **MobileNet**, this diagnostic model aims to improve the speed and accuracy of stroke detection, providing clinicians with a powerful AI-assisted tool.

---

## 🧠 Motivation
Traditional stroke diagnosis methods, while effective, often face challenges such as time delays, human error, and inefficiency. Deep learning models have shown promising potential in automating and improving diagnostic accuracy. This project seeks to bridge the gap by delivering a scalable and accurate solution for real-world clinical use.

---

## 🎯 Objectives
- Accurately classify neuroimages into **Normal** and **Stroke** categories.
- Leverage **ResNet** for deep feature extraction and **MobileNet** for lightweight inference.
- Improve diagnostic speed and consistency.
- Provide a deployable web interface for clinicians to interact with the model.

---

## 🛠️ Tech Stack

| Component               | Technology                                   |
|------------------------|----------------------------------------------|
| Programming Language   | Python 3.6+                                  |
| Deep Learning Framework| PyTorch, Keras, TensorFlow                   |
| Web Framework          | Flask                                         |
| Frontend               | HTML, CSS, Bootstrap, JavaScript             |
| Deployment             | XAMPP Server                                 |
| Database               | MySQL                                        |
| IDE                    | PyCharm / VSCode                             |

---

## 🧪 Methodology

### 📷 Data Pipeline
1. **Data Collection:** Neuroimages collected and categorized as Stroke or Normal.
2. **Preprocessing:** Resized, normalized, and augmented for robustness.
3. **Splitting:** 80% training, 20% testing.

### 🧠 Model Training
- **MobileNet:** Lightweight model for faster prediction on edge devices.
  - Achieved **92%** training accuracy.
- **ResNet:** Deep residual model for extracting complex patterns.
  - Achieved **94%** training accuracy.

---

## 🗂️ Modules

### 🔐 Admin/User System
- **Register/Login**
- **Image Upload**
- **Real-time Prediction**
- **Result Display**

### 🧠 Backend Logic
- Loads trained `.pt` model files.
- Predicts and displays results using Flask-based backend.

---

## 📊 Architecture & Diagrams
- UML Diagrams: Use Case, Class, Sequence, Collaboration, Component
- ER Diagram & Activity Diagram
- Deployment & Flow Charts

---

## 💡 Features
- Fast and accurate stroke classification
- Lightweight MobileNet architecture for real-time performance
- Robust ResNet for deeper analysis
- Secure user interface for clinicians
- Scalable model deployment

---

## ✅ Future Enhancements
- Integrate with PACS or hospital imaging systems.
- Clinical validation on real-world hospital datasets.
- Mobile app interface for on-device inference.
- Extend to other brain disorders (e.g., hemorrhage, tumors).

---

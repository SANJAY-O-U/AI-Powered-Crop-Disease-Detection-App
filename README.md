# 🌱 AI-Powered Crop Disease Detection App

An AI-driven mobile application designed to help farmers detect crop diseases at an early stage using leaf image analysis. The system leverages Machine Learning (CNN) to classify crop diseases and provides instant treatment and prevention recommendations.

This project focuses on solving real-world agricultural challenges in India.

---

## 🚜 Problem Statement
Farmers often face heavy crop losses due to late or incorrect identification of crop diseases. Limited access to agricultural experts and dependency on traditional methods result in improper pesticide usage and reduced yield.

---

## 💡 Solution
The application allows farmers to capture or upload images of infected crop leaves. These images are analyzed using a trained AI model, which identifies the disease and suggests appropriate remedies and preventive measures.

---

## ⚙️ Features
- Leaf image upload or capture
- AI-based crop disease detection
- Instant disease diagnosis
- Treatment & prevention suggestions
- Simple and farmer-friendly interface
- Scalable architecture

---

## 🏗️ System Architecture
Mobile App (Android)
|
| Image Upload
↓
Flask Backend (Python)
|
| AI Inference
↓
CNN Model (TensorFlow)
---

## 🛠️ Tech Stack
- **Frontend:** Android (Java)
- **Backend:** Python, Flask
- **AI Model:** CNN (TensorFlow / Keras)
- **Dataset:** PlantVillage Dataset
- **API:** REST API

---

## 📂 Project Structure
AI-Crop-Disease-Detection/
│
├── backend/
│ ├── app.py
│ ├── model.h5
│ └── requirements.txt
│
├── android-app/
│ ├── MainActivity.java
│ └── activity_main.xml
│
├── model-training/
│ └── train_model.py
│
└── README.md



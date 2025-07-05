# 🚗 Smart Parking Spot Detection using Computer Vision

An AI-powered parking lot monitoring system that uses Computer Vision to detect whether parking spots are **empty** or **occupied** in real-time. Built using Python, OpenCV, Scikit-learn, and classical machine learning techniques.

---

## 📸 Project Overview

This project uses an SVM classifier to distinguish between images of **empty** and **occupied** parking spaces. The model is trained using a labeled image dataset and can be applied to real-time CCTV footage or individual frames to monitor parking space availability.

---

## ✅ Features

- 🔍 Image classification using SVM
- 📂 Labeled dataset: `empty/` and `not_empty/`
- 🧠 Image preprocessing with resizing and flattening
- 📈 Accuracy evaluation using GridSearchCV
- 💾 Trained model saved as `model.p` for later use

---

## 🧠 Tech Stack

- Python 3.x
- OpenCV
- Scikit-learn
- NumPy
- Scikit-Image
- Pickle

---

## 📂 Dataset

The dataset contains two classes:

- `empty` — Parking slots without vehicles
- `not_empty` — Parking slots with vehicles

> 🗂️ **Full dataset is not uploaded to GitHub due to size limits.**  
> You can download it from the link below and place it inside a `dataset/` folder in your project directory.

🔗 **[Download Dataset (Google Drive)](https://drive.google.com/drive/folders/1H1z6pJLPyY7dLWzZEW5w6qJoHJZzcZw-?usp=drive_link)**


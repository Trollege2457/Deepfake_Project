# Deepfake_Project
# 🎭 Deepfake Detection Using XceptionNet on Audio and Video Modalities
This project aims to detect deepfake content in both audio and video formats using the XceptionNet deep learning model. It was developed as part of a group project to explore how a common CNN architecture can be used effectively across multiple modalities.

---

## 📌 Objective
- Detect fake vs real content in both video and audio
- Use XceptionNet for robust binary classification

---

## 🛠️ Technology Stack
- **Programming Language:** Python  
- **Libraries:** TensorFlow, Keras, NumPy, OpenCV, librosa  
- **Model:** XceptionNet  
- **Development Tools:** Jupyter Notebook, Google Colab  
- **Data Augmentation:**  
  - Video: ImageDataGenerator  
  - Audio: MFCC conversion 

---

## 🧠 Project Overview
XceptionNet — a CNN architecture

### 🔹 Video:
- Frame extraction 
- Data augmentation
- XceptionNet training with early stopping and cross-entropy loss

### 🔹 Audio:
- Audio converted to MFCC images
- Data augmentation
- Trained on XceptionNet

---

## 👥 Team Roles

- **Vidhi & Navneet:**  
  - Audio dataset creation, MFCC transformation, model training and evaluation

- **Arushi & Sohamm:**  
  - Video preprocessing, model tuning, evaluation

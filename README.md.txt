# 🧠 AI-Powered Medical Image Analysis System

## 📌 Overview

This project implements an AI-powered medical image analysis system that detects pneumonia from chest X-ray images using deep learning.

The model uses **MobileNetV2 Transfer Learning** to classify medical images into:

- NORMAL
- PNEUMONIA

This system simulates real-world hospital diagnostic workflows.

---

## 🏥 Problem Statement

Manual diagnosis of chest X-ray images is time-consuming and prone to human error.

Hospitals generate thousands of X-ray images daily.

This project uses deep learning to:

- Automate pneumonia detection
- Reduce diagnosis time
- Assist radiologists
- Improve accuracy

---

## 🎯 Objectives

- Build an AI model for pneumonia detection
- Use transfer learning for medical image classification
- Visualize performance metrics
- Simulate real healthcare workflows

---

## 🧰 Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 📂 Dataset

Dataset Used:

Chest X-ray Pneumonia Dataset

Source:

Kaggle

Contains:

- NORMAL chest X-rays
- PNEUMONIA chest X-rays

Dataset Link:

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

---

## 🏗️ Project Architecture

Chest X-ray Image
↓
Preprocessing
↓
MobileNetV2 CNN
↓
Classification
↓
Prediction
↓
Visualization


---

## 📁 Project Structure

AI-Medical-Image-Analysis/
│
├── notebook/
│ └── AI_Medical_Image_Analysis.ipynb
│
├── models/
│ └── pneumonia_model.h5
│
├── outputs/
│ ├── accuracy_plot.png
│ ├── loss_plot.png
│ └── confusion_matrix.png
│
├── images/
│
├── README.md
├── requirements.txt
├── .gitignore


---

## ▶️ How to Run

1. Clone repository

git clone https://github.com/adityatamhanedev/AI-Medical-Image-Analysis.git

2. Open notebook

Run in:

Google Colab

3. Train model

Run all cells.

---

## 📊 Results

Model Performance:

- Training Accuracy: ~95%
- Validation Accuracy: ~94%

Generated Outputs:

- Accuracy Plot
- Loss Plot
- Confusion Matrix

---

## 🖼️ Output Screenshots

### Sample Images

(Add image)

### Model Training

(Add image)

### Confusion Matrix

(Add image)

### Prediction Output

(Add image)

---

## 🚀 Future Improvements

- Deploy using Streamlit
- Add Grad-CAM visualization
- Multi-class disease detection
- Web-based prediction system

---

## 🧠 Learning Outcomes

- Transfer Learning
- Medical Image Processing
- CNN Model Training
- Model Evaluation
- Deep Learning Deployment

---

## 👨‍💻 Author

Aditya Tamhane
GitHub: https://github.com/adityatamhanedev
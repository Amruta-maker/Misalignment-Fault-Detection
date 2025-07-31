# Misalignment-Fault-Detection

This repository supports the research article:  
**"AI-Based Correlation Analysis of Torque and Vibration for Misalignment Fault Detection in Rotating Machinery"**

It includes dataset information, preprocessing scripts, model training, and evaluation pipelines for fault diagnosis using machine learning and deep learning techniques.

---

## 📁 Dataset

The dataset includes:
- **180 signal samples**: 60 aligned, 60 with 0.5° misalignment, and 60 with 2.0° misalignment
- Each sample has **5000 time-series data points**
- Signal sources: **Torque** and **Vibration sensors**
- Stored in `.csv` format (provided upon request or can be uploaded)

---

## 🧠 Models Used

- **SVM** with RBF Kernel
- **Random Forest** with 100 decision trees
- **CNN** with 3-layer architecture
- **PCA** applied for feature dimensionality reduction

---

## 📊 Features

- Time-domain, frequency-domain, and statistical features
- PCA-reduced inputs for ML models
- 5-fold Cross-validation
- Accuracy, Precision, Recall, and F1 Score evaluation

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Amruta-maker/Misalignment-Fault-Detection.git
   cd Misalignment-Fault-Detection

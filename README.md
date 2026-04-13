# 🌊 OceanPlastic Detector: Deep Learning-Based Identification of Marine Plastic Waste from Ocean Images

## 📌 Abstract
Marine plastic pollution is a major environmental challenge that threatens ocean ecosystems and marine biodiversity. Manual monitoring of floating plastic waste through ocean imagery is time-consuming and difficult to scale. This project develops a deep learning-based image classification system to automatically identify the presence of plastic waste in ocean images. A baseline Convolutional Neural Network (CNN) and a transfer learning model using MobileNetV2 were implemented and compared. The transfer learning approach significantly improved generalization and achieved a test accuracy of **89.77%**, demonstrating the effectiveness of pretrained deep learning models for environmental image classification tasks.

---

## ❗ Problem Statement
Plastic waste floating in oceans causes severe harm to marine ecosystems and biodiversity. Traditional manual detection methods are inefficient for large-scale monitoring. The objective of this project is to automate marine plastic detection using deep learning techniques applied to ocean image datasets.

---

## 🎯 Objectives
- Detect plastic waste in ocean images
- Compare baseline CNN and MobileNetV2
- Improve classification performance using transfer learning
- Support environmental monitoring applications

---

## 📂 Dataset Source
- Marine Plastic Pollution Dataset (Kaggle)
- Classes:
  - `plastic`
  - `no-plastic`
- Training Images: **1720**
- Test Images: **430**

---

## ⚙️ Methodology / Workflow
1. Dataset Collection
2. Data Understanding
3. Image Preprocessing
4. Baseline CNN Model
5. Transfer Learning with MobileNetV2
6. Model Evaluation
7. Prediction Demo
8. Result Interpretation

---

## 📊 Model Comparison

CNN Accuracy: 76.05%  
MobileNetV2 Accuracy: 89.77%  

MobileNetV2 performed better due to transfer learning.

---

## 🛠 Tools & Technologies

- Python
- TensorFlow
- Keras
- Jupyter Notebook
- Deep Learning

---

## 📊 Results / Findings

| Model | Validation Accuracy | Test Accuracy |
|---|---:|---:|
| Baseline CNN | 90.12% | 76.05% |
| MobileNetV2 | **96.51%** | **89.77%** |

### ✅ Key Finding
Transfer learning with **MobileNetV2** significantly improved generalization and reduced overfitting compared to the baseline CNN.

---

## 🖼️ Demo Result
Sample prediction on unseen test image:

- Prediction: **plastic**
- Confidence: **99.99%**

---

## 📂 Folder Structure Explanation

- notebooks: contains all model development files  
- outputs: contains model and graphs  
- docs: contains PPT and documents  
- report: contains final report

---

## 👥 Team Members
- Raga Amirtha.A
- Bumeeswar.S

---

## 🌍 SDG Alignment
**Goal 14: Life Below Water**  
Reduce marine pollution through AI-powered environmental monitoring.

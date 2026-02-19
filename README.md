# 🌿 Plant Leaf Disease Detection using Deep Learning  

## 📌 Introduction
Plant diseases significantly affect agricultural productivity and crop quality.  
Early and accurate detection of plant diseases is essential to reduce crop loss, optimize treatment decisions, and support sustainable farming practices.

This project presents a **deep learning–based computer vision system** that detects and classifies plant leaf diseases from images, providing a fast and reliable diagnostic tool that can be used by farmers and agricultural stakeholders.

---

## 🧾 Project Summary
In this project, I designed and implemented an **end-to-end plant disease detection system** using **Convolutional Neural Networks (CNNs)**.  
The system takes an image of a plant leaf as input and predicts the disease class with high accuracy.

The project covers the full pipeline:
- Data understanding and preparation
- Deep learning model development
- Model evaluation
- Deployment and automation
- Real-world and business impact analysis

---

## 🎯 Problem Statement
Traditional plant disease diagnosis:
- Requires expert knowledge
- Is time-consuming
- Is not easily accessible for small-scale farmers

**Objective:**  
Build an automated, scalable, and accessible solution that enables early plant disease detection using image-based deep learning models.

---

## 📊 Dataset

Due to GitHub file size limitations, the dataset is **not included in this repository**.

- **Dataset Name:** Plant Leaf Disease Dataset  
- **Source:** Kaggle  
- **Dataset Link:**  
  👉 (https://www.kaggle.com/datasets/alinedobrovsky/plant-disease-classification-merged-dataset)
- **NoteBook Link :**
  👉 (https://www.kaggle.com/code/haneenmohammed13/plant-disease-classification))
- **And for DEMO:**
  👉 (https://www.linkedin.com/posts/haneen-mohammed13_agriculture-flask-chatbot-activity-7400983799242641408-ZyW3?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFXqN0YB9MXJE1EtZI6fzRserWu6bzT7RvY))

---

## 🌾Dataset Sample Images

Below is a sample image showcasing the crops and disease types in the dataset:
> 👉 <img src="https://github.com/Haneenmohammed1311/-Plant-Leaf-Disease-Detection-using-Deep-Learning/blob/main/Samples%20of%20the%20crops.jpg" width="400">

## Healthy images :

> 👉 <img src="https://github.com/Haneenmohammed1311/-Plant-Leaf-Disease-Detection-using-Deep-Learning/blob/main/Healthy.png" width="400">

---

## 🧠 Technical Approach

### 1️⃣ Data Preparation & Preprocessing
- Image resizing and normalization
- Dataset splitting (train / validation / test)
- Data augmentation:
  - Rotation
  - Flipping
  - Zooming
- Handling class imbalance to improve generalization

---

### 2️⃣ Model Development
- Designed **CNN architectures from scratch**
- Experimented with **pre-trained models** for performance comparison
- Tuned hyperparameters (learning rate, batch size, epochs)
- Used regularization techniques to reduce overfitting

---

### 3️⃣ Model Evaluation
- Tracked training and validation accuracy/loss
- Evaluated model generalization on unseen test data
- Analyzed misclassified samples to identify weaknesses

---

## 🚀 Deployment & Automation
- Deployed the trained model using **Flask** as a backend service
- Built a simple and user-friendly interface using **HTML & CSS**
- Integrated the model with the **Hugging Face API** for scalable inference
- Automated predictions using a **Telegram Bot**, allowing users to upload images and receive instant diagnosis

---



## 💼 Business & Impact Perspective
- Solves a **real agricultural problem**: early disease detection
- Helps farmers **reduce crop loss and treatment costs**
- Enables **data-driven farming decisions**
- Can be integrated into Agritech platforms or mobile advisory systems
- Supports **sustainable agriculture and food security goals**

---

## 🛠️ Tools & Technologies
- **Programming Language:** Python  
- **Deep Learning:** TensorFlow, Keras  
- **Computer Vision:** CNNs  
- **Deployment:** Flask  
- **Automation & APIs:** Hugging Face API, Telegram Bot  
- **Frontend:** HTML, CSS  

---
## 📂 Folder Structure

```plant_disease_classification_app/

├── _ALL_Errors.txt
├── Plant_disease_classification_app (Static, upload)
├── Plant_disease_detection_app
│   ├── static/
│   │   ├── uploads/
│   │   ├── styles.css
│   ├── templates/
│   │   ├── index.html
│   ├── uploads/
│   │   ├── .gitkeep
│   │   ├── images/
│   ├── .gitignore
│   ├── app.py
│   ├── Dockerfile
│   ├── README.md
│   ├── requirements.txt
│   ├── ResNet.keras
```
## 👩‍💻 Author
**Haneen Mohammed Mousa And Lourina Emil Fawzy**
***AS graduation Project from Samsung Innovation Campus(SIC)***
**LinkedIN :https://www.linkedin.com/in/haneen-mohammed13/**
```


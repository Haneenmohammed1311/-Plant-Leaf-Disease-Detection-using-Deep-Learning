<div align="center">

# 🌿 Plant Leaf Disease Detection
### Deep Learning & Computer Vision System for Agricultural Diagnostics

*End-to-end · CNN + Transfer Learning · Deployed · Automated*

<br/>

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)](https://tensorflow.org)
[![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)](https://keras.io)
[![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)](https://flask.palletsprojects.com)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://docker.com)
[![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21F?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co)
[![Samsung SIC](https://img.shields.io/badge/Samsung%20Innovation%20Campus-1428A0?style=flat-square&logo=samsung&logoColor=white)](https://samsung.com)

<br/>

[![Kaggle Notebook](https://img.shields.io/badge/📓%20View%20Notebook-Kaggle-20BEFF?style=for-the-badge&logo=kaggle)](https://www.kaggle.com/code/haneenmohammed13/plant-disease-classification)
[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-Hugging%20Face-FFD21F?style=for-the-badge)](https://huggingface.co/spaces/Lourina2/plant-disease-detection)
[![LinkedIn Demo](https://img.shields.io/badge/🎬%20Watch%20Demo-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/posts/haneen-mohammed13_agriculture-flask-chatbot-activity-7400983799242641408-ZyW3)

</div>

---

## 📌 Overview

Plant diseases are one of the leading causes of agricultural loss worldwide. Traditional diagnosis requires expert knowledge, is time-consuming, and is inaccessible to most small-scale farmers.

This project presents a **deep learning–based computer vision system** that automatically detects and classifies plant leaf diseases from images — providing a fast, accurate, and accessible diagnostic tool for farmers and agricultural stakeholders.

The system covers the **complete pipeline**: data preparation → model development → evaluation → deployment → automation.

> Developed as a graduation project from **Samsung Innovation Campus (SIC)** in collaboration with **Lourina Emil Fawzy**.

---

## 🎯 Problem Statement

- Traditional plant disease diagnosis **requires expert knowledge** most farmers don't have
- Manual inspection is **time-consuming** and prone to human error
- Early-stage diseases are **missed** until crop damage becomes severe
- Small-scale farmers have **no affordable, accessible diagnostic tool**

**Objective:** Build an automated, scalable, and accessible solution for early plant disease detection using image-based deep learning.

---

## 🧠 Technical Approach

### 1️⃣ Data Preparation & Preprocessing

- Image resizing and normalization
- Dataset splitting: train / validation / test
- Data augmentation: rotation, flipping, zooming
- Handling class imbalance to improve model generalization

### 2️⃣ Model Development

- Designed **CNN architectures from scratch**
- Experimented with **pre-trained models** (ResNet) for performance comparison via transfer learning
- Tuned hyperparameters: learning rate, batch size, number of epochs
- Applied regularization techniques to reduce overfitting

### 3️⃣ Model Evaluation

- Tracked training and validation **accuracy & loss curves**
- Evaluated model generalization on **unseen test data**
- Analyzed **misclassified samples** to identify and address weaknesses

---

## 🚀 Deployment & Automation

| Layer | Implementation |
|---|---|
| Backend | **Flask** web application |
| Frontend | HTML & CSS user interface for image upload & prediction |
| Scalable Inference | **Hugging Face API** integration |
| Automation | **Telegram Bot** — users send a leaf image and receive instant diagnosis |
| Containerization | **Docker** for reproducible, portable deployment |

---

## 💼 Business & Impact

- ✅ Solves a **real agricultural problem** — early disease detection at scale
- 💰 Helps farmers **reduce crop loss and treatment costs**
- 📊 Enables **data-driven farming decisions**
- 🌾 Can integrate into Agritech platforms or mobile advisory systems
- 🌍 Supports **sustainable agriculture and food security goals**

---

## 📊 Dataset

> Due to GitHub file size limits, the dataset is not included in this repository.

- **Name:** Plant Leaf Disease Classification Dataset
- **Source:** Kaggle
- **Format:** Image classification (multi-class)

[![Dataset](https://img.shields.io/badge/📦%20Download%20Dataset-Kaggle-20BEFF?style=flat-square&logo=kaggle)](https://www.kaggle.com/datasets/alinedobrovsky/plant-disease-classification-merged-dataset)

---

## 🛠️ Technologies & Tools

| Category | Tools |
|---|---|
| Language | Python |
| Deep Learning | TensorFlow, Keras |
| Model Architecture | CNN (from scratch) + ResNet (transfer learning) |
| Deployment | Flask |
| Automation | Hugging Face API, Telegram Bot |
| Frontend | HTML, CSS |
| Containerization | Docker |

---

## 📁 Project Structure

```
Plant-Leaf-Disease-Detection/
│
├── Plant_disease_detection_app/
│   ├── static/
│   │   ├── uploads/
│   │   └── styles.css
│   ├── templates/
│   │   └── index.html
│   ├── uploads/
│   ├── app.py
│   ├── Dockerfile
│   ├── requirements.txt
│   └── ResNet.keras          ← Trained model weights
│
├── Plant_disease_classification_app/
├── _ALL_Errors.txt
└── README.md
```

---

## 🔮 Future Work

- [ ] Support for more crop species and disease classes
- [ ] Mobile application for direct camera-based diagnosis in the field
- [ ] Severity estimation alongside disease classification
- [ ] Multilingual support (Arabic interface for Egyptian farmers)
- [ ] Integration with IoT sensors for environment-aware diagnosis

---

## 👩‍💻 Authors

**Haneen Mohammed Mousa** &nbsp;·&nbsp; [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/haneen-mohammed13)

**Lourina Emil Fawzy** &nbsp;·&nbsp; Graduation Project — Samsung Innovation Campus (SIC)

---

## 📜 License

This project is intended for **educational and research purposes** only.

# Fraud Detection Using Machine Learning

*A practical machine learning pipeline for identifying fraudulent financial transactions*

---

## 📌 Project Overview

This project implements a fraud detection system using machine learning techniques to identify suspicious financial transactions in highly imbalanced datasets.

The focus is on **data preprocessing, model experimentation, and evaluation**, with an emphasis on **fraud recall, precision trade-offs, and real-world constraints**.

- 📍 Built and executed entirely in **Google Colab** for easy reproducibility  
- 🤝 Forked and collaboratively developed with a project partner  

---

## 🎯 Problem Statement

Fraud detection presents unique challenges:

- ⚖️ Extreme class imbalance  
- 💸 High cost of false negatives  
- 📊 Complex, noisy transaction features  

This project explores how classical machine learning models can be trained and evaluated effectively under these conditions.

---

## 🧠 Key Features

- 📊 Exploratory Data Analysis (EDA) for transaction behavior  
- 🧹 Data preprocessing and feature scaling  
- ⚖️ Imbalance-aware modeling strategy  
- 🤖 Multiple classification models  
- 📈 Comprehensive evaluation metrics  
- 🧪 Model comparison and analysis  

All experimentation and results are contained within a **single Google Colab notebook**.

---

## 🗂 Dataset

- Transaction-level financial dataset  
- Binary classification target: **Fraud / Non-Fraud**  
- Highly imbalanced distribution reflecting real-world data  

> Dataset loading, preprocessing, and analysis are handled directly inside the notebook.

---

## 🔬 Machine Learning Pipeline

```text
Data Loading
     ↓
Exploratory Data Analysis
     ↓
Preprocessing & Scaling
     ↓
Class Imbalance Handling
     ↓
Model Training
     ↓
Evaluation & Comparison

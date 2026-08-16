# 🧠 WellnessIQ — ML-Based Mental Health Score Predictor

**WellnessIQ** is an end-to-end machine learning application that predicts a user's **Mental Health Score (0–10)** from lifestyle, study, sleep, physical activity, stress, and digital-device usage patterns.

The project demonstrates a complete ML deployment workflow — from data analysis and preprocessing to model training, evaluation, API development, and cloud deployment.

## 🚀 Live Demo

👉 **[Try WellnessIQ Live](https://wellness-iq-1.onrender.com)**

## ✨ Key Features

* 🤖 Predicts a **Mental Health Score from 0–10**
* 📊 Exploratory Data Analysis and visualization
* 🧹 Data preprocessing and feature engineering
* 🎯 Machine learning model training and evaluation
* 🔧 Hyperparameter tuning for model improvement
* 🔄 Reusable **Scikit-learn Pipeline** for preprocessing and prediction
* 🚀 **FastAPI** REST API for serving predictions
* 🧩 **Pydantic** models for request validation
* 🌐 Deployed and accessible through **Render**
* 🎨 User-friendly web interface for making predictions

## 🛠️ Tech Stack

| Category         | Technologies          |
| ---------------- | --------------------- |
| Language         | Python                |
| Data Processing  | Pandas, NumPy         |
| Visualization    | Matplotlib, Seaborn   |
| Machine Learning | Scikit-learn          |
| API              | FastAPI               |
| Validation       | Pydantic              |
| Deployment       | Render                |
| Frontend         | HTML, CSS, JavaScript |

## 🔄 ML Workflow

```text
Dataset
   ↓
Data Cleaning & Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Model Training
   ↓
Hyperparameter Tuning
   ↓
Model Evaluation
   ↓
Scikit-learn Pipeline
   ↓
FastAPI REST API
   ↓
Render Deployment
```

## 📌 Project Highlights

### Machine Learning

The model uses relevant lifestyle and behavioral features to learn patterns associated with the target **Mental Health Score**. The project includes preprocessing, model experimentation, evaluation, and hyperparameter tuning.

### Production-Ready Pipeline

A reusable ML pipeline combines preprocessing and prediction steps, helping ensure that incoming API data is transformed consistently with the data used during training.

### FastAPI Backend

FastAPI provides REST endpoints for receiving user inputs, validating them with Pydantic, and returning the model's predicted score.

### Deployment

The application  deployed on Render, making the ML model available as a live web application.

## 🎯 What This Project Demonstrates

* End-to-end machine learning development
* Data preprocessing and EDA
* Feature engineering
* Model selection and evaluation
* Hyperparameter tuning
* ML pipeline creation
* REST API development with FastAPI
* Input validation using Pydantic
* Cloud deployment





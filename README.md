#  Mental Health Prediction

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge&logo=fastapi" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn" />
  <img src="https://img.shields.io/badge/Frontend-HTML%20%7C%20CSS%20%7C%20JavaScript-yellow?style=for-the-badge&logo=javascript" />
  <img src="https://img.shields.io/badge/Deployment-Render-purple?style=for-the-badge&logo=render" />
</p>

<h2 align="center"> Student Mental Health Prediction System</h2>

<p align="center">
  An interactive Machine Learning web application that analyzes student lifestyle,
  academic and digital habits to generate a predicted mental health score.
</p>

---

##  About The Project

**Mental Health Prediction** Mental Health Prediction is an interactive Machine Learning-based web application designed to analyze the relationship between a 
student's daily lifestyle, academic environment, digital habits, and behavioral patterns and generate an estimated mental health score.
The main purpose of this project is to demonstrate how real-world student lifestyle data can be processed using Data Science and Machine Learning and integrated into a user-friendly web application.
The application provides a simple assessment form where students can enter information about their routine and digital behavior. 
This information is then sent to a FastAPI backend, processed using 
the same preprocessing pipeline used during model training, and passed to a trained Machine Learning model to generate a prediction.

The application collects information such as:
-  Age
- Gender
-  Country
-  Academic Level
-  Most-used Social Media Platform
-  Primary Purpose of Social Media
-  Daily Screen Time
-  Daily Phone Unlocks
-  Lifestyle & behavioral information

The collected information is processed by a trained Machine Learning model and used to generate a **predicted mental health score from 0–10**.

>  **Disclaimer:** This project is intended for educational and informational purposes only. The prediction is not a medical diagnosis and should not be used as a replacement for professional medical advice.

---
##  Tech Stack

| Category | Technologies |
|---|---|
|  **Language** | Python |
|  **Data Science** | Pandas, NumPy |
|  **Visualization** | Matplotlib, Seaborn |
|  **Machine Learning** | Scikit-learn |
|  **Models** | Linear Regression, Random Forest |
|  **Optimization** | RandomizedSearchCV |
|  **Backend** | FastAPI, Uvicorn |
|  **Frontend** | HTML, CSS, JavaScript |
|  **Development** | Jupyter Notebook  |
|  **Model Deployment** | `.pkl` trained model |
|  **Deployment** | Render |
|  **Version Control** | Git, GitHub |

#  Project Preview
###  Personal Assessment

The application provides a clean and interactive assessment form where users can enter their personal and digital habits.

###  Prediction Dashboard

After submitting the assessment, the application displays:

- Predicted mental health score
- Visual score indicator
- Signal classification
- AI-generated insight
- Option to run another prediction

---

#  Main Features

| Feature | Description |
|---|---|
|  User Profile | Collects basic user information |
|  Academic Data | Captures academic level |
|  Digital Habits | Analyzes screen time and phone usage |
|  Social Media | Tracks platform usage and purpose |
|  ML Prediction | Generates a mental health score |
|  Visual Dashboard | Displays prediction using an interactive UI |
|  FastAPI API | Provides backend prediction services |
|  Responsive UI | Modern frontend interface |
|  Deployment | Backend can be deployed using Render |

---
##  Live Demo

 **Live Application:** [Mental Health Prediction](https://mental-health-prediction-1-d68v.onrender.com/)

#  Machine Learning Workflow

```text
                 USER INPUT
                     │
                     ▼
        ┌─────────────────────────┐
        │   Personal Information  │
        └────────────┬────────────┘
                     │
                     ▼
        ┌─────────────────────────┐
        │ Academic & Digital Data │
        └────────────┬────────────┘
                     │
                     ▼
        ┌─────────────────────────┐
        │     Data Processing     │
        └────────────┬────────────┘
                     │
                     ▼
        ┌─────────────────────────┐
        │ Machine Learning Model  │
        └────────────┬────────────┘
                     │
                     ▼
                 PREDICTION
                     │
                     ▼
        ┌─────────────────────────┐
        │   Mental Health Score   │
        │          0 – 10         │
        └─────────────────────────┘

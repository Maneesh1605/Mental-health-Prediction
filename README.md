# Mental Health Prediction

A Machine Learning based web application designed to predict mental health risks in workplace environments using survey and behavioral data. The project focuses on early detection, proactive intervention, and improving employee well-being through intelligent analytics and predictive modeling.

---

# Project Overview

The Mental Health Prediction system leverages Machine Learning algorithms to analyze employee survey responses and workplace-related data to predict potential mental health risks. The application provides real-time predictions through a Flask-based web interface and helps promote awareness, support, and early intervention strategies.

---

# Problem Statement

Mental health challenges in workplaces often remain unnoticed due to lack of timely identification and support systems. This negatively impacts:

- Employee well-being
- Productivity
- Organizational culture
- Workplace efficiency

This project addresses these issues using Machine Learning techniques for early detection and predictive analysis.

---

# Objectives

- Predict mental health risks using Machine Learning
- Provide a self-assessment platform
- Deliver actionable insights for employees and HR
- Reduce stigma around mental health discussions
- Improve workplace support systems
- Enable continuous learning and model enhancement

---

# Key Features

- Machine Learning based mental health prediction
- Flask-powered web application
- User-friendly self-assessment interface
- Real-time prediction system
- Data preprocessing and feature engineering
- Multiple trained ML models
- Visualization and data analysis support
- Continuous learning capability

---

# Tech Stack

## Programming Language
- Python

## Framework
- Flask

## Libraries Used
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn

## Development Tools
- Google Colab
- VS Code
- Git


---

# Machine Learning Workflow

## 1. Data Collection
- Mental health survey dataset collected from Kaggle

## 2. Data Preprocessing
- Handling missing values
- Label encoding
- Feature scaling
- Data cleaning

## 3. Exploratory Data Analysis
- Statistical analysis
- Data visualization
- Pattern identification

## 4. Model Training
- Gradient Boosting Model
- Classification algorithms
- Performance evaluation

## 5. Model Serialization
- Trained models stored using `.pkl` files

## 6. Web Application Deployment
- Flask application for real-time predictions

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/Maneesh1605/Mental-health-Prediction.git
```

## Navigate to Project Directory

```bash
cd Mental-health-Prediction
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Run the Application

```bash
python app.py
```

The Flask server will start locally.

---

# Model Files

| File Name | Description |
|---|---|
| mental_health_model.pkl | Main trained prediction model |
| gradient_boosting_model.pkl | Gradient Boosting ML model |
| scaler.pkl | Feature scaling object |
| label_encoders.pkl | Encoded categorical variables |
| le_target.pkl | Target label encoder |

---

# Dataset Information

- Source: Kaggle
- Format: CSV
- Records: 1000+ entries
- File Used: `survey.csv`

The dataset contains employee survey responses and workplace-related behavioral attributes used for mental health prediction.

---

# Resource Requirements

## Hardware Requirements

| Resource | Specification |
|---|---|
| CPU/GPU | 4 Core CPU / T4 GPU |
| RAM | 8GB |
| Storage | 1TB SSD |

## Software Requirements

| Software | Usage |
|---|---|
| Flask | Web Framework |
| scikit-learn | Machine Learning |
| pandas | Data Handling |
| numpy | Numerical Computing |
| matplotlib | Visualization |
| seaborn | Data Visualization |

---

# Future Enhancements

- Deep Learning integration
- Real-time cloud deployment
- Authentication system
- Dashboard analytics
- AI chatbot assistance
- Mobile application support
- Explainable AI integration

---

# Expected Impact

This project aims to:

- Improve employee well-being
- Enable proactive mental health intervention
- Reduce workplace mental health stigma
- Increase organizational productivity
- Support healthier workplace environments

---

# License

This project is developed for educational and research purposes.

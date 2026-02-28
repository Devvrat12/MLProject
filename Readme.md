# 🎯 Student Performance Prediction - End-to-End ML Project

## 📖 Overview

This project is an end-to-end Machine Learning pipeline that predicts student math scores based on demographic and academic features.

The project follows a modular ML architecture including:

- Data Ingestion
- Data Transformation
- Model Training
- Model Evaluation
- Experiment Tracking using MLflow
- Remote Tracking with DagsHub

## 🏗️ Project Structure

MLProject/
│
├── src/
│ └── mlproject/
│ ├── components/
│ │ ├── data_ingestion.py
│ │ ├── data_transformation.py
│ │ └── model_trainer.py
│ ├── pipeline/
│ ├── utils.py
│ └── exception.py
│
├── notebook/
├── artifacts/
├── app.py
├── requirements.txt
├── environment.yml
└── README.md

## 📊 Dataset

The dataset contains student academic performance records with features such as:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Math Score (Target)
- Reading Score
- Writing Score

## ⚙️ Technologies Used

- Python 3.11
- Pandas
- NumPy
- Scikit-learn
- CatBoost
- XGBoost
- MLflow
- DagsHub
- Git & GitHub

## 🔬 Machine Learning Workflow

1. Data Cleaning & Preprocessing
2. Feature Engineering
3. Model Training (Multiple Models)
4. Hyperparameter Tuning
5. Best Model Selection
6. MLflow Experiment Tracking
7. Model Logging

## 👨‍💻 Author

Devvrat Tiwari  
Machine Learning Enthusiast

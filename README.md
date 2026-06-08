# 🎓 Student Exam Score Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📌 Overview

This project aims to predict student exam scores based on their study habits, attendance, sleep quality, mental health, and lifestyle factors using Machine Learning techniques.

The project compares multiple regression algorithms to determine the most effective model for predicting academic performance.

---

## 🎯 Objectives

* Analyze factors affecting student exam performance.
* Build predictive machine learning models.
* Compare model performance using multiple evaluation metrics.
* Identify the best-performing algorithm.

---

## 📂 Dataset

Dataset: **Student Habits Performance Dataset**

Features include:

* 📚 Study Hours Per Day
* 📱 Social Media Usage
* 🎬 Netflix Hours
* 🏫 Attendance Percentage
* 😴 Sleep Hours
* 💪 Exercise Frequency
* 🧠 Mental Health Rating
* 🌐 Internet Quality
* 👨‍👩‍👧 Parental Education Level
* 🎓 Exam Score (Target Variable)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib

---

## 🔄 Machine Learning Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Encoding Categorical Features
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Prediction
```

---

## 🤖 Models Compared

### 1️⃣ Linear Regression

A statistical model that assumes a linear relationship between input features and the target variable.

### 2️⃣ Decision Tree Regressor

A tree-based model that predicts values by learning decision rules from data features.

### 3️⃣ Random Forest Regressor

An ensemble learning method that combines multiple decision trees to improve prediction accuracy.

---

## 📊 Model Performance

| Model                | MAE  | RMSE | R² Score |
| -------------------- | ---- | ---- | -------- |
| 🥇 Linear Regression | 4.19 | 5.15 | 0.8965   |
| 🥈 Random Forest     | 4.99 | 6.24 | 0.8484   |
| 🥉 Decision Tree     | 7.09 | 9.09 | 0.6781   |

---

## 🏆 Best Model

### Linear Regression

Performance:

* ✅ MAE: 4.19
* ✅ RMSE: 5.15
* ✅ R² Score: 0.8965

The model successfully explains approximately **89.65% of the variance** in student exam scores.

---

## 📈 Evaluation Metrics

### MAE (Mean Absolute Error)

Measures the average prediction error.

### RMSE (Root Mean Squared Error)

Measures the standard deviation of prediction errors.

### R² Score

Represents the proportion of variance explained by the model.

---

## 🔍 Key Findings

* Study habits significantly influence exam performance.
* Attendance percentage is one of the strongest predictors.
* Mental health and sleep quality also contribute to academic outcomes.
* Linear Regression outperformed more complex models on this dataset.

---

## 🚀 Future Improvements

* Implement XGBoost Regressor
* Hyperparameter Tuning
* Cross Validation
* Feature Selection
* Model Deployment using Streamlit

---

## 👨‍💻 Author

**Briliant Vilendro**

Teknik Informatika

Universitas Mercu Buana


# Heart-Risk-Analysis-Predictor
Cardiovascular disease (CVD) is the leading cause of death worldwide. Early detection is key to prevention. This project uses data to build a predictive model that identifies high-risk individuals before it is too late.

# 🫀 Cardiovascular Risk Analysis

This project explores and predicts the presence of **cardiovascular disease** using tabular medical data. It includes **exploratory data analysis (EDA)** and **machine learning modeling** to identify risk patterns and build predictive tools.

The primary goal is to understand how features such as blood pressure, cholesterol, glucose, hypertension, and lifestyle habits correlate with cardiovascular risk.

---

## 📁 Project Structure

- `EDA/`: plots for exploratory analysis
- `models/`: machine learning training and evaluation (XGBoost, Random Forest, etc.)
- `data/`: dataset files or links to data sources
- `notebooks/`: step-by-step pipeline of the project
- `requirements.txt`: project dependencies
- `Informe`: Pdf Report
- `Presentation`: Power Bi presentation

---

## 📊 Dataset Overview

The dataset includes over 60,000 patient records with the following features:

- Age
- Gender
- Systolic and diastolic blood pressure
- Cholesterol levels
- Glucose levels
- Lifestyle indicators (smoking, alcohol intake, physical activity)
- Hypertension diagnosis
- Cardiovascular disease diagnosis (`target`)

> ⚠️ The `target` variable is binary:  
> `0 = No cardiovascular disease` | `1 = Cardiovascular disease`

---

## 🧠 Methodology

- Data cleaning and feature engineering
- Derived variables (Pulse Pressure, Mean Arterial Pressure, etc.)
- Visual analysis of correlations with cardiovascular risk
- Class balancing (if applicable)
- Model training:
  - XGBoost 
  - Random Forest
  - Logistic Regression
- Evaluation metrics: AUC, precision, recall, F1-score

---

## 📈 Results

The best-performing model was **XGBoost**, with:

- AUC ROC: `0.80`
- Accuracy: `74%`
- Precision: `76%`
- Recall: `70%`
- F1-score: `73%`
- Top features: systolic pressure, PAM (Pressure arterial mean) cholesterol and age

Hypertension and elevated pulse pressure showed strong association with cardiovascular risk.

---

## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/Sebamir/Heart-Risk-Analysis
cd Heart-Risk-Analysis

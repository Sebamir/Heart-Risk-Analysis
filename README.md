# Heart-Risk-Analysis/POWER BI/ ML_predictor 
Cardiovascular disease (CVD) is the leading cause of death worldwide. Early detection is key to prevention. This project uses data to find insights and build a predictive model that identifies high-risk individuals before it is too late.

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
- Presentation created with POWER BI
- Write the final report 

---

## 📈 Results
# ML-Predictor
The best-performing model was **XGBoost**, with:

- AUC ROC: `0.80`
- Accuracy: `74%`
- Precision: `76%`
- Recall: `70%`
- F1-score: `73%`

# DATA ANALYSIS 
- From the age of 40, the first positive cases of cardiovascular risk begin to appear, with an increase of **259.88%** in the first decade (40–50 years) and **51.99%** in the second decade (50–60 years).
- **84.88%** of positive hypertension cases (10,379) also have a positive cardiovascular risk.
- Systolic pressures above **125** already represent a problem: at **130**, **59.64%** of cases are positive for cardiovascular risk, and at **140**, the percentage rises to **76.28%**.
- **Obesity** shows the highest cardiovascular risk index among BMI categories, with **62.88%**.
- **Cholesterol level 3** is associated with a **76.23%** rate of positive cardiovascular risk.


---

## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/Sebamir/Heart-Risk-Analysis
cd Heart-Risk-Analysis

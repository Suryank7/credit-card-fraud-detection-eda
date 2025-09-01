# Credit Card Fraud Detection — EDA & Baseline Model

## 🔹 Overview
This project explores the **Kaggle Credit Card Fraud Dataset** to detect fraudulent transactions using Exploratory Data Analysis (EDA) and baseline machine learning models.

---

## Result
- **284,807 transactions**
- **492 frauds (0.17%) → Highly imbalanced**
- Features: `V1`–`V28` (PCA anonymized), `Amount`, `Time`, and `Class` (1 = Fraud, 0 = Legit)

---

## Goals
- Perform **EDA** to study transaction behavior
- Handle **class imbalance**
- Train baseline models: Logistic Regression & Random Forest
- Evaluate using **ROC-AUC** and **PR-AUC**
- Tune thresholds to improve recall on frauds
- Package a simple **inference pipeline**

---

## Tech Stack
- Python, Pandas, NumPy, Matplotlib  
- Scikit-learn (ML models, metrics)  
- Joblib (model persistence)  
- Flask (optional API)

---

## Project Structure
fraud-eda/ ├── data/creditcard.csv ├── notebooks/01_eda_and_baseline.ipynb ├── src/ │   ├── data_utils.py │   ├── train.py │   ├── inference.py │   └── api.py ├── models/baseline_pipeline.joblib └── README.md

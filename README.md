# Real-Time-Fraud-Detection-System-with-Explainable-AI-Live-Dashboard
🛡️ Fraud Operations Dashboard A multi-page Streamlit application for fraud detection analytics, risk scoring, and ML explainability.

## 📌 Project Overview

This project is an end-to-end **Fraud Detection System** developed using **Machine Learning**, **Explainable AI (SHAP)**, and **Streamlit Dashboarding**. The system detects fraudulent financial transactions, explains predictions using SHAP values, and provides an interactive dashboard for fraud monitoring and analysis.

The project uses the **IEEE-CIS Fraud Detection Dataset** from Kaggle and focuses on solving real-world fraud detection challenges such as:
- Severe class imbalance
- High-dimensional data
- Missing values
- Fraud risk segmentation
- Model interpretability

---

# 🎯 Problem Statement

Financial fraud causes massive losses every year across banking and fintech industries. Traditional rule-based systems often fail to detect modern fraud patterns, while black-box machine learning models lack transparency.

The objective of this project is to:
- Detect fraudulent transactions accurately
- Handle class imbalance using SMOTE
- Explain predictions using SHAP Explainable AI
- Build an interactive Streamlit dashboard
- Provide actionable fraud insights

---

# 📂 Dataset Information

### Dataset Used
IEEE-CIS Fraud Detection Dataset

### Source
https://www.kaggle.com/c/ieee-fraud-detection/data

### Files Used
- `train_transaction.csv`
- `train_identity.csv`

### Merge Key
- `TransactionID`

### Dataset Characteristics
- ~590,000 transactions
- 433+ features
- ~3.5% fraud rate
- Severe class imbalance

---

# ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| 🐍 Python | Main Programming Language |
| 📊 Pandas / NumPy | Data Processing |
| 🤖 Scikit-learn | ML Utilities |
| 🚀 LightGBM | Primary Fraud Classifier |
| 🌳 XGBoost | Comparison Model |
| 🕵️ Isolation Forest | Anomaly Detection |
| 🧠 SHAP | Explainable AI |
| ⚖️ SMOTE | Imbalance Handling |
| 📈 Plotly | Interactive Charts |
| 🌐 Streamlit | Dashboard Development |
| 📉 Matplotlib / Seaborn | Visualizations |

---

# 🔄 Project Workflow

1. Data Loading & Merging  
2. Exploratory Data Analysis (EDA)  
3. Missing Value Handling  
4. Feature Engineering  
5. Data Preprocessing  
6. SMOTE Imbalance Handling  
7. Model Training  
8. Model Evaluation  
9. Threshold Optimization  
10. Explainable AI using SHAP  
11. Risk Segmentation  
12. Streamlit Dashboard Deployment  

---

# 🤖 Machine Learning Models Used

## 🚀 LightGBM Classifier
- Fast and efficient gradient boosting algorithm
- Best performing model in this project
- Handles imbalanced data effectively

## 🌳 XGBoost Classifier
- Advanced boosting algorithm
- Strong predictive performance
- Reduces overfitting

## 🕵️ Isolation Forest
- Anomaly detection algorithm
- Detects unusual transaction behavior
- Effective for fraud outlier detection

---

# 📊 Evaluation Metrics

The models were evaluated using:
- ✅ Accuracy
- ✅ Precision
- ✅ Recall
- ✅ F1-Score
- ✅ ROC-AUC
- ✅ PR-AUC

---

# 🧠 Explainable AI using SHAP

SHAP (SHapley Additive exPlanations) was used to improve model transparency and interpretability.

### SHAP Features
- Global Feature Importance
- Waterfall Plot Explanations
- Dependence Plots
- Transaction-Level Explanations

### Benefits
- Explains fraud predictions clearly
- Helps analysts understand model decisions
- Increases trust in ML predictions

---

# ⚠️ Risk Segmentation

Transactions were segmented into:

| Risk Tier | Fraud Probability |
|---|---|
| 🔴 Critical Risk | ≥ 0.75 |
| 🟡 Suspicious | 0.40 – 0.74 |
| 🟢 Clear | < 0.40 |

---

# 🌐 Streamlit Dashboard

## Dashboard Features

### 📊 Overview Page
Displays:
- Total transactions
- Fraud count
- Detection rate
- Average fraud amount

### 🔍 Transaction Explorer
Features:
- Searchable transaction table
- Fraud filtering
- Live fraud probability score

### 🧠 SHAP Explainer
Features:
- SHAP waterfall plot
- Plain-English fraud explanation
- Transaction-level interpretability

---

# 📁 Project Folder Structure


FraudDetection_Project/
│
├── 📓 analysis.ipynb
│
├── 📂 data/
│   ├── train_transaction.csv
│   └── train_identity.csv
│
├── 📂 dashboard/
│   ├── app.py
│   ├── model.pkl
│   ├── scaler.pkl
│   └── pages/
│
├── 📂 charts/
│
├── 📊 shap_summary.png
├── 📈 model_comparison.png
│
├── ⚙️ requirements.txt
├── 📘 README.md
└── 📄 summary.pdf






# 🌐 Live Dashboard Deployment

The Fraud Detection Dashboard was deployed using **Streamlit Community Cloud** for real-time fraud monitoring and interactive analysis.

## 🚀 Dashboard Features
- 📊 Fraud Overview Analytics
- 🔍 Transaction Explorer
- 🧠 SHAP Explainable AI
- 📈 Interactive Plotly Charts
- ⚠️ Real-Time Fraud Risk Scores
- 🎯 Risk Tier Segmentation

---

# 🔗 Live Dashboard URL

👉
https://real-time-fraud-detection-system-with-explainabl--tamilarsan538.replit.app/SHAP_Explainer

---

# 🛠️ Deployment Platform

The dashboard was deployed using:

- 🌐 Streamlit Community Cloud
- 💻 GitHub Repository Integration

---

# 📦 Deployment Steps

1. Push project files to GitHub
2. Open Streamlit Community Cloud
3. Connect GitHub repository
4. Select `dashboard/app.py`
5. Deploy application
6. Copy deployment URL
7. Add live URL to README.md

---

# 📌 Dashboard Pages

## 📊 Overview
Displays:
- Total transactions
- Fraud count
- Detection rate
- Average fraud amount

---

## 🔍 Transaction Explorer
Features:
- Searchable transaction table
- Fraud filtering
- Live fraud probability scoring

---

## 🧠 SHAP Explainer
Features:
- SHAP waterfall visualization
- Plain-English fraud explanation
- Transaction-level interpretability

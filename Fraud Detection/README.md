
# 🕵️‍♂️ Fraud Detection Model – Internship Project

This repository showcases a machine learning project completed during my internship with INSAID. The objective was to identify fraudulent financial transactions using classification models and evaluate their effectiveness.

## 📁 Project Overview

The dataset contains financial transactions where only a small fraction are labeled as fraudulent. The task involved cleaning the data, feature engineering, building models, and evaluating their performance to detect fraud accurately.

## ⚙️ Tasks Completed

### 1. **Data Cleaning & Feature Engineering**
- The dataset was mostly clean, with appropriate data types.
- 99% of transactions were legitimate; only 1% were fraud.
- Missing merchant transaction amounts were handled via **feature engineering**, rather than removing the data.
- Multicollinearity and outliers were assessed to ensure robust modeling.

### 2. **Model Building & Evaluation**
- Implemented multiple models using `DecisionTreeClassifier`.
- **Key Metrics Used:**
  - Accuracy
  - Precision
  - Recall (critical for fraud detection)
  - F1 Score

### 3. **Model Performance**
- **Model 2**: 
  - Recall: 99% (flagged nearly all frauds)
  - Precision: 15% (many false positives)
  - Suitable when it's better to over-flag than miss actual fraud.

- **Model 3 (Best Model)**:
  - Recall: 87%
  - Precision: 74%
  - Balanced and more practical for real-world use.

### 4. **Key Fraud Indicators**
- Type of transaction (`CashOut`) and high account balances were most predictive of fraud.
- Fraudsters tend to target high-value accounts.

### 5. **Preventive Recommendations**
- Implement **transaction monitoring** based on customer behavior.
- Alert when large transactions deviate from typical patterns.
- Ensure confirmation from recipients on successful receipt of funds.

### 6. **Effectiveness Evaluation**
- After infrastructure updates, effectiveness can be evaluated by:
  - Running the updated model on fresh data.
  - Measuring changes in fraud detection performance metrics.

## 🛠️ Tools & Technologies Used
- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- NumPy

---

## 📌 Author

**Rohan Prabhakar**  
Data Science Intern at INSAID

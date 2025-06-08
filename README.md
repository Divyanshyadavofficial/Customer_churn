# 📉 Customer Churn Prediction using Logistic Regression

This project predicts whether a customer will churn (leave) or not using logistic regression. It uses the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) and includes data preprocessing, model training, evaluation, and visualization.

---

## 📁 Project Structure

customer-churn-logistic-regression/
│
├── data/
│ └── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── churn_logistic_regression.ipynb


---

## 📊 Dataset Summary

- **Source:** Kaggle Telco Churn Dataset  
- **Target Variable:** `Churn` (Yes/No)  
- **Features:** Demographics, Account Info, Services Used  
- **Size:** ~7,000 rows and 20+ features  

---

## 🧠 Problem Statement

**Goal**: Predict whether a customer will churn based on their usage patterns and service details.

---

## 🛠️ Technologies Used

- Python
- Pandas & NumPy
- scikit-learn
- Seaborn & Matplotlib
- Jupyter Notebook

---

## 🔁 Pipeline Steps

1. **Data Loading**
2. **Data Cleaning**
   - Handle missing/empty values
   - Remove whitespace and convert types
3. **Encoding**
   - One-hot encode categorical columns

4. **Train-Test Split**
5. **Logistic Regression**
   - Fit model on training data
   - Predict on test data
6. **Evaluation**
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)
   - Accuracy Score
7. **Model Saving**

---

## ✅ Results

- **Accuracy:** 80–85% (varies slightly depending on preprocessing)
- **Evaluation Metrics:**
  - Confusion Matrix
  - Precision, Recall, F1-Score
  - ROC Curve (optional)

---


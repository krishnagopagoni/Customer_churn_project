# Customer Churn Prediction using Machine Learning

## 📌 Project Overview
Customer churn is a major challenge in the telecom industry. When customers switch to competitors, companies lose revenue and market share. Predicting customer churn allows businesses to take proactive steps to retain customers.

This project applies machine learning techniques to analyze telecom customer data and predict whether a customer is likely to churn.

The goal is to help telecom companies identify high-risk customers and implement retention strategies.

---

## 🎯 Project Objectives

- Identify factors influencing customer churn
- Build machine learning models to predict churn
- Compare multiple models to find the best performer
- Provide business insights to reduce churn

---

## 📊 Dataset Information

The dataset contains telecom customer information including:

- Customer demographics
- Service usage patterns
- Salary information
- Number of calls and SMS sent
- Data usage
- Customer churn status

### Target Variable
`churn`

- **0 → Customer stays**
- **1 → Customer leaves**

Dataset size: **243,553 customers**

---

## ⚙️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **XGBoost**
- **LightGBM**
- **SQL**

---

## 🧠 Machine Learning Models Used

The following models were trained and evaluated:

1. Logistic Regression
2. Random Forest
3. XGBoost
4. LightGBM

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 📈 Model Performance

| Model | Accuracy | Churn Recall |
|------|------|------|
| Logistic Regression | 0.51 | 0.50 |
| Random Forest | 0.79 | 0.02 |
| XGBoost | 0.54 | 0.44 |
| LightGBM | 0.51 | 0.48 |

**Best Model:** LightGBM (better churn detection)

---

## 🔍 Key Insights

Feature importance analysis identified several important factors influencing churn:

- Customer tenure
- Data usage
- Number of calls made
- Estimated salary
- Telecom provider

These insights can help telecom companies understand customer behavior and develop targeted retention strategies.

---

## 📊 Project Workflow

1. Data Extraction from SQL Database
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Categorical Encoding
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Feature Importance Analysis
10. Business Insights

---

## 💼 Business Impact

This churn prediction model helps telecom companies:

- Identify customers likely to churn
- Take proactive retention actions
- Improve customer engagement
- Reduce revenue loss
- Enhance customer satisfaction

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Advanced imbalance handling (SMOTE)
- Deployment using API
- Real-time churn prediction dashboard
- Customer segmentation analysis

---

## 👨‍💻 Author

**Krishna Teja Gopagoni**

AI & Machine Learning Enthusiast  
B.Tech in Artificial Intelligence & Machine Learning  

GitHub:  
https://github.com/krishnagopagoni

LinkedIn:  
http://www.linkedin.com/in/krishna-teja-gopagoni

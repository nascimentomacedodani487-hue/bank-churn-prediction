# 📊 Bank Customer Churn Prediction

## 🚀 Project Overview

This project aims to predict customer churn in a banking context using Machine Learning techniques. The main objective is to identify customers with a high probability of leaving the bank, enabling data-driven retention strategies.

The dataset used in this project was obtained from Kaggle:
🔗 https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn?resource=download

---

## 🎯 Business Problem

Customer churn is one of the most critical challenges in the financial sector. Losing customers directly impacts revenue and long-term growth.

The goal of this project is to:
- Analyze customer behavior patterns
- Identify key factors influencing churn
- Build predictive models to classify customers at risk of leaving

---

## 📂 Dataset

The dataset used in this project contains detailed information about bank customers, including demographic, financial, and behavioral attributes.

📥 The file used in this project is available in this repository:

👉 **Customer-Churn-Records.csv**

You can download it directly from the repository and use it to reproduce the analysis in the notebook (cell [5]).

---

## 🧠 Methodology

The project follows a complete data science pipeline:

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Feature Engineering
- Detection and removal of data leakage
- Model training and evaluation

---

## 🤖 Machine Learning Models

Two models were implemented and compared:

- Logistic Regression
- Random Forest Classifier

---

## 📈 Results

- Logistic Regression: baseline performance
- Random Forest: better performance in identifying churn customers

The Random Forest model showed superior capability in capturing customers at risk of leaving, making it more suitable for retention strategies.

---

## 💡 Key Insights

- Customers with complaints had strong correlation with churn (data leakage removed)
- Active customers are less likely to leave the bank
- Age and number of products significantly influence churn behavior

---

## 🛠️ Tech Stack

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn

---

## 🚀 Conclusion

This project demonstrates an end-to-end machine learning workflow applied to a real-world business problem. It highlights the importance of data quality, feature selection, and model evaluation in building reliable predictive systems for business decision-making.

# 📊 Bank Customer Churn Prediction

## 🚀 Project Overview
This project aims to predict customer churn in a banking context using Machine Learning techniques. The main objective is to identify customers with a high probability of leaving the bank, enabling data-driven retention strategies.

**Dataset Source:** 🔗 [Bank Customer Churn Dataset (Kaggle)](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn?resource=download)

---

## 🖥️ Interactive Business Dashboard
To complement the machine learning analysis, an interactive web dashboard was developed to provide real-time business insights. This allows stakeholders to explore data patterns beyond the static model.

👉 **[Access the Dashboard here: Bank Churn Analytics - Lovable](https://lovable.dev/projects/0671d6bb-dc25-46ca-b45d-be4f063e4ade?magic_link=mc_3120b031-c20f-47ad-b147-995656e054c9)**

> [!TIP]
> **How to use:** To explore the dashboard, simply upload the `Customer-Churn-Records.csv` file available in this repository. This ensures full consistency between the predictive model and the visual analytics.

---

## 🎯 Business Problem
Customer churn is one of the most critical challenges in the financial sector. Losing customers directly impacts revenue and long-term growth.

**Our main goals:**
* **Analyze** customer behavior patterns.
* **Identify** key factors influencing churn.
* **Build** predictive models to classify customers at risk.

---

## 📂 Dataset
The dataset contains detailed information about bank customers, including demographic, financial, and behavioral attributes.

📥 **File available in this repo:** [`Customer-Churn-Records.csv`](./Customer-Churn-Records.csv)  
*Note: Use this file to reproduce the analysis in the notebook (cell [5]) or to power the Interactive Dashboard.*

---

## 🧠 Methodology
The project follows a complete data science pipeline:
1.  **Exploratory Data Analysis (EDA)**
2.  **Data Cleaning and Preprocessing**
3.  **Feature Engineering**
4.  **Leakage Detection:** Identification and removal of data leakage.
5.  **Model Training & Evaluation**

---

## 🤖 Machine Learning Models
Two models were implemented and compared to find the best fit for this business case:
* **Logistic Regression:** Used as the baseline performance.
* **Random Forest Classifier:** Best performance in identifying at-risk customers.

---

## 📈 Results
* **Random Forest** showed superior capability in capturing customers likely to leave, making it the most suitable model for retention strategies.
* The model prioritizes **Recall**, ensuring that the bank doesn't miss potential churn cases.

---

## 💡 Key Insights
* **Complaints:** Customers with past complaints showed a high correlation with churn.
* **Activity:** Active members are significantly less likely to leave the bank.
* **Demographics:** Age and the number of products used are the strongest behavioral influencers.

---

## 🛠️ Tech Stack
* **Data Science:** Python (Pandas, NumPy, Scikit-learn)
* **Visualization:** Matplotlib, Seaborn
* **Deployment:** Lovable (React/Tailwind)

---

## 🚀 Conclusion
This project demonstrates an end-to-end machine learning workflow applied to a real-world business problem. It highlights the importance of data quality, feature selection, and model evaluation in building reliable systems for high-stakes business decision-making.

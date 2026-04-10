📊 Bank Customer Churn Prediction
🚀 Project Overview
This project aims to predict customer churn in a banking context using Machine Learning techniques. The main objective is to identify customers with a high probability of leaving the bank, enabling data-driven retention strategies.

The dataset used in this project was obtained from Kaggle:
🔗 Bank Customer Churn Dataset

🖥️ Interactive Business Dashboard
To complement the machine learning analysis, an interactive web dashboard was developed to provide real-time business insights.

👉 Access the Dashboard here: Bank Churn Analytics - Lovable

💡 Note for Reviewers: To explore the dashboard, simply upload the Customer-Churn-Records.csv file available in this repository. This is the exact same dataset used in the Google Colab notebook (Cell [5]), ensuring full consistency between the predictive model and the visual analysis.

🎯 Business Problem
Customer churn is one of the most critical challenges in the financial sector. Losing customers directly impacts revenue and long-term growth.

The goal of this project is to:

Analyze customer behavior patterns

Identify key factors influencing churn

Build predictive models to classify customers at risk of leaving

📂 Dataset
The dataset used in this project contains detailed information about bank customers, including demographic, financial, and behavioral attributes.

📥 The file used in this project is available in this repository:

👉 Customer-Churn-Records.csv

You can download it directly from the repository and use it to reproduce the analysis in the notebook (cell [5]) or to power the Interactive Dashboard.

🧠 Methodology
The project follows a complete data science pipeline:

Exploratory Data Analysis (EDA)

Data Cleaning and Preprocessing

Feature Engineering

Detection and removal of data leakage

Model training and evaluation

🤖 Machine Learning Models
Two models were implemented and compared:

Logistic Regression

Random Forest Classifier

📈 Results
Logistic Regression: baseline performance

Random Forest: better performance in identifying churn customers

The Random Forest model showed superior capability in capturing customers at risk of leaving, making it more suitable for retention strategies.

💡 Key Insights
Customers with complaints had strong correlation with churn (data leakage removed)

Active customers are less likely to leave the bank

Age and number of products significantly influence churn behavior

🛠️ Tech Stack
Data Science: Python, Pandas, NumPy, Scikit-learn

Visualization: Matplotlib, Seaborn

Deployment & Dashboard: Lovable (React/Tailwind)

🚀 Conclusion
This project demonstrates an end-to-end machine learning workflow applied to a real-world business problem. It highlights the importance of data quality, feature selection, and model evaluation in building reliable predictive systems for business decision-making.

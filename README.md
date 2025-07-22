# Task-2-Telecom-Customer-Churn-predictions
Submit Ai task 2


# 📊 Telecom Customer Churn Prediction

📁 Project Description

This project aims to predict customer churn in a telecom company using supervised machine learning models. Churn means when a customer stops doing business with the company. The goal is to identify high-risk customers and understand why they might churn, then suggest actions to reduce churn and retain more customers.

💡 Problem Statement

Telecom companies lose revenue when customers churn.
The objective of this project is to:

Predict which customers are likely to churn.

Understand the reasons behind customer churn using SHAP.

Provide actionable business strategies to reduce churn.





# 📊 Dataset Description

Dataset Name: Telco Customer Churn

Source: Kaggle – Telco Churn Dataset

Records: 7,043 customer data points

Target Variable: Churn (Yes/No)


Column Type	Example

Demographics	Gender, SeniorCitizen
Services	InternetService, TechSupport
Payments	MonthlyCharges, PaymentMethod
Target	Churn




🔍 Exploratory Data Analysis (EDA)

📉 1. Churn by Contract Type

Insight: Customers with Month-to-month contracts churn the most.

🔁 Recommendation: Offer long-term contracts with loyalty discounts.

<img width="567" height="553" alt="churn by contract type" src="https://github.com/user-attachments/assets/95e64587-dd29-4713-b645-56eee6246e6a" />


💰 2. Monthly Charges by Churn

Insight: Customers paying higher monthly charges are more likely to churn.

🔁 Recommendation: Provide bundled or discounted plans.

<img width="571" height="455" alt="montly charges by Churn" src="https://github.com/user-attachments/assets/e8f43ca1-9d40-4228-9806-3ccad6c3f8d6" />






📆 3. Tenure Distribution

Insight: New customers (<12 months) have higher churn rates.

🔁 Recommendation: Focus on onboarding and support campaigns early.



<img width="580" height="455" alt="tenure distribution" src="https://github.com/user-attachments/assets/862e7b22-387e-4162-b8ca-d5f5ee7f55b9" />




🧹 Data Preprocessing

Removed customerID column (not useful for modeling)

Converted TotalCharges to numeric

Handled missing values

Applied One-Hot Encoding to categorical features

Used SMOTE to fix class imbalance in Churn column

🤖 Machine Learning Models Used

Model	Accuracy

Logistic Regression	✅
Random Forest Classifier	✅
XGBoost Classifier	✅


Evaluation Metric: Classification Report (Precision, Recall, F1-score)

🧠 Model Interpretability

Used SHAP (SHapley Additive Explanations) to explain how features impact churn.

<img width="803" height="940" alt="download" src="https://github.com/user-attachments/assets/581d5b44-f3c4-4e30-ae59-e37558fbad55" />


🔍 Top Features Impacting Churn:

MonthlyCharges

Tenure

Contract Type

OnlineSecurity, TechSupport

<img width="1497" height="166" alt="download 2" src="https://github.com/user-attachments/assets/8e9c48f7-d4bc-4732-b0ca-19f4821b66c1" />







💼 Business Insights

Graph	Insight	Recommendation

Churn by Contract Type	Month-to-month users churn more	Promote yearly/2-year plans
Monthly Charges	Higher cost → more churn	Offer lower-cost bundles
Tenure	New users churn more	Improve onboarding



🧾 Real-World Considerations

Challenge	Strategy

Imbalanced Classes	Used SMOTE to balance Churn classes
Explainability	Used SHAP to build trust with business stakeholders


📌 Project Deliverables

✅ Cleaned & Analyzed Dataset

✅ EDA Visualizations

✅ Trained ML Models

✅ SHAP Interpretability Visuals

✅ 📄 Business Insight Card

✅ 📄 Client Insight Card

✅ Google Colab Notebook   
✅ GitHub Repository (this README file)





📎 Google Colab Notebook

🔗 https://colab.research.google.com/drive/1xMoluyX_r77lMB72RioEYPUdDxWWJbie#scrollTo=IV_kGBAxXLVd





🔧 Tools & Libraries Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

SHAP

SMOTE (Imbalanced-learn)



🙋‍♀ Author

👩 [Anamta Qureshi]
AI Intern at Digipex Solutions
📅 Submission Date: 23rd July 2025




 Note

This project was submitted as part of the AI Internship Program – Task 2 under the guidance of Muhammad Taimoor, Lead – AI Internship, Digipex Solutions.






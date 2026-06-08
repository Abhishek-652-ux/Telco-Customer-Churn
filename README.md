
# Telco Customer Churn Prediction & Analytics

## 📌 Project Overview
This project targets a core business challenge: predicting customer attrition. Using a dataset of 100,000 subscriber records, I conducted exploratory data analysis (EDA), applied feature engineering to handle categorical variables, and built machine learning models to identify high-risk customer segments.

## 📊 Key Insights from EDA
* **Contract Risks:** Customers on Month-to-Month contracts exhibit significantly higher churn rates compared to those on One-Year or Two-Year terms.
* **Financial Thresholds:** Attrition spikes sharply when a customer's Monthly Charges exceed $100, marking a critical target baseline for pricing optimization.

## 🛠️ Tech Stack & Workflow
* **Data Processing:** Python, Pandas, NumPy
* **Visualization:** Seaborn, Matplotlib
* **Machine Learning:** Scikit-Learn (Logistic Regression, Decision Trees, Random Forests)

## 📈 Model Performance Summary
* **Logistic Regression:** 72.3% Accuracy
* **Decision Tree:** 68.0% Accuracy
* **Random Forest:** 73.1% Accuracy (Best Performing Model)

## 💡 Business Recommendations
1. **Contract Incentives:** Proactively migrate high-risk Month-to-Month subscribers to long-term plans via targeted discounts.
2. **Pricing Safeguards:** Introduce automated retention outreach and value-added loyalty perks once a customer's individual billing profile scales past $100/month.

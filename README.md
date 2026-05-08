# 📊 Telecom Customer Churn Prediction

This repository contains the final project for the **TripleTen Data Science Bootcamp**. The goal is to forecast customer churn for the telecom operator **Interconnect** to enable proactive retention strategies through promotional codes and special plan options.

## 🎯 Business Problem
Interconnect wants to reduce customer attrition. By identifying users who are likely to cancel their service, the marketing team can intervene with loyalty programs and targeted offers.

## 🛠️ Tech Stack
- **Languages:** Python (Pandas, NumPy)
- **Machine Learning:** CatBoost (Gradient Boosting), Scikit-Learn
- **Database:** SQL-like joins for data unification
- **Visualization:** Matplotlib, Seaborn

## 📈 Key Findings (EDA)
- **Tenure:** Newer customers have a significantly higher probability of churn.
- **Contract Type:** "Month-to-month" contracts are the most vulnerable segment.
- **Charges:** Customers with higher monthly charges are more likely to leave, suggesting a need for price-optimization or loyalty discounts.

## 🚀 Model Performance
The final model was built using **CatBoost**, achieving the following results:
- **AUC-ROC:** > 0.85 (High discriminative power)
- **Recall:** 77% (Successfully identified 77% of all customers who actually churned)
- **Precision:** 63% (Ensures marketing efforts are targeted efficiently)

## 📁 Repository Structure
- `Final_Sprint_19.ipynb`: Main Jupyter Notebook with data cleaning, feature engineering, and modeling.
- `EDA.ipynb`: Initial exploratory data analysis.
- `requirements.txt`: List of necessary Python libraries.

---
**Author:** Carlos Andrés Arias Lopez Reyes  
*Data Scientist & Physics Student*

# Telecom Churn Case Study

##  Project Overview
Predicting **high-value customer churn** in the telecom industry using **machine learning** and **dimensionality reduction techniques**.

---

##  Problem Statement
In the competitive telecom industry, **customer churn** poses a major challenge, with an annual churn rate of 15–25%. Retaining customers is more cost-effective than acquiring new ones. The goal is to **predict churn among high-value prepaid customers** and **identify key drivers** of churn so that proactive retention strategies can be implemented.

---

##  Objective

### 1. Predictive Modeling
- Build models using data from June, July, and August to predict churn in September.
- Identify customers in the **"action" phase** — those at high risk of churn.
- Enable targeted actions to prevent customer loss.

### 2. Feature Identification
- Determine significant variables using **PCA** and **classification algorithms**.
- Build an interpretable model to explain **why customers churn**.

### 3. Business Insights
- Provide actionable recommendations.
- Drive strategic decision-making to **improve customer retention**.

---

##  Algorithms and Techniques Used

###  Data Processing
- Importing Necessary Libraries
- Reading and Understanding the Dataset
- Data Preprocessing
- Identifying High-Value Customers
- Churn Tagging
- Data Cleaning & EDA
- Deriving New Features
- Standardization
- Handling Class Imbalance

###  Dimensionality Reduction
- Principal Component Analysis (PCA)

###  Model Building
- Logistic Regression
  - RFE for Feature Selection
  - ROC Curve
- Decision Tree
  - Hyperparameter Tuning
  - ROC Curve
- Random Forest
  - Hyperparameter Tuning
  - ROC Curve
- AdaBoost Classifier

---

## Conclusion

- The models successfully identified high-risk customers, enabling proactive engagement to reduce churn.
- **Top predictors of churn** included:
  - Night calls, roaming charges, total international minutes, VBC usage, recharge frequency, and more.
- **Logistic Regression** and **Random Forest** performed well, offering both accuracy and interpretability.
- **PCA helped reduce noise**, making models more efficient without much performance drop.
- The business can now focus on:
  - Targeted offers for high-risk users.
  - Improving service quality and recharge experience.
  - Enhancing customer engagement in the action phase.
---

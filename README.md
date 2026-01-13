📊 Customer Churn Analysis & High-Risk Customer Prediction
1. Introduction

Customer churn is a major challenge for subscription-based businesses, as losing customers directly impacts revenue and long-term growth.
The goal of this project is to understand the key drivers of customer churn and build a machine learning model to predict high-risk customers early, so that the business can take preventive action before customers leave.

This project combines exploratory data analysis (EDA), machine learning, and business insights, making it suitable for placements and internship evaluation.

2. Dataset Overview

Dataset: Telecom Customer Churn Dataset

Records: ~7,000 customers

Target Variable: Churn (0 = Not Churned, 1 = Churned)

Key features used in analysis:

Tenure

Monthly Charges

Contract Type

Internet Service

Senior Citizen

Churn

3. Exploratory Data Analysis (EDA)

The following EDA charts were created to understand customer behavior and identify churn patterns.

3.1 Churn Distribution

![image alt](https://github.com/nikhil3156/churn-prediction-and-analysis/blob/9fdfab6c7afaa7367e3012c332e20ce3684e4afa/Screenshot%20(190).png)

Insight:
The dataset shows a clear imbalance between churned and non-churned customers, indicating that churn is a significant but not dominant event. This highlights the importance of early detection rather than reactive handling.

3.2 Tenure vs Churn

![image alt](https://github.com/nikhil3156/churn-prediction-and-analysis/blob/9fdfab6c7afaa7367e3012c332e20ce3684e4afa/Screenshot%20(191).png)

Insight:
Customers with low tenure (early months) have a much higher churn rate compared to long-tenure customers.
This indicates that early customer experience is critical, and most churn happens before strong loyalty is built.

3.3 Monthly Charges vs Churn

![image alt](https://github.com/nikhil3156/churn-prediction-and-analysis/blob/9fdfab6c7afaa7367e3012c332e20ce3684e4afa/Screenshot%20(192).png)

Insight:
Customers with higher monthly charges show a noticeably higher churn rate.
This suggests that pricing and perceived value play a major role in churn decisions, especially for customers who feel they are paying more than expected.

3.5 Internet Service vs Churn

![image alt](https://github.com/nikhil3156/churn-prediction-and-analysis/blob/9fdfab6c7afaa7367e3012c332e20ce3684e4afa/Screenshot%20(193).png)

Insight:
Churn behavior varies across internet service types. Certain services show higher churn, indicating service quality or pricing dissatisfaction linked to specific offerings.

3.6 Senior Citizen vs Churn

![image alt](https://github.com/nikhil3156/churn-prediction-and-analysis/blob/9fdfab6c7afaa7367e3012c332e20ce3684e4afa/Screenshot%20(194).png)

Insight:
Senior citizens show a slightly higher churn tendency compared to non-senior customers.
While not a primary churn driver, this demographic factor provides supporting insight for targeted retention strategies.

4. Machine Learning Model

A machine learning classification model was built to predict customer churn.

Model Outputs:

Predicted Churn (0 / 1)

Churn Probability

Risk Level (Low / Medium / High)

The model enables the identification of high-risk customers before actual churn occurs, allowing the business to intervene early.

5. Final Dashboard (Business View)

![image alt](https://github.com/nikhil3156/churn-prediction-and-analysis/blob/9fdfab6c7afaa7367e3012c332e20ce3684e4afa/Screenshot%20(172).png)

The dashboard consolidates:

Actual churn vs predicted churn

High-risk customer identification

Revenue-related churn insights

Customer segmentation for decision-making

This dashboard is designed for management and business stakeholders, not just analysts.

6. Key Business Insights (Summary)

Early churn is the biggest risk: Customers churn most in the initial months.

High-paying customers are more likely to churn: Pricing sensitivity directly affects churn.

Month-to-month contracts drive churn: Long-term contracts improve retention.

A small high-risk group causes major revenue loss: Predicting and acting early is critical.

7. Conclusion & Business Recommendations
Problem Identified

Customer churn is predictable, not random. It is driven primarily by tenure, pricing, and contract type.

Recommended Business Actions

Focus retention efforts on high-risk customers identified by the model

Improve onboarding and engagement during the first few months

Encourage customers to move from month-to-month to long-term contracts

Offer targeted discounts or plans to high-value customers with high churn probability

Final Outcome

By using churn prediction and data-driven insights, a company can:

Reduce customer churn

Protect revenue

Improve customer lifetime value

Make proactive, not reactive, decisions

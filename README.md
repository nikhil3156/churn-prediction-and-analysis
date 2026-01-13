Customer Churn Analysis & Prediction
🔹 Problem Statement

Telecom companies lose significant revenue due to customer churn. The objective of this project is to identify churn patterns, predict high-risk customers, and provide actionable insights that help the business reduce churn and improve retention.

🔹 Dataset

Source: Public Telecom Customer Churn Dataset

Size: ~7,000 customers

Key Columns:

CustomerID

MonthlyCharges

Tenure

Contract Type

Payment Method

Churn (Actual)

Churn Probability (Predicted)

🔹 Tools & Technologies

Python: Data cleaning, EDA, feature engineering

Pandas & NumPy: Data manipulation

Scikit-learn: Churn prediction model

SQL: Aggregations and KPI validation

Power BI: Interactive dashboard & KPIs

GitHub: Project documentation & version control

🔹 Key Steps
1️⃣ Data Cleaning

Removed duplicates and invalid records

Handled missing values using statistical methods

Converted categorical variables into numerical format

2️⃣ Exploratory Data Analysis (EDA)

Analyzed churn distribution

Compared churn vs non-churn customers

Studied relationship between tenure, charges, and churn

3️⃣ Feature Engineering

Created churn labels (0 = No, 1 = Yes)

Derived risk levels based on churn probability

Engineered tenure groups and charge buckets

4️⃣ Modeling & Prediction

Built a classification model to predict churn

Generated churn probability for each customer

Evaluated model using confusion matrix logic

5️⃣ Visualization (Power BI)

KPI cards (Total Customers, Actual Churn, Predicted Churn)

Actual vs Predicted Churn comparison

Confusion Matrix

Risk Level Distribution

Churn Probability slicer for business decision-making

🔹 Key Insights (MOST IMPORTANT)

• High Monthly Charges increase churn:
Customers paying higher-than-average monthly charges show significantly higher churn rates, especially on month-to-month contracts.

• Tenure is a strong churn indicator:
Customers with tenure less than 12 months churn the most, indicating early dissatisfaction.

• Contract type drives retention:
Month-to-month customers churn far more than annual or two-year contract customers, directly impacting revenue stability.

• High-risk customers contribute major revenue risk:
A small percentage of high-risk customers accounts for a large portion of potential revenue loss.

🔹 Dashboard / Output

📌 Power BI Dashboard includes:

Actual vs Predicted Churn

Confusion Matrix

Average Monthly Charge by Risk Level

Churn Probability Threshold Slicer



🔹 Conclusion

This analysis clearly shows that churn is not random — it is driven by pricing, contract type, and customer tenure.

✅ Business Actions Recommended:

Target high-risk customers with retention offers

Incentivize long-term contracts over month-to-month plans

Offer personalized discounts for high-paying, low-tenure customers

Use churn probability threshold to optimize retention cost vs benefit

By acting on these insights, a company can reduce churn, protect revenue, and improve customer lifetime value.

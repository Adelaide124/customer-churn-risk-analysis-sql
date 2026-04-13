# churn-analysis-project-
# Customer Churn Analysis & Risk Segmentation

## Project Overview

This project analyzes customer churn behavior using SQL-based analysis and data visualization.  
The goal is to identify key drivers of churn, segment customers by risk level, and estimate revenue loss due to churned customers.

The project simulates a real-world business scenario where a company wants to improve customer retention and reduce revenue loss.

---

## Business Problem

The company is experiencing customer churn but lacks clear insight into:

- Which customers are most likely to leave
- What factors drive churn
- How much revenue is being lost
- Which segments should be prioritized for retention

---

## 📊 Dataset

The dataset used is the **Telco Customer Churn dataset**, which includes information about:

- Customer demographics
- Subscription details
- Contract type
- Monthly and total charges
- Churn status

---

## Tools Used

- SQL (via SQLite in Google Colab)
- Python (Pandas for querying and visualization)
- Matplotlib for data visualization
- Google Colab

---

## Analysis Performed

### 1. Churn Rate Analysis
- Overall churn distribution
- Churn rate by contract type
- Churn behavior across customer segments

### 2. Customer Segmentation
Customers were segmented into risk groups based on:

- Contract type
- Tenure
- Monthly charges

Segments defined:
- High Risk
- Medium Risk
- Low Risk

---

### 3. Revenue Impact Analysis
- Estimated revenue loss from churned customers
- Identified high-risk customer segments contributing most to revenue loss

---

## Key Insights

- Customers with **month-to-month contracts** show significantly higher churn rates.
- New customers (low tenure) are more likely to churn.
- High-risk customers represent a disproportionate share of revenue loss.
- Retention strategies should focus on early-stage customer engagement.

---

## Visualization

### Churn Rate by Contract Type

This visualization highlights how contract type impacts churn behavior:

*(Insert image here: images/churn_plot.png)*

---

## Business Recommendations

- Encourage long-term contracts to improve retention
- Focus retention efforts on customers in their first 12 months
- Target high-risk customers with proactive engagement strategies
- Investigate pricing and service issues for short-term contract users

---

## Project Outcome

This analysis demonstrates how data-driven insights can be used to:

- Identify churn patterns
- Segment customers by risk
- Estimate financial impact
- Support strategic business decisions

---

## Next Steps

- Build predictive churn model (Logistic Regression or Random Forest)
- Develop dashboard for real-time churn monitoring
- Expand feature engineering for deeper behavioral analysis

---

## Author

Created as a portfolio project focused on SQL-driven data analysis and business intelligence.

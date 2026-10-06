# FUTURE_DS_02

## Customer Retention & Churn Analysis

Customer Retention & Churn Analysis using Python and Jupyter Notebook – Future Interns Task 2.

## 📌 Project Overview

This project analyzes customer churn and retention patterns using the Telco Customer Churn dataset.

The analysis identifies key factors associated with customer churn, high-risk customer segments, customer tenure, contract types, services, payment methods, and customer lifetime value.

## 🎯 Objectives

- Analyze overall customer churn and retention
- Identify major factors influencing customer churn
- Compare churn rates across contract types
- Analyze customer tenure and lifetime patterns
- Identify high-risk customer segments
- Study service and payment-related churn factors
- Provide actionable customer retention recommendations

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📊 Dataset

**Telco Customer Churn Dataset**

The dataset contains customer information including:

- Customer demographics
- Contract type
- Tenure
- Internet service
- Payment method
- Monthly charges
- Total charges
- Customer churn status

After data cleaning, **7,032 customer records** were used for analysis.

## 🔍 Key Findings

- **Overall Churn Rate:** 26.58%
- **Retention Rate:** 73.42%
- **Churned Customers:** 1,869
- **Retained Customers:** 5,163
- **Average Tenure:** 32.42 months
- **Average Monthly Charge:** $64.80

### Contract-Based Churn

| Contract Type | Churn Rate |
|---|---:|
| Month-to-month | 42.71% |
| One year | 11.28% |
| Two year | 2.85% |

Month-to-month customers show significantly higher churn compared with customers on longer-term contracts.

### High-Risk Customer Segment

A high-risk segment was identified using:

- Month-to-month contract
- Fiber optic internet service
- Tenure of 12 months or less

This segment contains **816 customers** with an approximate **70.4% churn rate**.

## 💡 Actionable Recommendations

1. Encourage customers to move from month-to-month contracts to longer-term contracts through loyalty benefits and discounts.
2. Strengthen onboarding and support for new customers.
3. Proactively target high-risk customers with personalized retention campaigns.
4. Improve technical support and customer service.
5. Review payment and billing experiences associated with higher churn.
6. Protect high-value customers through personalized retention offers.
7. Continuously monitor churn patterns across customer segments.

## 📓 Project Files

- `Customer_Retention_Churn_Analysis.ipynb` – Complete Jupyter Notebook analysis
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` – Dataset used for analysis

## 📈 Conclusion

The analysis demonstrates that customer churn is strongly associated with factors such as contract type, tenure, services, and payment methods.

Identifying high-risk customer segments and applying targeted retention strategies can help reduce customer churn, improve customer lifetime value, and strengthen long-term customer relationships.

---

### Future Interns – Data Science & Analytics Task 2

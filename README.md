
# Customer Churn & Retention Analysis

Exploratory data analysis of telecom customer churn aimed at identifying retention drivers, high-risk customer segments, and the financial impact of churn using Python and Pandas.

---

## Business Problem

Customer churn is one of the most significant challenges for subscription-based businesses. For telecommunications companies, losing customers directly impacts recurring revenue and long-term profitability.

This project analyzes telecom customer data to identify the key demographic, behavioral, and service-related factors associated with churn and uncover actionable retention opportunities.

---

## Objectives

- Quantify the financial impact of customer churn
- Identify high-risk customer segments
- Analyze how churn varies across demographics, services, and contract types
- Determine which factors are most strongly associated with retention
- Generate business-focused retention recommendations

---

## Dataset

The dataset contains information for 7,043 telecom customers including:

- Customer demographics
- Subscription details
- Internet and phone services
- Billing and payment information
- Contract type
- Monthly and total charges
- Customer churn status

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

1. Data Understanding  
2. Data Cleaning  
3. Key Performance Indicators (KPIs)  
4. Exploratory Data Analysis (EDA)  
5. Business Insights & Recommendations  

---

## Key Insights

- Customers on month-to-month contracts churned at significantly higher rates than long-term contract customers.
- Churn was heavily concentrated within the first 12 months of customer tenure.
- Fiber optic customers showed unexpectedly high churn despite generating higher monthly revenue.
- Customers without OnlineSecurity and TechSupport services churned at nearly three times the rate of customers who subscribed to them.
- Electronic check payment users exhibited substantially higher churn compared to automatic payment methods.

---

## Business Recommendations

- Encourage long-term contracts through incentives and upgrade offers
- Improve onboarding and engagement during the first year of subscription
- Investigate dissatisfaction drivers among fiber optic customers
- Promote support-oriented services such as OnlineSecurity and TechSupport
- Encourage automatic payment adoption to improve customer retention

---


## Repository Structure

```text
customer-churn-analysis/
│
├── data/
├── notebooks/
├── README.md
└── requirements.txt
```

---

## Conclusion

The analysis shows that customer churn is strongly associated with contract flexibility, early customer tenure, pricing, and support-related services. By targeting high-risk customer segments with focused retention strategies, telecom companies can reduce revenue loss and improve long-term customer loyalty.

# Customer Churn Prediction – Data Analyst Project

## Problem Statement
Customer churn is a major challenge in subscription-based businesses, as acquiring new customers is more costly than retaining existing ones.  
However, businesses often lack clear insights into **which customers are likely to churn and why**.

This project aims to use customer data to:
- Predict customer churn
- Identify key factors driving churn
- Provide actionable business recommendations

---

## Objective
- Analyze customer behavior related to churn  
- Build a predictive model to identify high-risk customers  
- Translate analytical results into business insights  

---

## Dataset
- Telco Customer Churn Dataset  
- Approximately **50,000 customer records**  
- Features include:
  - Contract type
  - Tenure
  - Monthly charges
  - Payment method
  - Additional services
  - Churn status (Yes / No)

---

## Tools & Skills
- Python (pandas, numpy)
- Data Visualization (matplotlib)
- Machine Learning (scikit-learn)
- Logistic Regression
- Exploratory Data Analysis (EDA)
- Business Insight & Data Storytelling

---

## Analysis Workflow
1. Data loading and overview  
2. Exploratory Data Analysis (EDA)  
3. Data cleaning and preprocessing  
4. Feature encoding  
5. Train-test split  
6. Model training (Logistic Regression)  
7. Model evaluation  
8. Business insights and recommendations  

---

## Model Performance

### ROC Curve
![ROC Curve](reports/figures/roc_curve.png)

The ROC curve shows that the model can effectively distinguish between churn and non-churn customers.

### Confusion Matrix
![Confusion Matrix](reports/figures/confusion_matrix.png)

The confusion matrix summarizes the model’s prediction results and shows that the model performs well in identifying non-churn customers while reasonably detecting churn cases.

---

## Key Business Insight
### Contract Type vs Churn
![Contract vs Churn](reports/figures/contract_vs_churn.png)

Customers with **month-to-month contracts** have a significantly higher churn rate compared to customers with long-term contracts.

---

## Key Churn Drivers
- Month-to-month contract  
- Short customer tenure  
- High monthly charges  
- Lack of additional services (e.g., Online Security)  
- Electronic check payment method  

---

## Business Recommendations
- Offer retention promotions for customers with month-to-month contracts  
- Encourage customers to switch to long-term contracts with discounts or benefits  
- Provide bundled services for high-risk customers  
- Design targeted retention campaigns for new customers with low tenure  

---

## Conclusion
This project demonstrates how data analysis and predictive modeling can be applied to understand customer behavior and support business decision-making.  
The insights gained from this analysis can help businesses proactively reduce customer churn and improve customer retention strategies.

---

## Author
**Dolthida**  
Computer Science Student | Aspiring Data Analyst

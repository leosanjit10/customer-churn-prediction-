# Customer Churn Prediction

## Project Overview

This project analyzes customer behavior and builds a machine learning model to predict customer churn. The objective is to identify factors contributing to customer attrition and provide actionable business recommendations.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab

## Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Data Encoding
5. Logistic Regression Modeling
6. Model Evaluation
7. Feature Importance Analysis
8. Business Recommendations

## Key Findings

- Customers on month-to-month contracts exhibited the highest churn rates.
- Customers with shorter tenure were more likely to leave the company.
- Higher monthly charges were associated with increased churn.
- Fiber optic customers demonstrated significantly higher churn levels.
- Electronic check users exhibited higher churn rates than other payment groups.
- Customers without technical support were significantly more likely to churn.
- Long-term contracts, online security, and technical support services were associated with greater customer retention.

---

## Model Performance

- **Model:** Logistic Regression
- **Accuracy:** 82.19%
- **True Negatives:** 934
- **True Positives:** 224

The model demonstrated strong predictive performance and can be used to support customer retention strategies.

---

## Key Visualizations

### Customer Churn Distribution

images/customer_churn_distribution.png

**Insight:** Approximately 26.5% of customers churned, indicating a significant retention challenge for the business.

---

### Contract Type vs Churn

images/contract_type_vs_churn_distribution.png

**Insight:** Customers with month-to-month contracts exhibited substantially higher churn than customers on one-year and two-year contracts.

---

### Customer Tenure vs Churn

images/customer_tenure_vs_churn.png

**Insight:** Customers who churned generally had much shorter tenures, indicating that newer customers are at greater risk of leaving.

---

### Payment Methods vs Churn

images/payment_methods_vs_churn.png

**Insight:** Electronic check users showed the highest churn levels among all payment methods.

---

### Feature Importance

images/feature_importance.png

**Insight:** Fiber optic internet service, paperless billing, and electronic check payment methods were identified as the strongest factors increasing churn.

---

### Confusion Matrix

images/confusion_matrix.png

**Insight:** The Logistic Regression model correctly classified the majority of customers and achieved an overall accuracy of 82.19%.

---

## Business Impact

The analysis identified several key drivers of customer churn. By focusing on contract upgrades, customer onboarding, pricing strategies, payment preferences, online security adoption, and technical support services, the company can improve retention rates and reduce revenue loss.

---

## Project Structure

```text
customer-churn-prediction/
│
├── Customer_Churn_Prediction.ipynb
├── README.md
└── images/
    ├── confusion_matrix.png
    ├── contract_type_vs_churn_distribution.png
    ├── customer_churn_distribution.png
    ├── customer_tenure_vs_churn.png
    ├── feature_importance.png
    └── payment_methods_vs_churn.png
```

## Future Improvements

- Implement Random Forest Classifier
- Implement XGBoost Classifier
- Address class imbalance techniques
- Improve churn recall score
- Build an interactive Streamlit dashboard
- Deploy the model as a web application

## Author

**Sanjit Sitaula**

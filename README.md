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

- Month-to-month customers showed the highest churn rates.
- Customers with shorter tenure were more likely to leave.
- Fiber optic customers exhibited higher churn levels.
- Electronic check users had higher churn rates.
- Customers without technical support were significantly more likely to churn.
- Long-term contracts helped reduce customer churn.

---

## Model Performance

- **Model:** Logistic Regression
- **Accuracy:** 82.19%
- **True Negatives:** 934
- **True Positives:** 224

The model successfully predicts customer churn and can support customer retention strategies.

---

## Key Visualizations

### Contract Type vs Churn

images/contract_type_vs_churn_distribution.png

**Insight:** Customers on month-to-month contracts exhibit significantly higher churn rates than customers on one-year and two-year contracts.

---

### Feature Importance

images/feature_importance.png

**Insight:** Fiber optic internet service, paperless billing, and electronic check payment methods were identified as the strongest factors increasing churn.

---

### Confusion Matrix

images/confusion_matrix.png

**Insight:** The model correctly classified the majority of customers and achieved an overall accuracy of 82.19%.

---

## Business Impact

The analysis identified key factors contributing to customer churn. By focusing on long-term contract adoption, customer onboarding, technical support services, and targeted retention campaigns, the company can improve customer retention and reduce revenue loss.

---

## Project Structure

```text
customer-churn-prediction/
│
├── Customer_Churn_Prediction.ipynb
├── README.md
└── images/
    ├── contract_vs_churn.png
    ├── feature_importance.png
    └── confusion_matrix.png
```

## Future Improvements

- Train Random Forest models
- Train XGBoost models
- Handle class imbalance
- Improve churn recall score
- Deploy the model using Streamlit

## Author

**Sanjit Sitaula**

# Customer Churn Prediction for Retention Strategy Optimization

## Business Problem
Customer churn impacts revenue and growth. Identifying at-risk customers enables proactive retention strategies.

---

## Objective
- Identify customers likely to churn  
- Understand key drivers  
- Support data-driven decisions  

---

## Dataset
Telco Customer Churn dataset with:
- Tenure  
- Monthly Charges  
- Total Charges  
- Contract Type  
- Churn  

---

## Approach

### Data Preprocessing
- Handled missing values  
- Encoded categorical variables  
- Scaled numerical features  

### Exploratory Data Analysis
- Churn vs non-churn distribution  
- Relationships between tenure, charges, and churn  

### Model Development
- Logistic Regression  
- Tree-based models  

### Model Evaluation
- Accuracy  
- Precision & Recall  
- ROC-AUC  

---

## Key Insights
- Higher monthly charges → higher churn probability  
- Longer tenure → lower churn  
- Contract type impacts churn behavior  

These insights support pricing and retention strategies.

---

## Business Impact
- Identify high-risk customers  
- Support retention campaigns  
- Improve customer lifetime value (LTV)  

---

## Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

## Example SQL Query
```sql
SELECT customer_id, tenure, monthly_charges, churn
FROM customer_data
WHERE churn = 1;
```

## Future Improvements
- Feature engineering
- Hyperparameter tuning
- Model deployment
- Model interpretability (SHAP)
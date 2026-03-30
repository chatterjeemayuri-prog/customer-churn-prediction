# Customer Churn Prediction

## Project Overview
This project builds a predictive model to identify customers at risk of churn. Using statistical modeling and machine learning techniques, the goal is to analyze customer behavior and predict which users are most likely to leave.

## Problem Statement
- Identify customers likely to churn  
- Understand key drivers behind churn behavior  
- Support data-driven retention strategies  

## Dataset
The dataset includes customer demographic information, account details, and service usage patterns.

Key variables:
- Tenure  
- Monthly Charges  
- Total Charges  
- Contract Type  
- Churn Indicator  

## Methodology
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature selection  
- Model building (Logistic Regression, Tree-based models)  
- Model evaluation  

## Model Evaluation
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

## Key Insights
- Higher monthly charges → higher churn probability  
- Longer tenure → lower churn  
- Contract type significantly impacts churn behavior  

These insights support pricing and retention strategies.

## Business Impact
- Identify high-risk customers  
- Support retention campaigns  
- Improve customer lifetime value (LTV)  

## Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

## How to Run
1. Open the notebook `churn_analysis.ipynb`  
2. Run all cells  
3. The notebook will:
   - Load and preprocess data  
   - Train models  
   - Evaluate performance  
   - Generate insights  

## Repository Structure
```
customer-churn-prediction/
│
├── data/                  # Dataset files
├── notebooks/
│   └── churn_analysis.ipynb
├── src/                   # Reusable code (optional future use)
├── models/                # Saved models (optional future use)
└── README.md
```

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
# Customer Churn Prediction for Retention Strategy Optimization

## 📌 Business Problem
Customer churn is a major challenge for subscription-based businesses, directly impacting revenue and growth. Identifying customers at risk of leaving allows companies to take proactive retention actions.

---

## 🎯 Objective
Develop a predictive model to:
- Identify customers likely to churn  
- Understand key drivers of churn  
- Support data-driven retention strategies  

---

## 📊 Dataset
Telco Customer Churn dataset containing:
- Customer demographics  
- Account information  
- Service usage patterns  

**Key features:**
- Tenure  
- Monthly Charges  
- Total Charges  
- Contract Type  
- Churn (target variable)  

---

## ⚙️ Approach

### 1. Data Preprocessing
- Handled missing values and data inconsistencies  
- Encoded categorical variables  
- Scaled numerical features  

### 2. Exploratory Data Analysis
- Analyzed churn vs non-churn distribution  
- Examined relationships between tenure, charges, and churn  
- Visualized feature distributions and correlations  

### 3. Feature Engineering
- Selected key predictors influencing churn  
- Evaluated feature importance  

### 4. Model Development
- Logistic Regression  
- Tree-based models (for comparison)  

### 5. Model Evaluation
- Accuracy  
- Precision & Recall  
- ROC-AUC  

---

## 📈 Key Insights
- Customers with **higher monthly charges** show higher churn probability → pricing sensitivity  
- Customers with **longer tenure** are less likely to churn → loyalty effect  
- Contract type significantly impacts churn behavior  

These insights support targeted retention strategies such as pricing adjustments and engagement campaigns.

---

## 🧠 Business Impact
- Enables early identification of high-risk customers  
- Supports retention campaigns and reduces revenue loss  
- Improves customer lifetime value (LTV)  

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

## 🗃️ Example SQL Query (Data Extraction Simulation)
```sql
SELECT customer_id, tenure, monthly_charges, churn
FROM customer_data
WHERE churn = 1;

## 🚀 Future Improvements
- Advanced feature engineering  
- Hyperparameter tuning  
- Model deployment (API/dashboard)  
- SHAP-based interpretability
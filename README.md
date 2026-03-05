# Customer Churn Prediction
Customer churn prediction using logistic regression and exploratory data analysis on telecom customer data.
This project demonstrates an end-to-end machine learning workflow for predicting customer churn using Python.

## Project Overview

This project builds a predictive model to identify customers at risk of churn. 
Using statistical modelling and machine learning techniques, the goal is to 
analyze customer behavior and predict which users are most likely to leave.

The project demonstrates a typical data science workflow:
- Data exploration and preprocessing
- Feature engineering
- Model development and evaluation
- Visualization of insights

Tools used: Python, pandas, scikit-learn, matplotlib.

## Exploratory Data Analysis

Initial analysis of the telecom dataset includes:
- distribution of churn vs non-churn customers
- summary statistics of key variables
- visualization of relationships between tenure, charges, and churn

This step helps understand patterns in customer behavior before model development.

## Key Results

- Built predictive models to identify customers likely to churn.
- Evaluated multiple algorithms including Logistic Regression and tree-based models.
- Compared model performance using metrics such as accuracy, precision, recall, and ROC-AUC.
- Identified key features influencing churn behaviour.
- Produced visualizations to interpret model performance and feature importance.

This project illustrates how statistical modelling can be applied to real business problems such as customer retention.

## Modeling Approach

The project demonstrates a simple churn prediction workflow:

1. Load telecom customer dataset
2. Prepare numerical features
3. Split the dataset into training and test sets
4. Train a Logistic Regression model
5. Evaluate model performance using classification metrics

The example model uses:

- Tenure
- Monthly Charges
- Total Charges

as predictive features for customer churn.

This project illustrates the basic structure of a machine learning pipeline for churn prediction.

## Example Output

The logistic regression model produces a classification report evaluating churn prediction performance.

Typical output structure:

```
precision    recall  f1-score   support

0       0.xx      0.xx      0.xx        n
1       0.xx      0.xx      0.xx        n

accuracy                           0.xx
```

This demonstrates the workflow for training and evaluating a churn prediction model using scikit-learn.


## Project Structure

```
customer-churn-prediction
│
├── data/              # Dataset files
├── notebooks/         # Jupyter notebooks for analysis
│   └── churn_analysis.ipynb
├── src/               # Reusable code (future)
├── models/            # Saved models (future)
└── README.md
```

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Future Work

- Feature engineering
- Model comparison
- Model evaluation
- Model deployment

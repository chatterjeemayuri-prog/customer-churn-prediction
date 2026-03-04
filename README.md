# Customer Churn Prediction

This project demonstrates an end-to-end machine learning workflow for predicting customer churn using Python.

## Project Overview

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

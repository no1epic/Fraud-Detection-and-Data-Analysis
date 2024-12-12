# Final Project - Fraud Detection and Data Analysis

This repository contains two Jupyter notebooks analyzing and predicting fraud in healthcare claims. The project involves exploratory data analysis (EDA), feature engineering, and machine learning model implementation to identify potential fraudulent claims. The analysis utilizes datasets with attributes related to healthcare services, patient demographics, and billing information.

## Contents
1. **Final_Project.ipynb**: 
   - Implements data preprocessing and fraud prediction models.
   - Utilizes metrics such as precision, recall, and F1-score for evaluation.
   - Key outputs:
     - Fraud distribution statistics.
     - Classification reports for multiple models.
     - Random forest results with accuracy and hyperparameters.

2. **final_project_eda.ipynb**:
   - Focuses on exploratory data analysis (EDA).
   - Highlights statistical summaries of key variables.
   - Investigates patterns in reimbursement and co-payment amounts across conditions.

## Key Features
- **Data Cleaning and Preprocessing**:
  - Prepares raw data for analysis.
  - Handles missing values and normalizes feature distributions.

- **EDA Highlights**:
  - Average reimbursement and co-payment amounts by chronic conditions.
  - Fraudulent claim trends and distribution patterns.

- **Machine Learning Models**:
  - Multiple classifiers tested, including Random Forest.
  - Hyperparameter tuning and performance evaluation.

## Outputs
- Fraud prediction performance metrics:
  - Precision, Recall, F1-score, and Accuracy.
- Statistical summaries and visualizations:
  - Average inpatient and outpatient reimbursement amounts.

## Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Libraries:
  - `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `pyspark` (for specific tasks).

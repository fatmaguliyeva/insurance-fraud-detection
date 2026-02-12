# Insurance Fraud Detection

## Overview
This project detects fraudulent insurance claims using machine learning.
The workflow is split into two notebooks:

- `notebooks/01_data_cleaning.ipynb` — Data cleaning, and exploratory data analysis (EDA)
- `notebooks/02_modeling_ml.ipynb` — Model training, evaluation, threshold tuning, and ensemble methods

## Workflow
1) Run `01_data_cleaning.ipynb` to prepare the dataset  
2) Run `02_modeling_ml.ipynb` to train and evaluate models  

## Models
- Logistic Regression  
- Random Forest  
- Support Vector Classifier (SVC)  
- Voting Classifier (Soft/Hard)  
- Stacking Classifier  

## Evaluation
Metrics used: Accuracy, Precision, Recall, F1-Score, ROC-AUC.  
Threshold tuning is applied to optimize the Precision/Recall trade-off for fraud detection.

## Dashboard (Power BI)
Screenshots are located in the `reports/` folder.

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Power BI

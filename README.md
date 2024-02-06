# Telco Customer Churn Prediction

## About Dataset
The Telco Customer Churn dataset provides information about customers' behavior to predict churn, enabling the analysis of relevant customer data and the development of focused retention programs. Each row represents a customer, with columns containing customer attributes such as services subscribed to, account information, and demographic details.

## Code Overview
The project consists of two Jupyter Notebooks: `telco-customer-churn.ipynb` and `telco-customer-churn-final.ipynb`. In `telco-customer-churn-final.ipynb`, the final model is developed and evaluated using machine learning techniques.

## Model Development
The Random Forest Classification model is implemented to predict customer churn. The dataset is preprocessed, categorical features are encoded, and the model is trained using undersampling techniques to address class imbalance.

## Metrics and Evaluation
The model's performance is evaluated using precision, recall, F1-score, and confusion matrix. The Random Forest Classification Undersampled model is selected as the preferred choice for customer retention efforts due to its robust recall for identifying churn cases.

## Setup Environment
To set up the environment, run the following command:
```conda env create --file environment.yml --name env```
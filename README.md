
# Customer Churn Prediction

## Project Overview
This project uses Machine Learning to predict whether a telecom customer is likely to leave the company (churn) based on customer information, services, contract details, and billing data.

## Dataset
- IBM Telco Customer Churn Dataset
- 7,043 customer records
- 19 input features
- Binary classification target: Churn (Yes/No)

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Google Colab

## Project Workflow
1. Data loading and exploration
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature encoding and scaling
5. Training and comparing classification models
6. Handling class imbalance
7. Threshold tuning
8. Model evaluation using Precision, Recall, F1-score and ROC-AUC
9. Saving and testing the trained model

## Models Evaluated
- Logistic Regression
- Decision Tree
- Random Forest

## Results

Original Logistic Regression:
- Accuracy: 80.55%
- Precision: 65.72%
- Recall: 55.88%
- F1-score: 60.40%
- ROC-AUC: 0.8421

Balanced Logistic Regression:
- Accuracy: 73.81%
- Precision: 50.43%
- Recall: 78.34%
- F1-score: 61.36%
- ROC-AUC: 0.8416

## Key Learnings
- Data cleaning and preprocessing
- Exploratory Data Analysis
- Binary classification
- Handling imbalanced datasets
- Threshold tuning
- Model comparison and evaluation
- Building reusable ML pipelines

## Model Deployment Preparation
The trained Logistic Regression pipeline is saved as `customer_churn_model.pkl`.

It includes preprocessing and prediction in one pipeline and was tested on a new customer record.

## Future Improvements
- Hyperparameter tuning
- Cross-validation
- Further threshold optimization
- Deployment using Flask or FastAPI

## Author
B.Tech Computer Science Engineering Student

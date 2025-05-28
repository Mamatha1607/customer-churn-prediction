# Customer Churn Prediction

## Overview

This project focuses on predicting customer churn using historical data from a telecommunications company. By analyzing key customer attributes and behavioral patterns, the goal is to develop a model that identifies customers likely to discontinue services. This helps businesses take proactive measures to improve retention.

## Dataset

- **Source**: Telco Customer Churn Dataset from Kaggle  
- **Records**: 7,043 customers  
- **Features**: Demographics, contract type, service usage, monthly charges, and churn status  

## Objective

- Analyze customer attributes to uncover patterns influencing churn
- Build a machine learning model to predict churn with high accuracy
- Provide actionable insights to reduce churn and improve customer retention strategies

## Tools & Technologies

- Python, Pandas, NumPy  
- Matplotlib, Seaborn for visualization  
- Scikit-learn for machine learning  
- Jupyter Notebook for interactive development  

## Data Preprocessing

- Removed irrelevant identifiers (e.g., customerID)
- Converted total charges to numeric format and handled missing values
- Encoded categorical variables using one-hot encoding
- Scaled numerical features for model optimization

## Exploratory Data Analysis (EDA)

- Customers with month-to-month contracts showed higher churn rates
- High monthly charges were strongly associated with churn
- Services like Tech Support and Online Security correlated with lower churn

## Model Building

- Model Used: Logistic Regression
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score
- Train-Test Split: 80/20 with stratification on churn
- Feature Scaling: StandardScaler applied to numerical features

## Results

- **Model Accuracy**: 82%  
- **F1-Score (Churn class)**: 0.76  
- Visualized performance using confusion matrix and classification report

## Business Insights

- Month-to-month contracts increase churn risk — recommending longer-term contract incentives
- Customers with high monthly charges and limited support are more likely to churn
- Retention campaigns should target high-risk profiles identified by the model

## Conclusion

The churn prediction model provides valuable insights into customer behavior and enables data-driven retention strategies. Businesses can leverage these findings to enhance customer experience, reduce attrition, and increase long-term value.


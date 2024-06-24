# credit-risk-classification
Credit Risk Classification Analysis
Overview
In this analysis, we utilized machine learning models to assess credit risk using historical lending data from a peer-to-peer lending services company. The objective was to predict whether loans are likely to be 'healthy' or 'high-risk' based on various financial indicators.

Data Description
The dataset (lending_data.csv) includes financial information such as loan amount, interest rate, borrower's credit score, and other relevant factors. The target variable, loan_status, is binary:

0: Healthy loans
1: High-risk loans
Machine Learning Process
Data Preprocessing: The dataset was read into a Pandas DataFrame, and EDA (Exploratory Data Analysis) was conducted to understand the distribution of classes and identify any preprocessing needs.

Model Selection: Logistic Regression was chosen as the initial model due to its interpretability and suitability for binary classification tasks.

Model Training and Evaluation:

The data was split into training and testing sets using train_test_split.
The logistic regression model was trained on the training data and evaluated on the testing data using metrics such as accuracy, precision, recall, and F1-score.
Results
Logistic Regression Model Performance
Accuracy: 99%
Precision:
Class 0 (Healthy Loan): 1.00
Class 1 (High-Risk Loan): 0.86
Recall:
Class 0 (Healthy Loan): 0.99
Class 1 (High-Risk Loan): 0.94
Summary
The logistic regression model demonstrated high accuracy and strong performance in predicting both healthy and high-risk loans. It achieved near-perfect precision for healthy loans (0) and good precision for high-risk loans (1). The recall scores were also commendable, especially for class 0.

Recommendation
Based on these results, the logistic regression model appears well-suited for the initial screening of loan applications, particularly in identifying healthy loans with high precision and recall. However, further efforts could focus on improving the model's ability to detect high-risk loans (1) more effectively, possibly through additional feature engineering or exploring alternative algorithms.

Given the importance of accurately identifying high-risk loans to mitigate potential losses, ongoing refinement and evaluation against larger datasets or more complex scenarios would be advisable.

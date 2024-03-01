# credit-risk-classification
# Module 20 Credit Risk Classification Challenge Report

# Credit Risk Analysis

I completed the following analysis for the Credit Risk Challenge
I used the following financial report which included the following data

File included in the following folder
- Credit Risk / Resources / lending data

Date included in file
- loan size
- interest rate
- borrower income
- dept to income
- number of accounts
- degorgatory marks
- total debt
- Loan status (healthy or default)

- Analysis Files
- credit_risk_classification_RG - my analysis code
- credit_risk_classification - starter code

I used this data to predict the probability that someone would default on a loan

I completed the following analysis 

# Split the Data into Training and Testing Sets
- Split the data into training and testing datasets by using train_test_split.

# Created a Logistic Regression Model with the Original Data
- Fit a logistic regression model by using the training data (X_train and y_train).
- Saved the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
- Evaluated the model’s performance by doing the following:
  - Printed a balanced accuracy report
  - Generated a confusion matrix.
  - Printed the classification report.
- Used RandomOverSampler to adjust the data into a more balanced data set. I then ran the following on the balanced data set
  - Printed a balanced accuracy report
  - Generated a confusion matrix.
  - Printed the classification report.

# Analysis Findings
The financial information data provided data on historical healthy and high-risk loans which allowed me to run analysis on the data to help predict future high-risk loans.
I ran the reports listed above to help predict future high-risk loans.
I first split the data to look at the original data which is an unbalanced data set.
I then used Random over sampling to balance the data set for a more accurate prediction of high risk loans.
The logistic regression model predicts the 0 (healthy loans) at around 99% accuracy and the 1 (high-risk loans) at 85-87% accuracy. 

# Results
## Original Data Machine Learning Model 1:
- Original Data Model 1 
- Balanced Accuracy Score - 94.5%
- Classification Report
  - Accuracy score - 99%
  - Precision - 100 % - 0 (Healthy Loans) / 85% (training) 87% (test) - (High-risk loans)
  - Recall scores - 100 % - 0 (Healthy Loans) and 89% - (High-risk loans)

## Rebalanced Data Machine Learning Model 2:
- Rebalanced Data Model 2
- Balanced Accuracy Score - 99.6%
- Classification Report
  - Accuracy score - 99%
  - Precision - 100 % - 0 (Healthy Loans) and 87% - (High-risk loans)
  - Recall scores - 100 % 

# Summary
- The logistic regression model predicts the 0 (healthy loans) at around 99% accuracy and the 1 (high-risk loans) at 85-87% precision. 
- The prediction accuracy is slightly more accurate with the balanced report using the Random Oversampler.  I would recommend using the RandomOverSampler for a more accurate reading.
- I would also recommend including checks and balances to evaluate customers that could be falsely flagged as high risk as well as customers that might be falsely rated as a healthy risk.
- It is most likely more important to the financial institution to correctly identify high risk loans even if the model identifies some customers to be high risk that are not high risk.

# Resources
I received help from the following
- Tutor - Kelli Kennedy
- TA - Manuel Eduardo Sotelo Cervante
- Instructor - Rufel Estrada

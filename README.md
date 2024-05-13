# Module 12 Report 
Completed by Ashleigh Wittenberg

## Overview of the Analysis

The purpose of the analysis is to build a model that can identify the creditworthiness of borrowers.
The dataset catagories used were: loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt, loan_status.
The stages of the process are as follows:
  Read in the csv file containing the initial dataset
  Seperated the y variable from the X features
  Split the data into training and testing
  Created, fitted, and perdicted a logistic regression model
  Created a confusion matrix
  Printed the classification report

Model 1: Logistic Regression

-Accuracy: 0.99
-Precision (healthy loan): 1.00
-Recall (healthy loan): 1.00
-F1-score (healthy loan): 1.00
-Precision (high-risk loan): 0.87
-Recall (high-risk loan): 0.89
-F1-score (high-risk loan): 0.88

Accuracy (Overall Performance):
The logistic regression model achieved an accuracy score of 0.99, indicating that it correctly predicted the loan status for 99% of the instances in the dataset.

Precision (Ability to Avoid False Positives):
For the "healthy loan" class, the precision score is 1.00. This means that when the model predicts a loan as "healthy", it is correct 100% of the time, minimizing false positives.
For the "high-risk loan" class, the precision score is 0.87. This indicates that when the model predicts a loan as "high-risk", it is correct around 87% of the time, suggesting a low rate of false positives.

Recall (Ability to Capture True Positives):
For the "healthy loan" class, the recall score is 1.00. This means that the model correctly identifies all instances of "healthy loans" in the dataset, indicating no false negatives.
For the "high-risk loan" class, the recall score is 0.89. This indicates that the model captures around 89% of the true "high-risk loans" in the dataset, suggesting a low rate of false negatives.

Overall, the Logistic Regression model is recommended for use by the company due to its high accuracy, balanced precision and recall, consistency in performance, interpretability, and efficiency. It provides a reliable framework for predicting loan status, enabling the
company to make informed decisions regarding lending practices.

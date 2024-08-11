# credit-risk-classification
Module 20 Challenge

ANALYSIS OVERVIEW

The purpose of this analysis is to create a machine learning model to best predict the credit worthiness of borrowers based on their data provided. 

The data provided for each client possessed the features:
Loan Size
Interest Rate
Borrower Income
Debt-To-Income
Number of Accounts
Derogatory Marks
Total Debt
Loan Status

Based off of these features, the model is to predict whether providing a loan to a borrower would be a healthy loan or a high-risk loan. A healthy loan is noted with 0 and high-risk loan is labeled as 1. 

Using a logistic regression model, it predicts whether a loan is healthy or high-risk and using a confusion matrix, it provided instances where the model correctly and incorrectly predicted positive and negative classes. 

[[18655   110]
 [   36   583]]

 Out of the 19,384 rows of data, 18,765 of the records were predicted correctly.

 Then using a classification report, we obtained these results.

                precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.94      0.89       619

    accuracy                           0.99     19384
   macro avg       0.92      0.97      0.94     19384
weighted avg       0.99      0.99      0.99     19384

-Based on the classification report, the accuracy of the model is 99% out of the 19,384 records.

-Precision for healthy loans (0) prediction, is at 100% out of the 18,765 records. As for high-risk loans, it had a precision of 84% out of 619 records.

-Recall was 99% for healthy loans and 94% for high-risk loans. This means the proportion of actual instances were 99% predicted correctly and 94%.

RESULTS

Overall, from the model and logistic report, there is a high percentage of accuracy and precision when it comes to predicting whether a loan is healthy or high-risk based on the data provided per borrower. Based on the report, predicting which borrower would be a healthy loan is accurate and precise as it's close to 100% if not 100%. However when it comes to high-risk loan, it becomes a lot less accurate, but still high at 84% precision. This model would be recommended for use as it has a high precision rate as well as accuracy. Although precision drops when it comes to high-risk loans, it only has 619 records as compared to 18,765 in healthy loans. Providing more records for high-risk loans may provide greater insight on the precision and accuracy for the model. According to the model, healthy loans will be identified and it's 100%, therefore the company should rely on it when it comes to healthy loans, but train the model more on high-risk loans. 
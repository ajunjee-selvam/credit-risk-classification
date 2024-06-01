# credit-risk-classification

This project involved applying machine learning concepts to split data and create a Logistic Regression model for classifying loan risk data using historical lending activity data from a lending services company.

The following libraries and dependencies were used to split the data, create the model, and evaluate its performance:
- numpy
- pandas
- pathlib
- sklearn; confusion_matrix, classification_report

## Credit Risk Analysis Report
### Overview
The purpose of this Credit Risk Analysis Report is to evaluate the reliability of the Logistic Regression model that was created and trained on the provided dataset. Evaluating the performance of the created model is essential for determining whether the lending company can reliably use the model for classifying loans which can save them time and money, or if they would be at a high risk of incorrect classifications leading to loss of business and funds, and potentially, bankrupcy. 

### Results 
The logistic regression model:
- has an weighted accuracy of 99%
- predicted healthy loans 100% of the time
- predicted high-risk loans 84% of the time
- recalled healthy loan predictions 99% of the time (1% mistakes)
- recalled high-risk loan predictions 94% of the time (6% mistakes) 

### Summary 
The most desirable model would be one with high accuracy in classifying healthy loans and high-risk loans, and with minimal mistakes. 

While classifying a healthy loan as a high-risk loan (false positives) may cause the lending company to lose business, classifying a high-risk loan as a healthy loan (false negatives) could result in the loss of funds that the lender had granted. 
- 36 False Positives - classified loan as high-risk when it was actually healthy
- 110 False Negatives - classified loan as healthy when it was actually high-risk

Given the high accuracy (99%) and low degree of mistakes (1%), I would recommend this log model for use by the company in classifying and distinguishing between healthy and high-risk loans. 
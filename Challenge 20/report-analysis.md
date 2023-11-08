# Module 12 Report Template

## Overview of the Analysis

The objective of this study was to develop a predictive model capable of assessing the creditworthiness of individuals seeking loans. The model's predictions were anchored on a range of variables, including the size of the loan, the applicable interest rate, the borrower's income level, their debt-to-income ratio, the number of credit accounts open, the presence of any derogatory marks, and the total accumulated debt. The data set under examination comprised 75,036 borrowers who were in good standing with their loan repayments and an additional 2,500 borrowers who were identified as having a high likelihood of default.

The methodology implemented in this analysis involved several key steps. Initially, the available data was divided into two segments: the labels (y = loan status) and the features (which encompassed the remaining data points). Subsequently, the data was partitioned into two distinct sets, one for training and the other for testing purposes.

A logistic regression model was then calibrated using the training data. Following this, the model was employed to generate predictions based on the testing data. To gauge the efficacy of the model, its accuracy was quantified, a confusion matrix was constructed, and a classification report was generated and scrutinized.

As a means of comparison, the entire process was replicated with a set of training data that had been subjected to resampling, with the aim of evaluating any differences in performance between the two models.

## Results



* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

  - Accuracy: 99%. high accuracy percentage.
  - Precision: 100% for 0 (healthy loan) and 86% for 1 (high-risk loan). The model was better at calculating healthy loans than high-risk loans.
   - Recall: The model was able to catch 99% of healthy loans and 91% of high-risk loans.


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
 - Accuracy: 99%. This was a really high accuracy percentage.
 - Precision: 100% for 0 (healthy loan) and 85% for 1 (high-risk loan). The model was better at calculating healthy loans than high-risk loans.
Recall: The model was able to catch 99% of healthy loans and 99% of high-risk loans.
 - Recall: The model was able to catch 99% of healthy loans and 99% of high-risk loans.
## Summary

Model two is preferable for its higher recall in identifying high-risk loans, which is our primary concern. While it has a lower precision at 85% for these loans, understanding the business implications of this trade-off is crucial before deciding on its deployment.


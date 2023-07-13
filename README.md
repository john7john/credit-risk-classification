# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Purpose of the analysis is to predict the probablity of high-risk applicants in order to reduce total number of defaults on bank loans.
* A dataset of historical lending activity from a peer-to-peer lending services company was used.
* Dependant variable (y value) in this analysis was the "loan status" indicating if a loan is healthy or at risk.
* Independent Variables (x values) were loan size, interest rate, borrower income, debt to income ratio, number of accounts and derogatory marks.
* Describe the stages of the machine learning process you went through as part of this analysis.
* Two diffeent Logistic Regression models were created by using the original data set and randomy over resampled data set (to get rid of the imbalances). In the end, their results -which was gathered with scikit-learn library- were compared.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Balance Accuracy Score: 94.8%.
  * Precision: Model predicted with 100% accuracy low-risk loans, 84% high-risk loans .
  * Recall: high-risk @90%, low-risk @99%
  



* Machine Learning Model 2:
  *  Balance Accuracy -: 99.4%
     Precision- Model predicted with 100% accuracy low-risk loans, 84% high-risk loans
     Recall scores- high-risk @99%, low-risk @99%

## Summary

 * This model currently works better than the industry stanard, given this number of samples and data points.
 * Discerning potential high-risk loan holders is of most importance, because those accounts are responsible for the majority of the bank's lost    earning potential.This single category, when managed correctly, can increase the institution's bottom line by over 1000 basis points.


# Module 12 Report 

## Overview of the Analysis

In this challenge, we were provided a document containing lending data to analyze risks associated with lending. This includes historical data, and will be used to predict healthy or high risk loan scores.

* Purpose of Research: To build a model that can to identify and predict a creditholder's creditworthiness. 
* This data was composed of historical data regarding lending, including loan_status, which can determine a healthy loan or a high risk loan.
* First, I prepared the data and separated the "loan_status" column from the main table. I then split the data for training using `train_test_split`. Following that, I created a `LogisticRegression` model, and generated a `confusion_maxtrix` prediction and `classification_report`.

## Results

As can be seen through the implementation of `LogisticRegression`, the model's accuracy is at 99%, showing that it is very precise for healthy loans, but shows that work needs to be done for the high risk loans. 

* Machine Learning Model 1:
        * Accuracy Score: 99%
        * Precision for Healthy Loans: 100%
        * Precision for High Risk Loans: 85%
        * Recall for Healthy Loans: 99%
        * Recall for High Risk Loans: 91%


## Summary

After analyzing this data, we can infer that the use of a Logistic Regression model demonstrated high accuracy and precision for most healthy loans, although it was found to be less effective in precision and recall for high risk loans. 

        * Healthy Loans: Highly successful (100%, 99%)
        * High Risk Loans: Less successful (85%, 91%)

Although work needs to be done to improve this model, it is overall highly effective and can be recommended as a way to assess a loan risk. 
        
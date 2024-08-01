# Module 12 Report Template

## Overview of the Analysis

* The purpose of the analysis is to develop and evaluate machine learning models to predict credit risk, i.e., to determine whether a borrower will be able to meet their payment obligations.

* The financial data used in this analysis includes various features related to individuals' credit profiles. The goal is to predict High-Risk Loans(1) or Healthy Loans(0).

### Data Preprocessing

* Read the data from lending_data.csv into a Pandas DataFrame and separating the features (X) from the target variable (y), and splitting the data into training and testing sets.


### Model Training

*Use LogisticRegression to build the model and fit the model using the training data.

### Model Evaluation

* Make predictions using the testing data and evaluate the model's accuracy, confusion matrix, and classification report.

## Results

### Machine Learning Model 1: Logistic Regression

* **Accuracy**: 0.99
* **Precision**:
  * Healthy Loan (0): 1.00
  * High-Risk Loan (1): 0.84
* **Recall**:
  * Healthy Loan (0): 0.99
  * High-Risk Loan (1): 0.94
* **F1-Score**:
  * Healthy Loan (0): 1.00
  * High-Risk Loan (1): 0.89

## Summary

The logistic regression model performs exceptionally well for predicting healthy loans with perfect scores in precision, recall, and F1. It also shows strong performance in predicting high-risk loans, with a precision of 0.84 and a recall of 0.94. Given the high accuracy of 99%, the model is highly reliable for predicting loan statuses.

The performance does depend on the problem we are trying to solve. If the priority is to avoid high-risk loans, the model's recall for high-risk loans (0.94) is crucial.

**Recommendation**: I recommend using this logistic regression model for evaluating loan applications due to its high overall accuracy and strong performance in identifying both healthy and high-risk loans.







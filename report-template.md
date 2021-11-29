# Module 12 Report Template

## Overview of the Analysis

* Explain the purpose of the analysis.
The PURPOSE of this analysis was to evaluate whether the imbalanced data or oversampled data used in the logistic regression model was more effective in predicting high-risk loans.

* Explain what financial information the data was on, and what you needed to predict.
The lending_data.csv file provided 77536 count of borrower information that included loan size, interest rate, borrower income, number of accounts, derogatory marks, total debt and loan status. 

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`). 
The initial goal was to separate the labels from the features by assigning y to the labels and x to the features from the data frame created by the information inside the csv file. The value_counts function was used to provide a numerical value to the credit worthiness of the borrowers with the assigned integer of 0 or 1.

* Describe the stages of the machine learning process you went through as part of this analysis.
I split the data into training and testing datasets using train_test_split. I fit the logistic regression model by using the training data x_train and y_train. 

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
        


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

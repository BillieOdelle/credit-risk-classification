# credit-risk-classification
Module 20

Analysis Overview

The objective of this analysis was to develop a model capable of accurately identifying the creditworthiness of borrowers. The dataset includes income, interest rate, and loan details.

The analysis commenced by dividing the data into distinct training and testing datasets utilizing the "train_test_split" method. The "X" and "y" variables were employed to represent the labels and features, respectively.  Notably, the loan_status column was deliberately dropped to ensure precise training and prediction of the corresponding target variable.

Two machine learning algorithms, namely Logistic Regression and Random Forest Classifier, were employed to construct the models. Logistic Regression, a linear classifier, adeptly models the relationship between features and the target variable. Conversely, the Random Forest Classifier assembles an ensemble of decision trees to achieve superior classification accuracy.

Results

Machine Learning Model 1: 
• 	Balanced Accuracy: 0.94 
• 	Precision: 0.92 
• 	Recall: 0.95

Machine Learning Model 2: 
• 	Balanced Accuracy: 0.99 
• 	Precision: 0.99 
• 	Recall: 0.99

Summary

Both Model 1 and Model 2 demonstrated commendable performance in the classification task, with Model 2 marginally surpassing Model 1 in terms of balanced accuracy, precision, and recall scores.

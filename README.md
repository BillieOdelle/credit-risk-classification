# credit-risk-classification
Module 20

Analysis:

The objective of this analysis was to develop a model for creditworthiness prediction, using income, interest rate, and loan details as features. The motivation behind this analysis is likely to help lenders and financial institutions assess the risk associated with potential borrowers more accurately. By accurately identifying creditworthy borrowers, lenders can make informed decisions, minimize default rates, and manage their lending portfolios more effectively.

The dataset was divided into training and testing sets using the "train_test_split" method, which is a standard practice in machine learning to evaluate model performance on unseen data. The features (X) and the target variable (y) were separated, and the loan_status column was dropped from the features to ensure that the model is not trained on the target variable itself.

Two machine learning algorithms were used to build the models: Logistic Regression and Random Forest Classifier.

1. Logistic Regression: This linear classifier is a common choice for binary classification tasks. It models the relationship between the features and the target variable, trying to find the best decision boundary to separate the two classes (creditworthy and non-creditworthy borrowers).

2. Random Forest Classifier: This algorithm constructs an ensemble of decision trees and combines their predictions to achieve better classification accuracy. Random Forests are known for their ability to handle complex relationships between features and the target variable, often resulting in more accurate predictions.

Results Interpretation:

1. Machine Learning Model 1:
   - Balanced Accuracy: 0.94
   - Precision: 0.92
   - Recall: 0.95

2. Machine Learning Model 2:
   - Balanced Accuracy: 0.99
   - Precision: 0.99
   - Recall: 0.99

The metrics used for evaluation are:
- Balanced Accuracy: The average of sensitivity (true positive rate) and specificity (true negative rate). It provides a balanced view of the model's performance on both classes and is especially useful when the classes are imbalanced.
- Precision: The proportion of true positive predictions (creditworthy borrowers) out of all positive predictions made by the model (true positive + false positive).
- Recall: The proportion of true positive predictions (creditworthy borrowers) out of all actual positive instances (true positive + false negative).

Summary:

Both Model 1 and Model 2 performed exceptionally well in the creditworthiness classification task, with Model 2 slightly outperforming Model 1 in terms of balanced accuracy, precision, and recall scores. A balanced accuracy of 0.99 indicates that the models are excellent at correctly classifying both creditworthy and non-creditworthy borrowers. The high precision and recall values (both close to 1.0) imply that the models are making accurate predictions with very few false positives and false negatives.

The high performance of Model 2 suggests that the ensemble approach of the Random Forest Classifier was successful in capturing complex relationships within the data, leading to superior predictive accuracy compared to Logistic Regression.

Overall, these models could be of great use to financial institutions and lenders as reliable tools for assessing creditworthiness, assisting them in making more informed and less risky lending decisions. However, it's essential to ensure that the models are continually monitored and updated as new data becomes available to maintain their effectiveness over time. Additionally, further analysis could be performed to understand the most influential features and potential areas for improvement in the creditworthiness assessment process.

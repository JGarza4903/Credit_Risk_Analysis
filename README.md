# Credit_Risk_Analysis
## Overview of the Analysis:
The purpose of this analysis is to evaluate the performance of six different machine learning models on an imbalanced dataset. The dataset contains information about loan applications and the target variable is the loan status, where 1 represents high-risk loans and 0 represents low-risk loans. The dataset is highly imbalanced, with only around 15% of the data being high-risk loans.

## Results:

### Logistic Regression (Random Oversampling)
* Balanced accuracy score: 0.637
* Precision score: 0.64
* Recall score: 0.65
### Logistic Regression (SMOTEENN)
* Balanced accuracy score: 0.636
* Precision score: 0.64
* Recall score: 0.65
### Logistic Regression (BalancedRandomForestClassifier)
* Balanced accuracy score: 0.636
* Precision score: 0.64
* Recall score: 0.65
### Logistic Regression (EasyEnsembleClassifier)
* Balanced accuracy score: 0.65
* Precision score: 0.64
* Recall score: 0.65

## Summary:
Based on the results, it can be seen that the balanced accuracy scores and precision and recall scores of all the models are quite similar. The highest balanced accuracy score is achieved by EasyEnsembleClassifier with a score of 0.65. However, the difference in score is not significant and all the models performed similarly.

Therefore, it is recommended to use the EasyEnsembleClassifier as it has a slightly higher balanced accuracy score and it is an ensemble method that combines multiple balanced subsets of the data to create an ensemble of classifiers, which can improve the overall performance of the model.

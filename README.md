# Credit_Risk_Analysis
## Overview of the Analysis:
The purpose of this analysis is to evaluate the performance of six different machine learning models on an imbalanced dataset. The dataset contains information about loan applications and the target variable is the loan status, where 1 represents high-risk loans and 0 represents low-risk loans. 

## Results:

### BalancedRandomForestClassifier
* Balanced accuracy score: 0.778
* Precision score: 0.04
* Recall score: 0.64
### EasyEnsembleClassifier
* Balanced accuracy score: 0.906
* Precision score: 0.07
* Recall score: 0.88
### SMOTE
* Balanced accuracy score: 0.661
* Precision: 0.01
* Recall: 0.67
### SMOTEENN
* Balanced accuracy score: 0.664
* Precision score: 0.01
* Recall score: 0.69
### ClusterCentroids:
* Balanced accuracy score: 0.504
* Precision: 0.01
* Recall: 0.61
### Random Oversampling
* Balanced accuracy score: 0.632
* Precision score: 0.01
* Recall score: 0.71

## Summary:
Based on the results, the best performing model is the EasyEnsembleClassifier, with a balanced accuracy score of 0.906, precision of 0.07 and recall of 0.88. This model has the highest balanced accuracy score and the highest precision among the models tried.

The other models have lower balanced accuracy scores and lower precision scores, making them less suitable for this specific classification task. Therefore, I recommend using the EasyEnsembleClassifier model for this dataset.

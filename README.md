# Module_17-Credit_Risk_Analysis

# Overview
The purpose of this anaylsis was to apply machine learning to a real world challenge: credit card risk. Because credit card risk is inherently unbalanced in terms of classifications (there are far more valid and secure loans than there are risky or fradulenet loans), multiple techniques are applied including Oversampling, Undersampling, and methods that reduce bias like Random Forest. The performance of these various techniques of machine learning will help evaluate credit risk.

# Results
![Screenshot (187)](https://user-images.githubusercontent.com/91569387/152911184-643df570-1f24-4299-94c1-3853aa9369ad.png)
## RandomOverSampler
- The balanced accuracy score for the RandomOverSampler is 0.637
- The Precision for the RandomOverSampler is 0.99
- The Recall for RandomOverSampler is 0.65
## SMOTE
- The balanced accuracy score for SMOTE is 0.630
- The Precision for SMOTE is 0.99
- The Recall for SMOTE is 0.64
## Cluster Centroids
- The balanced accuracy score for ClusterCentroids is 0.510
- The Precision for ClusterCentroids is 0.99
- The Recall for ClusterCentroids is 0.57
## SMOTEENN
- The balanced accuracy score for SMOTEENN is 0.638
- The Precision for SMOTEENN is 0.99
- The Recall for SMOTEENN is 0.57
## BalancedRandomForestClassifier
- The balanced accuracy score for the BalancedRandomForestClassifier is 0.788
- The Precision for BalancedRandomForestClassifier is 0.99
- The Recall for BalancedRandomForestClassifier is 0.91
## EasyEnsembleClassifier
- The balanced accuracy score for the EasyEnsembleClassifier is 0.925
- The Precision for EasyEnsembleClassifier is 0.99
- The Recall for EasyEnsembleClassifier is 0.94


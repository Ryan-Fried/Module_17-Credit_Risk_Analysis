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

# Summary
The best performing models are the BalancedRandomForestClassifier and the EasyEnsembleClassifier, which makes sense, given these two models use ensemble learning, combining multiple algorithms to refine the prediction. EasyEnsembleClassifier had the highest balanced accuracy score at 0.925 and a recall of 0.94, with BalancedRandomForestClassifier coming in with the second best scores in these two categories. The lowest overall performer was the Cluster Centroid model, with a 0.51 balanced accuracy score and a recall of 0.57, only slightly better than completely random chance. The precision did not differ significantly between any of the methods, with all averageing 0.99. Of any of these models, EasyEnsembleClassifier would be the recommendation, followed by BalancedRandomForestClassifier.

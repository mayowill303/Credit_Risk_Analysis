# Credit_Risk_Analysis
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, I’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## Deliverable 1: Use Resampling Models to Predict Credit Risk
### An accuracy score for the model is calculated
![Resampling_Accuracy_Score](https://user-images.githubusercontent.com/96395120/163513732-32d6fa95-e493-4657-a681-ec0e9b3afb39.png)
### A confusion matrix has been generated
![Resampling_Confusion_Matrix](https://user-images.githubusercontent.com/96395120/163513801-d330a02e-f329-400e-b26d-7bbb0b21df7a.png)
### An imbalanced classification report has been generated
![Resampling_Imbalanced_Classification_Report](https://user-images.githubusercontent.com/96395120/163513842-f5cb29b2-7650-40aa-8798-dc1ea5290b1f.png)

## Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
### SMOTEENN 
#### An accuracy score for the model is calculated
![SMOTEENN_Accuracy_Score](https://user-images.githubusercontent.com/96395120/163513966-1d815e3e-346b-4b14-bb15-28f6df154de2.png)
#### A confusion matrix has been generated
![SMOTEENN_Confusion_Matrix](https://user-images.githubusercontent.com/96395120/163514005-75002570-d654-46f3-8773-8330f0636b85.png)
#### An imbalanced classification report has been generated
![SMOTEENN_Imbalanced_Classification_Report](https://user-images.githubusercontent.com/96395120/163514060-77ecab48-a1b9-4f6f-bffc-d42e6b2dc095.png)

## Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
### BalancedRandomForestClassifier
#### An accuracy score for the model is calculated (2.5 pt)
![BalancedRandomForestClassifier_Accuracy_Score](https://user-images.githubusercontent.com/96395120/163515226-5afc2d2d-5388-4961-9f8f-acd543359636.png)
#### A confusion matrix has been generated (2.5 pt)
![BalancedRandomForestClassifier_Confusion_Matrix](https://user-images.githubusercontent.com/96395120/163515267-a664dea1-de1b-489d-8e03-177d5f9f9cdc.png)
#### An imbalanced classification report has been generated (5 pt)
![BalancedRandomForestClassifier_Imbalanced_Classification_Report](https://user-images.githubusercontent.com/96395120/163515310-9416de27-0885-4cfe-9a59-1441ff38e4bd.png)
#### The features are sorted in descending order by feature importance (5 pt)
![BalancedRandomForestClassifier_Sorted_Desc_Order](https://user-images.githubusercontent.com/96395120/163515370-09477399-11ed-422a-8746-2bf8f0344b63.png)

### EasyEnsembleClassifier
#### An accuracy score of the model is calculated
![EasyEnsembleClassifier_Accuracy_Score](https://user-images.githubusercontent.com/96395120/163515425-e8dfb71a-a9fd-4032-8039-3352a8e3d565.png)
#### A confusion matrix has been generated
![EasyEnsembleClassifier_Confusion_Matrix](https://user-images.githubusercontent.com/96395120/163515471-4da381d6-1865-46cc-bfd6-397a521442bd.png)
#### An imbalanced classification report has been generated
![EasyEnsembleClassifier_Imbalanced_Classification_Report](https://user-images.githubusercontent.com/96395120/163515547-ec01be6f-0b45-455e-9a8b-e92689fac058.png)

## Deliverable 4: A Written Report on the Credit Risk Analysis
### Overview of the Analysis 
The purpose of this analysis is to use Python to build and evaluate machine learning models to predict credit risk.  After review and testing, make a written recommendation on whether they should be used to predict credit risk.

### Results
- Describe the balanced accuracy scores
- The precision and recall scores of all six machine learning models
- Use screenshots of your outputs to support your results

### Summary
- Summarize the results of the machine learning models
- Recommendation on the model to use
- If you do not recommend any of the models, justify reasoning.

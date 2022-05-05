# Credit_Risk_Analysis

## Overview

Fast Lending, a peer-to-peer lending services company wants to use machine learning to predict credit risk. Management believes that this will provide a quicker and more reliable loan experience. It also believes that machine learning will lead to a more accurate identification of good candidates for loans which will lead to lower default rates. 

The following are the deliverables, in this project: 

-	Deliverable 1: Use Resampling Models to Predict Credit Risk
-	Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
-	Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk


## Results

### Deliverable 1: Use Resampling Models to Predict Credit Risk

For all three algorithms, the following have been completed:

•	An accuracy score for the model is calculated 

•	A confusion matrix has been generated

•	An imbalanced classification report has been generated

#### Oversampling

Naive Random Oversampling

![deliv1-Oversampling_NRO.png](https://github.com/OPahunang/Credit_Risk_Analysis/blob/main/resources/deliv1-Oversampling_NRO.png)


SMOTE Oversampling

![deliv1-Oversampling_SMOTE.png](https://github.com/OPahunang/Credit_Risk_Analysis/blob/main/resources/deliv1-Oversampling_SMOTE.png)


#### Undersampling

![deliv1-Undersampling.png](https://github.com/OPahunang/Credit_Risk_Analysis/blob/main/resources/deliv1-Undersampling.png)



### Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk

The combinatorial SMOTEENN algorithm does the following:

•	An accuracy score for the model is calculated 

•	A confusion matrix has been generated 

•	An imbalanced classification report has been generated 


#### Combination (Over and Under) Sampling

![deliv2-Combi.png](https://github.com/OPahunang/Credit_Risk_Analysis/blob/main/resources/deliv2-Combi.png)


### Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

The BalancedRandomForestClassifier algorithm does the following:

•	An accuracy score for the model is calculated 

•	A confusion matrix has been generated 

•	An imbalanced classification report has been generated 


#### Balanced Random Forest Classifier

![deliv3-brfc.png](https://github.com/OPahunang/Credit_Risk_Analysis/blob/main/resources/deliv3-brfc.png)


•	The features are sorted in descending order by feature importance 

![deliv3-brfc_features.png](https://github.com/OPahunang/Credit_Risk_Analysis/blob/main/resources/deliv3-brfc_features.png)



The EasyEnsembleClassifier algorithm does the following:

•	An accuracy score of the model is calculated 

•	A confusion matrix has been generated 

•	An imbalanced classification report has been generated 


#### Easy Ensemble AdaBoost Classifier

![deliv3-eec.png](https://github.com/OPahunang/Credit_Risk_Analysis/blob/main/resources/deliv3-eec.png)


## Summary

Of all the models presented, Easy Ensemble AdaBoost Classifier provided with the highest accuracy of .925.


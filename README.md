# Credit Risk Analysis

## Overview

### Purpose
The purpose of this analysis is to use the credit card dataset from LendingClub to make a recommendation of whether or not the models should be used to assess credit risk. The analysis will be done using RandomOverSampler, SMOTE, ClusterCentroids as well as the SMOTEENN algorithm, as well as the BalancedRandomForestClassifier and EasyEnsembleClassifier to predict credit risk.

## Analysis

###  Random Oversampler

The balanced accuracy score is 0.657. That means from all predictions (both true/false positive and true/false negative), we have predicted 65.7% of them correctly.
From the imbalanced classification report, we can see the precision is a total of 0.99 and recall of 0.87.
With the precision at 0.99 percent, it means from the true positive and false positives, 99% are actually true positive.
With the recall at 0.87, it means that 87% of the true positives out of the true positives and false negatives were predicted correctly.

![image](https://user-images.githubusercontent.com/108503112/212449359-c2c5959a-c581-4a37-91b0-a21145ae77a8.png)


### SMOTE Oversampler

The balanced accuracy score is 0.653. That means from all predictions (both true/false positive and true/false negative), we have predicted 65.3% of them correctly.
From the imbalanced classification report, we can see the precision is a total of 0.99 and recall of 0.69.
With the precision at 0.99 percent, it means from the true positive and false positives, 99% are actually true positive.
With the recall at 0.69, it means that 69% of the true positives out of the true positives and false negatives were predicted correctly.

![image](https://user-images.githubusercontent.com/108503112/212449344-edd2933a-a684-4d7d-bfe0-2ba92f160f7b.png)


### Undersampling

The balanced accuracy score is 0.545. That means from all predictions ((both true/false positive and true/false negative), we have predicted 54.5% of them correctly.
From the imbalanced classification report, we can see the precision is a total of 0.99 and recall of 0.40.
With the precision at 0.99 percent, it means from the true positive and false positives, 99% are actually true positive.
With the recall at 0.40 it means that 40% of the true positives out of the true positives and false negatives were predicted correctly.

![image](https://user-images.githubusercontent.com/108503112/212449326-e14439fc-c6c0-4aad-a8e5-cf2a67db903e.png)


### SMOTEENN Sampling

The balanced accuracy score is 0.545. That means from all predictions ((both true/false positive and true/false negative), we have predicted 54.5% of them correctly.
From the imbalanced classification report, we can see the precision is a total of 0.99 and recall of 0.40.
With the precision at 0.99 percent, it means from the true positive and false positives, 99% are actually true positive.
With the recall at 0.40 it means that 40% of the true positives out of the true positives and false negatives were predicted correctly.

![image](https://user-images.githubusercontent.com/108503112/212485520-c25e28e0-efe2-4c68-be4f-d5e88349fd1f.png)


## Ensemble Learners

### Balanced Random Forest Classifier

The balanced accuracy score is 0.788. That means from all predictions (both true/false positive and true/false negative), we have predicted 78.8% of them correctly.
From the imbalanced classification report, we can see the precision is a total of 0.99 and recall of 0.87.
With the precision at 0.99 percent, it means from the true positive and false positives, 99% are actually true positive.
With the recall at 0.87 it means that 87% of the true positives out of the true positives and false negatives were predicted correctly.

![image](https://user-images.githubusercontent.com/108503112/212450069-c74602f3-e05c-4271-aae0-d1fbfd17c603.png)

### Easy Ensemble AdaBoost Classifier

The balanced accuracy score is 0.932. That means from all predictions (both true/false positive and true/false negative), we have predicted 93.2% of them correctly.
From the imbalanced classification report, we can see the precision is a total of 0.99 and recall of 0.94.
With the precision at 0.99 percent, it means from the true positive and false positives, 99% are actually true positive.
With the recall at 0.94 it means that 94% of the true positives out of the true positives and false negatives were predicted correctly.

![image](https://user-images.githubusercontent.com/108503112/212450445-a3218dbb-ed83-458a-8a2c-10e9ac8bce2e.png)


## Summary
I would recommend using the Ensemble method with the Easy Ensemble AdaBoost Classifier because the results show that out of all the methods above, it has the highest accuracy score of 0.932, which means from all the predictions of true positive, false positive, true negative and false negative, we have predicted 93.2% of them correctly. It also has the highest recall score of 94% of all the methods above.

# Credit Risk Analysis

## Overview
### Purpose
The purpose of this analysis is to make a recommendation of whether or not the models should be used to assess credit risk.

## Analysis

###  Random Oversampler

The balanced accuracy score is 65.7%.
From the imbalanced classification report, we can see the precision is a total of 0.99 and recall of 0.87.

![image](https://user-images.githubusercontent.com/108503112/212449359-c2c5959a-c581-4a37-91b0-a21145ae77a8.png)


### SMOTE Oversampler

The balanced accuracy score is 65.3%.
From the imbalanced classification report, we can see the precision is a total of 0.99 and recall of 0.69.

![image](https://user-images.githubusercontent.com/108503112/212449344-edd2933a-a684-4d7d-bfe0-2ba92f160f7b.png)


### Undersampling

The balanced accuracy score is 54.5%.
From the imbalanced classification report, we can see the precision is a total of 0.99 and recall of 0.40.

![image](https://user-images.githubusercontent.com/108503112/212449326-e14439fc-c6c0-4aad-a8e5-cf2a67db903e.png)


### SMOTEENN Sampling


![image](https://user-images.githubusercontent.com/108503112/212485520-c25e28e0-efe2-4c68-be4f-d5e88349fd1f.png)


## Ensemble Learners

### Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/108503112/212450069-c74602f3-e05c-4271-aae0-d1fbfd17c603.png)

### Easy Ensemble AdaBoost Classifier
![image](https://user-images.githubusercontent.com/108503112/212450445-a3218dbb-ed83-458a-8a2c-10e9ac8bce2e.png)


## Summary
I would recommend using the Easy Ensemble AdaBoost Classifier because it has the highest accuracy score.

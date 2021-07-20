![image](https://user-images.githubusercontent.com/78892035/126404042-d4e4afa9-aab6-4c6c-8291-40a2a026dcd9.png)


# Credit_Risk_Analysis

## Overview

Employ various techniques including oversampling, undersampling, combination, and classifiers to determine the best models for predicting risky loans.

Tools/Resources:
-	Jupyter Notebook imbalanced-learn and scikit-learn
-	RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier, EasyEnsembleClassifier
-	Credit dataset from LendingClub

## Results

### Naive Random Oversampling

![image](https://user-images.githubusercontent.com/78892035/124388603-94e09380-dcb1-11eb-8eab-0173627cbe18.png)

- Balanced Accuracy Score: 0.65
- Precision Score High Risk: 0.01
- Precision Score Low Risk: 1.00
- Recall Score High Risk: 0.69
- Recall Score Low Risk: 0.60


### SMOTE Oversampling

![image](https://user-images.githubusercontent.com/78892035/124388627-b6417f80-dcb1-11eb-946d-ad2b32645131.png)

- Balanced Accuracy Score: 0.66
- Precision Score High Risk: 0.01
- Precision Score Low Risk: 1.00
- Recall Score High Risk: 0.63
- Recall Score Low Risk: 0.69


### Undersampling

![image](https://user-images.githubusercontent.com/78892035/124388661-ceb19a00-dcb1-11eb-9bad-730730a074ab.png)

- Balanced Accuracy Score: 0.54
- Precision Score High Risk: 0.01
- Precision Score Low Risk: 1.00
- Recall Score High Risk: 0.69
- Recall Score Low Risk: 0.40


### Combination (Over and Under) Sampling

![image](https://user-images.githubusercontent.com/78892035/124388674-e426c400-dcb1-11eb-9b12-836234b784e8.png)

- Balanced Accuracy Score: 0.64
- Precision Score High Risk: 0.01
- Precision Score Low Risk: 1.00
- Recall Score High Risk: 0.72
- Recall Score Low Risk: 0.57


### Balanced Random Forest Classifier

![image](https://user-images.githubusercontent.com/78892035/124388783-5b5c5800-dcb2-11eb-905c-27bb52d668c7.png)

- Balanced Accuracy Score: 0.79
- Precision Score High Risk: 0.04
- Precision Score Low Risk: 1.00
- Recall Score High Risk: 0.67
- Recall Score Low Risk: 0.91


### Easy Ensemble AdaBoost Classifier

![image](https://user-images.githubusercontent.com/78892035/124388911-f48b6e80-dcb2-11eb-9159-d9ffb8f4423a.png)

- Balanced Accuracy Score: 92
- Precision Score High Risk: 0.07
- Precision Score Low Risk: 1.00
- Recall Score High Risk: 0.91
- Recall Score Low Risk: 0.94

## Summary

From the reports, the Undersampling model is the least accurate, yielding low accuracy and recall scores. The Easy Ensemble AdaBoost Classifier is the most accurate model, with the highest accuracy and recall scores of all the models and is the recommended model for determining credit risk for this project. 

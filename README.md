# Credit_Risk_Analysis

## Overview

The purpose of this project is to create a supervised machine learning model to predict credit risk. For this project these 6 different models are used:

1. Naive Random Oversampling
2. SMOTE Oversampling
3. Cluster Centroid Undersampling
4. SMOTEENN Sampling
5. Balanced Random Forest Classifying
6. Easy Ensemble Classifying

## Results

The analysis results of each model is described below.

### Naive Random Oversampling

* Accuracy Score: 67%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 66%
* Recall Low Risk: 68%

![oversampling](https://github.com/carolineshipley/Credit_Risk_Analysis/blob/main/resources/Naive.png)

### SMOTE Oversampling

* Accuracy Score: 69.3%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 72%
* Recall Low Risk: 67%

![SMOTE]((https://github.com/carolineshipley/Credit_Risk_Analysis/blob/main/resources/Smote.png)

### Cluster Centroid Undersampling

* Accuracy Score: 52.2%
* Precision High Risk: 0%
* Precision Low Risk: 100%
* Recall High Risk: 64%
* Recall Low Risk: 41%

![undersampling](https://github.com/carolineshipley/Credit_Risk_Analysis/blob/main/resources/Cluster.png)

### SMOTEENN Sampling

* Accuracy Score: 68%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 76%
* Recall Low Risk: 60%

![SMOTEENN](https://github.com/carolineshipley/Credit_Risk_Analysis/blob/main/resources/Smoteen.png)

### Balanced Random Forest Classifying

* Accuracy Score: 64.8%
* Precision High Risk: 56%
* Precision Low Risk: 100%
* Recall High Risk: 30%
* Recall Low Risk: 100%

![random_forest](https://github.com/carolineshipley/Credit_Risk_Analysis/blob/main/resources/Forest.png)

### Easy Ensemble Classifying

* Accuracy Score: 92.3%
* Precision High Risk: 6%
* Precision Low Risk: 100%
* Recall High Risk: 91%
* Recall Low Risk: 94%

![easy_ensemble](https://github.com/carolineshipley/Credit_Risk_Analysis/blob/main/resources/Easy.png)

## Summary

To be able to detect if a loan is high risk or not, the model needs to allow the least amount of high risk loans pass through undetected. The statistic used for this is the recall rate for high risk. 

Analyzing the results of the different models, the ones that scored the highest were Easy Ensemble Classifying (91%), SMOTEENN Sampling (76%) and SMOTE Oversampling (72%).

Another important statistic is recall rate for low risk because it shows how many low risk loans are flagged as high risk. 

Analyzing the results of the different models, the ones that scored the highest were Balanced Random Forest Classifying (100%) and Easy Ensemble Classifying (94%).

Analyzing the accurary score to see the models overall performance, we can see that the models with the highest accuracy scores were Easy Ensemble Classify (92.3%), SMOTE Oversampling (69.3%) and SMOTEENN Sampling (68%).

After analyzing these three main statistics, the model that recommended to predict high risk loans is the Easy Ensemble Classifying model.

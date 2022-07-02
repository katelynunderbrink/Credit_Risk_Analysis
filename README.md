# Credit_Risk_Analysis

## Overview of Analysis

The purpose of this assignment is to use machine learning techniques to train and evaluate models for credit risk. Using credit card dataset from LendingClub, I oversampled the data, under sampled the data, and compared machine learning models to reduce bias. I will use these data samples to predict credit risk and made a written recommendation on whether they should be used to predict credit risk. 


## Machine Learning Models Results

- Naive Random Oversampling
	- Balanced Accuracy Score: 65 %
	- Precision High Risk Score: 1%
	- Precision Low Risk Score: 100%
	- Recall High Risk Score: 61%
	- Recall Low Risk Score: 68%


- SMOTE Oversampling
	- Balanced Accuracy Score: 62%
	- Precision High Risk Score: 1%
	- Precision Low Risk Score: 100%
	- Recall High Risk Score: 61%
	- Recall Low Risk Score: 64%

- Cluster Centroid Undersampling
	- Balanced Accuracy Score: 53%
	- Precision High Risk Score: 1%
	- Precision Low Risk Score: 100%
	- Recall High Risk Score: 61%
	- Recall Low Risk Score: 45%


- SMOTEENN Sampling
	- Balanced Accuracy Score: 62%
	- Precision High Risk Score: 1%
	- Precision Low Risk Score: 100%
	- Recall High Risk Score: 69%
	- Recall Low Risk Score: 54%


- Balanced Random Forest Classifying
	- Balanced Accuracy Score: 67%
	- Precision High Risk Score: 73%
	- Precision Low Risk Score: 100%
	- Recall High Risk Score: 34%
	- Recall Low Risk Score: 100%


- Easy Ensemble Classifying
	- Balanced Accuracy Score: 93%
	- Precision High Risk Score: 7%
	- Precision Low Risk Score: 100%
	- Recall High Risk Score: 94%
	- Recall Low Risk Score: 91%

## Summary

Using the Recall High Risk Score to find a model that lets the least amount of high risk loans come through undetected, the Easy Ensemble model has the highest score at 94% making it the best model for this type of detection. The easy ensemble model also has a high score of 91% in recall for low risk, meaning that less low risk loans will be flagged as high risk. The model with the highest balanced accuracy score is also the Easy Ensemble Classifying model. Due to these factors, it is best to use the Easy Ensemble Model to predict credit risk. 
 
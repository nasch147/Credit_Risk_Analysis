# Credit_Risk_Analysis

## Overview
The goal of the analysis is to utilize unsupervised machine learning tools to help predict credit risk for a peer-to-peer lending service. Our goal is to use over 80 explanatory varaibles to predict the risk of a loan as either "high risk" or "low risk" through a logistic regression model. This choice of functional form is appropriate as our dependent variable is binary in nature and logistical functions are asymptotic at y=0 and y=1.  Tools used in the analysis come from the scikit-learn and imbalanced-learn libraries. Null and incomplete data was removed from the set and different variables were reclassified so that they could be employed in a machine learning model. Given that the number of observations between 'high risk' and 'low risk' was significantly imbalanced, We employed various sampling techiques to rebalance the data to be used in the machine learning algorithms. Types of sampling included random over sampling, SMOTE algorithm, clustered centroids, comination over and under sampling using the SMOTEEN algorithm, and ensemble classicication methods such as random forrest and AdaBoost. 

## Results



### Random Oversampling



### SMOTE Oversampling



### Undersampling



### Combination sampling



### Random Forrest



### AdaBoost


## Summary




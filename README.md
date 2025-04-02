# Diabetes-Health-Indicators-Study-ML
This is a brief study on diabetes health indicators through Machine Learning techniques. It includes data preprocessing and
handle of class imbalance, feature selection methods and hyperparameter tuning.

## Dataset
The dataset of health indicators for diabetes contains health care statistics and survey information
on the lifestyle of individuals in general, along with their diabetes diagnosis. 

https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators

## Classifiers Explored
- Logistic Regression 
- Random Forest 
- Bagging 
- Gradient Boosting 
- K-Nearest Neighbors

## Feature Selection Algorithms Explored
- Random Forest
- Recursive Feature Elimination (RFE)

## Evaluation of classifiers
To compare classifiers and feature selection methods, the Area Under the ROC Curve (AUC) score was used.
Hyperparameter tuning was also used to maximize the AUC score obtained with some classifiers.
 
## Final Prediction System
The best classifier in terms of processing time and AUC score was selected as the final prediction system. The classifier selected was the Random Forest Classifier (after RFE and hyperparameter tuning).

## In-Depth Report
A detailed report in PDF is available to understand the comparison of the methods used and the selection of the final predictive model. Summaries of the data are in table format for easy comparison.

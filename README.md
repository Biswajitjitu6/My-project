# Rainfall-Prediction 

A project on predicting whether it will rain tomorrow or not by using the Rainfall in Australia dataset. Using catboost, xgboost, random forest, support vector classifier, etc I tried to obtain the best model giving the best accuracy. Out of these models, catboost performed very well giving an AUC score around a ROC score of 89 far better than others.

## Workflow
### 1.Data Collection:
Rainfall Prediction in Australia dataset from Kaggle
link: https://rainy-brain.herokuapp.com/

### 2.Data Preprocessing:
•	Missing Values Handled by Random Sample imputation to maintain the variance

•	Categorical Values like location, wind direction are handled by using Target guided encoding

•	Outliers are handled using IQR and boxplot

•	Feature Selection and was done

•	Feature Scaling didnt give a lot of difference

•	Imbalanced Dataset was handled using SMOTE

### 3.Model Creation:

•	Different types of models were tried like catboost, random forest, logistic regression, xgboost, support vector machines, knn, naive bayes.

•	Out of these catboost, random forest and XGB classifier were top 3

•	The conclusion were made using classification metrics. roc curve and auc score


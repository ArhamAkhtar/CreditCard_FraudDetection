# CreditCard_FraudDetection
**Introduction:** 

* The dataset contains transactions made by credit cards in September 2013 by European cardholders.
* This dataset presents transactions that occurred in two days, where we have 492 frauds out of 257,456 transactions. 
* The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
* It contains only numerical input variables which are the result of a PCA transformation. Unfortunately(due to confidentiality issues).
*  Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. 
*  Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. 
*  The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning.
*   Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
**Problem Statement:**
* Here our task is to make a model which identifies or predicts whether a given credit card transaction is fraudulent or not by feeding attribute values to a model.

**Strategies used:**
* Dataset:
  - 257,456 instances with 30 features
  - Output- 0/1 (legitimate/illegitimate transaction resp.)
 

* Problem type:
  - Supervised Problem: The problem in which we are given a dataset which has target/dependent/labelled variable.Here we know for what we are building the model
  - Classification Problem: The problem where dataset contains categorical target variable.
  - Binary classification problem: The problem where dataset contains categorical target, where categories are 2.
* Logistic Regression Implementation:
  - Models the probability of a discrete outcome given an input variable. 
             Uses a logistic function defined below to model a binary output variable.
             Logistic regression uses a loss function referred to as “maximum likelihood estimation (MLE)” which is a conditional probability. If the probability is greater than 0.5, the predictions will be classified as class 0. Otherwise, class 1 will be assigned.
             Range of logistic regression is bounded between 0 and 1
* Result: 
  - Precision is 1
  - Recall is 1

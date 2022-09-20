# Customer-Churn

![customerchurn](https://user-images.githubusercontent.com/104231685/190941964-1a375203-c28b-49fa-b2b1-e33b54ba1cc9.jpg)


Predicting How Many Customers Churn at IBM

By: Alexandria R.

# PROJECT OBJECTIVE
This project takes a customer churn dataset on IBMS customers and uses classification machine learning algothrims to predict how many customer churn. There is 
a single y target variable "churn" (I am predicting one column attribute in the dataset churn.) 

# PROJECT VALUE
The results of the machine learning models and analysis of all relevant customer data can develop focused customer retention programs for IBM.

# Download the dataset here: 
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

# About Dataset
This datasets focus is to predict behavior to retain customers from IBM. (IBM Sample Data Sets)


# Supervised Classification Models Used
#### 1.) KNeighborsClassifier | is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point.(IBM)
#### 2.) SVC Support Vector Classifier | The objective of the support vector machine algorithm is to find a hyperplane in an N-dimensional space(N — the number of features) that distinctly classifies the data points.
#### 3.) DecisionTreeClassifier | Decision Trees (DTs) are a non-parametric supervised learning method used for classification and regression. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features. A tree can be seen as a piecewise constant approximation.(Decision Tree Classifier) 
#### 4.) RandomForestClassifier | A random forest is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. The sub-sample size is controlled with the max_samples parameter if bootstrap=True (default), otherwise the whole dataset is used to build each tree. (scikit learn)
#### 5.) LogisticRegression | This type of statistical model (also known as logit model) is often used for classification and predictive analytics. Logistic regression estimates the probability of an event occurring, such as voted or didn’t vote, based on a given dataset of independent variables. Since the outcome is a probability, the dependent variable is bounded between 0 and 1. In logistic regression, a logit transformation is applied on the odds—that is, the probability of success divided by the probability of failure (IBM)
#### 6.) GradientBoostingClassifier | Boosting is an ensemble learning method that combines a set of weak learners into a strong learner to minimize training errors. In boosting, a random sample of data is selected, fitted with a model and then trained sequentially—that is, each model tries to compensate for the weaknesses of its predecessor. With each iteration, the weak rules from each individual classifier are combined to form one, strong prediction rule.  (IBM)

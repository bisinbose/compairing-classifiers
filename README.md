# compairing-classifiers

# Overview: 
In this practical application, the goal is to compare the performance of the classifiers, namely K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines. We will utilize a dataset related to marketing bank products over the telephone.

# Data
Dataset comes from the UCI Machine Learning repository link. The data is from a Portugese banking institution and is a collection of the results of multiple marketing campaigns.The provided dataset contains information on 411K results of marketing campaign and the goal is to help provide features that will help the client a bank improve their efficency of markerting campaigns. This is to done by building an accurate model. The data set had 21 columns of which 10 were numerical and rest categorical.

# Observations
The overall Acceptance rate for a deposit is nearly 89% when evaluating based on the feature set that includes job, marital status, default, education, loan and housing.
The testing of different models showed that the SVC classifier performs the best. Furthermore, the SVM was only performed on a subset of of 5,000 observations since it required tremendous amounts of run time to perform a grid search analysis. To ensure comparative models, I employed Gridsearch to optimize the parameters at hand of each model.

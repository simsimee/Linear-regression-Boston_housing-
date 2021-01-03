## Task : Linear Regression on Boston Housing Dataset

There are 506 samples and 13 feature variables (CRIM, ZN, INDUS, ... B, LSTAT) in this dataset. The objective is to predict the value of prices of the house (MEDV). 

What to do : Train and test the dataset (the ratio of train data vs. test data is up to you. e.g. 7:3, 8:2, etc.) and get MSE (Mean Squared Error), under the three different conditions, say (1) Using all 13 features, (2) Using 5 to 8 features by excluding some features which are strongly correlated to other features, i.e. their correlation coefficient is greater than 0.6. For example, the correlation coefficient between INDUS and NOX is 0.76, and then you may exclude either INDUS or NOX. (3) Using the 2 most important features 

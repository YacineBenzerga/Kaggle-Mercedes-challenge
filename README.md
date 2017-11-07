# Kaggle-Mercedes-challenge
https://www.kaggle.com/c/mercedes-benz-greener-manufacturing

This is a baseline approach to the Mercedes Challenge on Kaggle

The challenge consist on cutting the time that Mercedes-Benz manufacturing spends on the test bench
by removing non relevant features 

the approach used here is based on :

* Penalized regression (Lasso) to reduce the data dimension from 579 to 92 features
* 10fold Cross validation on reduced input using linear/non linear regression models scored on R square metric
* Hyperparameter Tuning through GridSearchCV on XGBoost Regressor(sklearn)

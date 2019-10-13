# Vectorized Logistic Regression
A beginner's attempt to vectorize logistic regression in python inspired from Courera's Machine Learning by Andrew NG. The initial commit is an unregularized logistic regression. Regularization modification will be done in commits to follow. 

The intent has been to vectorize most of the operartions in a logistic regression algorithm using numpy and pandas, from calculating the cost to solving for the parameters using graient descent to getting the output predictions.

The performance of the model has been measured using metrics such as roc_auc_score, f-1 score and accuracy score. The model performance has also been compared with scikit learn's implementation of logistic regression.

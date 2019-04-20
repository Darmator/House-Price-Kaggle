# House-Price-Kaggle
Entry for the Hose price prediction competition from kaggle 0.12440 score

It uses 7 Keras Dense neural networks with the following architechture:

Input->128 relu-> 256 relu -> 256 relu -> 1 Linear

and 3 sklearn classifiers:

Ridge(alpha = 10)
Lasso(alpha = 10)
KNeighborsRegressor(n_neighbors=10)

It uses the mean of all their predictions

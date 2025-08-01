### Football-ML

This repository contains code that tries to use machine learning to predict the outcome of football matches.
Initially we predict the scores themselves, then also only who wins the game. 
The accuracy of who wins based on predicted scores is about 60%, 
while predicting the winner directly gives an accuracy of about 68%.

Applied methods in this script are: machine learning using xgboost and tensorflow, preprocessing (one-hot encoding and feature engineering), dataframe slicing, hyperparameter optimisation with GridSearchCV.

The used dataset can be found at: 
https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017

# A.I.-ML-Project-2021
Project for the Course Machine Learning in MSc A.I.

This is work in progress

The Dataset consists of 5000 movies from https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv

The goal is to predict the revenue a movie will produce based on budget, number of votes and average votes rating.
Since it is a Regression problem, there are used the sklearn libraries Lasso, svm.SVR(kernel = 'rbf'), RandomForestRegressor and DecisionTreeRegressor

The metric used evaluate the results of the regressor is the mean absolute error.

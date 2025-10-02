**🚀 Project Overview**

This project applies machine learning algorithms to predict IMDb-style movie ratings. The pipeline covers:
Data cleaning and preprocessing
Feature extraction (genres, actors, budgets, etc.)
Model training with regression algorithms
Evaluation of performance with RMSE, MAE, and R² score
Final prediction on unseen movies

**📊 Dataset**
You can use:
IMDb dataset
TMDB 5000 Movie Dataset
Or any custom dataset containing columns like:
title, genre, director, actors, budget, revenue, runtime, rating
Place dataset file inside the data/ folder (e.g., data/movies.csv).

**🧠 Modeling Approach**

**Data Preprocessing**
Handle missing values (budget, revenue, etc.)
Convert categorical features (genre, director, actors) with one-hot or embeddings
Normalize numerical features (budget, runtime)

**Feature Engineering**
Number of genres per movie
Popularity scores of actors/directors
Budget-to-revenue ratio
Year-based release features

**Model Training**
Baseline: Linear Regression
Advanced: RandomForestRegressor, XGBoost, Gradient Boosting
Hyperparameter tuning with GridSearchCV / RandomizedSearchCV

**Evaluation**
RMSE (Root Mean Squared Error)
MAE (Mean Absolute Error)
R² Score

**Install Required Libraries**
pip install pandas
pip install numpy
pip install scikit-learn
pip install xgboost
pip install joblib
pip install flask
pip install matplotlib
pip install seaborn
pip install jupyter


**Dataset Path**
https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies

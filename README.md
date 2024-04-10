S&P 500 Stock Analysis Project README
Project Overview
This repository contains code and documentation for a machine learning project focused on forecasting S&P 500 stock prices. The project involves data collection, preprocessing, model building, and analysis using Python and various machine learning algorithms.

Data Sources
The project utilizes historical stock data from Yahoo Finance (yFinance) for 30 companies within the S&P 500 index. Data includes daily stock values spanning approximately four years, covering key financial metrics like Open, High, Low, Close, Adjusted Close, Volume, and Symbol.

Data Preprocessing
Data preprocessing involves cleaning, handling missing values, and formatting data for analysis. Steps include replacing null values, standardizing features using the standardScaler() function, and pivoting data for exploratory analysis and machine learning implementation.

Machine Learning Models
Linear Regression

Feature Selection: Lasso Regression Model
Metrics: MSE, R-squared, RMSE, Lasso Coefficients
Model Evaluation: Achieved R-squared of 0.9982 and RMSE of 51.41
Random Forest

Feature Selection: Feature Importance
Metrics: MSE, R-squared, RMSE
Hyperparameter Tuning: GridSearchCV
Model Evaluation: R-squared of 0.9999, RMSE of 11.42
Decision Tree

Feature Selection: Same as Random Forest
Metrics: MSE, R-squared, RMSE
Model Evaluation: R-squared of 0.9997, RMSE of 20.42
Exploratory Data Analysis (EDA)
Analyzed Adj Close values over four years (2020-2024), correlation of Adj Close values among sectors, distribution of Adj Close values of S&P, and close value range distribution.
Utilized visualizations including bar charts, correlation matrices, pie charts, and line plots.
Model Comparison
Compared performance, computational efficiency, and applicability of Linear Regression, Random Forest, and Decision Tree algorithms.
Identified Random Forest as the top performer with the lowest RMSE and highest R-squared score.
Conclusion and Recommendations
Recommended using Random Forest for superior predictive performance unless computational resources are limited, in which case Linear Regression or a tuned Decision Tree could be considered.
Provided contact information for further inquiries or collaboration.
For detailed implementation and analysis, refer to the code files and Jupyter Notebooks in this repository.


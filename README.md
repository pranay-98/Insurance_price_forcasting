# Insurance_price_prediction
build a machine learning model that helps establish the rates by predicting the charges or payouts done by the health insurance firm to maintain profitability.

## Introduction

The insurance industry is constantly evolving and insurance pricing is a critical aspect that affects both the insurance companies and the customers. This project aims to develop a machine learning model to predict insurance pricing based on historical data. The goal is to provide insurance companies with accurate pricing forecasts, allowing them to make informed business decisions and providing customers with fair and competitive pricing. Hence, our goal is to build a machine learning model that helps establish the rates by predicting the charges or payouts done by the health insurance firm to maintain profitability.

## Data

The data used in this project is a real-world insurance pricing dataset that includes various demographic and policy holder information. The data was cleaned and pre-processed to ensure its quality and suitability for the analysis.

## Methodology
The following steps were taken in order to build the model:

* Exploratory Data Analysis: Performed Exploratory Data Analysis (EDA) on categorical and continuous data to understand the variables and relationships between them. The EDA was conducted using various visualization techniques such as histograms, scatter plots, and bar charts.

* Univariate and Bivariate Analysis: Conducted univariate analysis to understand each variable individually and bivariate analysis to understand the relationships between variables. The univariate analysis was conducted using descriptive statistics and the bivariate analysis was conducted using scatter plots and correlation matrices.

* Correlation Analysis: Conducted a correlation analysis to understand the strength and direction of the relationship between variables. This was done using Pearson's correlation coefficient and visualized using a heatmap.

* Categorical Correlation: Used the Chi-squared test to understand the relationship between categorical variables. This was done to identify variables that are significant in explaining the target variable.

* ANOVA: Conducted ANOVA analysis to understand the relationship between categorical variables and the target variable. This was done to identify the significant variables that affect the target variable.

* Label Encoding: Used label encoding to convert categorical variables into numerical variables. This was done to prepare the data for the machine learning models.

* Linear Regression: Implemented linear regression to build a baseline model and validate its assumptions. The assumptions of linear regression were checked and if necessary, transformed to meet the assumptions.

* XGBoost Regressor: Implemented XGBoost regressor to improve the model's performance. XGBoost is a powerful machine learning algorithm that is known for its speed and accuracy.

* Pipeline and Hyperparameter Optimization: Built pipelines using Sklearn's Pipeline operator and performed hyperparameter optimization using BayesSearchCV. The pipelines were used to simplify the process of training and testing the models and the hyperparameter optimization was used to find the best set of hyperparameters for the XGBoost regressor.

* Model Evaluation: Evaluated the models using regression metrics such as RMSE. This was done to compare the performance of the linear regression and XGBoost models and select the best model.

## Results

The results of the project show that the XGBoost regressor outperforms the linear regression model in terms of accuracy and RMSE. The XGBoost model has a lower RMSE and a higher accuracy, making it the best model for the insurance pricing prediction problem.


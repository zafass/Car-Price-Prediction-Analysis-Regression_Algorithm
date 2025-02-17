# Car Price Prediction Analysis

## Project Overview

This project aims to help a Chinese automobile company entering the US market understand the factors influencing car prices. By analyzing a dataset of car features and prices, the goal is to develop accurate predictive models and identify key variables affecting car pricing. The insights from this analysis will support strategic decisions in car design, pricing, and market positioning.

## Dataset
* Source: Dataset of car specifications and pricing details across the American market.
* Features: 26 columns, including car specifications (e.g., enginesize, horsepower, curbweight) and the target variable (price).
* Target Variable: price (car price in USD).
  
## Objectives
* Identify the significant variables affecting car prices.
* Build and compare regression models to predict car prices.
* Evaluate model performance using metrics like R-squared, MAE, and RMSE.
  
## Data Preprocessing:
* Handled missing values and cleaned the data.
* Encoded categorical variables and scaled numerical features.
  
### Regression Models Implemented:
* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* Support Vector Regressor (SVR)
  
### Model Evaluation:
* Compared models based on R-squared, MAE, and RMSE.
* Selected the best-performing model for prediction.

### Feature Importance:
* Identified the most critical variables affecting car prices (e.g., curbweight, enginesize, horsepower).
  
### Hyperparameter Tuning:
* Fine-tuned the best model to achieve maximum performance.
  
Key Findings
* Significant Variables: The top factors influencing car prices are curbweight, enginesize, horsepower, carwidth, and fuel efficiency (e.g., highwaympg).
Best Model:
* Gradient Boosting Regressor emerged as the best model with the highest accuracy (R2 = 0.9677).

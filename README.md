# Insurance Premium Prediction

This project aims to predict the insurance premium amount based on a given dataset of customer information. Using machine learning techniques, we model the relationship between various input features (such as age, BMI, smoking habits, etc.) and the target variable (insurance premiums).

## Introduction 

Insurance companies calculate premium amounts based on various factors such as the age, gender, smoking habits, region and BMI of individuals. This project leverages machine learning algorithms to predict insurance premiums based on these factors, providing insights into how each feature impacts the final cost.

The goal of the project is to develop a model that can accurately predict insurance premiums using historical data, allowing insurance companies to assess premiums more effectively.

## Dataset

The [dataset](https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset) used for this project contains the following columns:

- Age: Age of the customer
- Sex: Gender of the customer
- BMI: Body mass index
- Children: Number of children or dependents
- Smoker: Whether the customer smokes or not
- Region: The region the customer belongs to
- Expenses: The insurance premium charged (target variable)

## Project Workflow

The project follows these steps:

- Data Preprocessing: Handling missing data, encoding categorical variables, and feature scaling.
- Exploratory Data Analysis (EDA): Visualizing relationships between the features and the target variable.
- Model Selection: Using various machine learning models to predict the insurance premium.
- Model Evaluation: Comparing the performance of models using different metrics such as MSE, RMSE, and R² score.

 ## Models Used

Several regression models were used and compared:

- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet
- K-Neighbors Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- AdaBoost Regressor
- SVR
- DecisionTreeRegressor
 

## Performance Evaluation

The models were evaluated based on the following metrics:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

## Results

After training multiple models, the best-performing model was selected based on the evaluation metrics mentioned above. For example, the Gradient Boosting Regressor may have shown the lowest error rates and highest R² score.

Summary of results:

- Best Model: Gradient Boosting Regressor
- RMSE: 4932.329761
- MAE: 2636.011545
- R² Score: 0.847888

Plots can be viwed in the .ipynb file

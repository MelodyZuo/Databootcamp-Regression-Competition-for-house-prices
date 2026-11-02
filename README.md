# Databootcamp-Regression-Competition-for-house-prices

# House Price Prediction

This project was completed for the Data Bootcamp Kaggle competition. Our goal was to predict house sale prices using regression models and compare different approaches to improve prediction accuracy.

## Project Overview

We worked with a dataset containing 1,200 training houses and 260 test houses. We explored the data, handled missing values, and tested several models, including Linear Regression, Polynomial Regression, Ridge Regression, and Random Forest.

We also created additional features based on house size, age, overall quality, and garage spaces. After comparing different models using cross-validation and Kaggle public scores, we selected a Ridge Regression model with `alpha=10`.

**Final Model Kaggle Public RMSE: 27,003.58788**

## Project Files

- **`house_price_model.ipynb`**: Contains the final model code, data preprocessing, feature engineering, cross-validation, and Kaggle submission. It also includes a record of our model development process.
- **`process.ipynb`**: Provides a detailed record of the models we tested, the changes we made, and how we selected our final model.

## Methods

We used Python, Pandas, NumPy, and scikit-learn for data processing and modeling. Our main methods included:

- Missing value imputation and one-hot encoding
- Feature scaling and feature engineering
- Linear Regression and Polynomial Features
- Ridge Regression and Random Forest
- Five-fold cross-validation and RMSE evaluation

We evaluated model performance using Root Mean Squared Error (RMSE), where a lower score indicates better prediction accuracy.

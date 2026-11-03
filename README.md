# Databootcamp-Regression-Competition-for-house-prices
Team members: Melody Zuo and Yihuan Zhang

## Project Overview

We worked with a dataset containing 1,200 training houses and 260 test houses. We explored the data, handled missing values, and tested several models, including Linear Regression, Polynomial Regression, Ridge Regression, and Random Forest.

We also created additional features based on house size, age, overall quality, and garage spaces. After comparing different models using cross-validation and Kaggle public scores, we selected a Ridge Regression model with `alpha=10`.

**Final Model Kaggle Public RMSE: 27,003.58788**

## Project Files

- **`house_price_model.ipynb`**: Contains the final model code, data preprocessing, feature engineering, cross-validation, and Kaggle submission. It also includes a record of our model development process.
- **`process.ipynb`**: Provides a detailed record of the models we tested, the changes we made, and how we selected our final model.

# House Price Prediction 

This project demonstrates a machine learning pipeline for predicting house prices using the XGBoost regression model. The pipeline includes data preprocessing, model training, evaluation, hyperparameter tuning, and result interpretation.

# Features

- Data Loading and Preprocessing:

- Handle missing values and split features/targets.

- Train-test split for model evaluation.

## Visualization:

- Exploratory Data Analysis (EDA) using matplotlib and seaborn.

- Insights into data distribution and relationships.

## XGBoost Model:

-  Train an XGBoost regressor for predicting house prices.

- Evaluate model performance using RMSE.

## Hyperparameter Tuning:

- Use GridSearchCV to optimize model hyperparameters.

## Model Interpretation:

-  Use SHAP values for feature importance and model explanation.

## Model Persistence:

- Save and load trained models using joblib.

# Acknowledgments

[XGBoost Documentation](https://xgboost.readthedocs.io/en/latest/)

[SHAP Documentation
](https://shap.readthedocs.io/en/latest/)


# Prerequisites

Ensure you have Python installed and the necessary libraries. Install dependencies using pip:

```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install xgboost
pip install scikit-learn
pip install shap
pip install joblib

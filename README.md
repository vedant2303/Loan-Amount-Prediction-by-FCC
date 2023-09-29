# Loan-Amount-Prediction-by-FCC

## Overview
This project aims to estimate the approximate capital amount needed to recover losses for financial instruments in any loss event. It calculates the capitalization rate using a formula that involves the predicted capital amount and the proportion of MTM exposure. The project was commissioned by FCC Canada.

## Main Objectives
- **Data Exploration:** We explored the dataset to understand the relationships between variables for training the machine learning models. Data visualization was performed using libraries such as Seaborn and Matplotlib.

- **Data Pre-Processing:** Based on data exploration, we carried out data pre-processing tasks, including handling null values and dropping unnecessary columns.

- **Model Implementation:** Various machine learning models were implemented, including Decision Trees, Random Forest, XGBoost, ExtraTreeClassifier, and Neural Network.

- **Evaluating Results:** We assessed model performance regarding mean absolute error (MAE) and R2 score to identify the best-performing model. The final model was used to predict Capital - EL Tail Risk Contribution on the test dataset, and the results were exported to a CSV file.

## Background
Financial institutions must hold sufficient capital reserves to withstand unlikely but potentially catastrophic loss events in client portfolios. Estimating these loss calculations quickly and accurately is crucial for risk assessment and pricing loans appropriately.

## Data Description
The dataset contains both numerical and categorical variables. Insignificant categorical variables were dropped, and feature engineering was applied to select significant features.

## Model Performance
- Ridge regression yielded considerable accuracy with a lower mean absolute error (MAE).
- Feature engineering improved model training with various algorithms, including decision trees, random forests, gradient boosting, xgboost, and extra trees.
- The random forest model demonstrated the best overall performance.

## Conclusion
This project provides a machine learning-based approach to estimate loss calculations quickly and accurately, assisting financial institutions in risk assessment and loan pricing. The random forest model emerged as the most effective for this task.

For a detailed project walkthrough and code implementation, please refer to the Jupyter Notebook or script files.

Feel free to reach out if you have any questions or need further information.

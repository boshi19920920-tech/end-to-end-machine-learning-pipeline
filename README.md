# End to End Machine Learning Pipeline

## Project Summary

This project demonstrates a complete supervised machine learning workflow, from raw data preparation to model evaluation and interpretation. The goal is to build a reproducible predictive modeling pipeline that reflects practical data science work in healthcare analytics, business analytics, and applied research.

The project includes data cleaning, exploratory data analysis, feature engineering, train and test split, cross validation, logistic regression, random forest, XGBoost, model evaluation, calibration assessment, feature importance, SHAP based interpretation, and visualization.

## Objectives

The main objectives of this project are to:

1. Prepare an analysis ready dataset through data cleaning and preprocessing.
2. Create meaningful features for predictive modeling.
3. Train and compare multiple supervised learning models.
4. Evaluate model performance using AUC, accuracy, precision, recall, and calibration.
5. Interpret model results using feature importance and SHAP values.
6. Communicate findings through clear visualizations and reproducible documentation.

## Workflow

### 1. Data Cleaning

The data cleaning process includes checking missing values, correcting inconsistent records, converting variable types, recoding categorical variables, and preparing an analysis ready dataset.

### 2. Exploratory Data Analysis

Exploratory data analysis is used to understand variable distributions, outcome balance, missingness patterns, and relationships between predictors and the outcome.

### 3. Feature Engineering

Feature engineering includes encoding categorical variables, scaling numerical variables when appropriate, creating derived predictors, and preparing model ready feature matrices.

### 4. Train and Test Split

The dataset is split into training and testing sets. The training set is used for model fitting and cross validation, while the testing set is held out for final evaluation.

### 5. Cross Validation

Cross validation is used to compare candidate models and assess model stability.

### 6. Models

This project compares the following models:

- Logistic Regression
- Random Forest
- XGBoost

Logistic regression is used as an interpretable baseline model. Random forest and XGBoost are used to capture nonlinear relationships and interactions.

### 7. Model Evaluation

Model performance is evaluated using:

- AUC
- Accuracy
- Precision
- Recall
- Confusion Matrix
- Calibration Plot

### 8. Model Interpretation

Model interpretation is conducted using feature importance and SHAP values. The goal is to identify important predictors and explain how they contribute to predictions.

### 9. Visualization

The project includes visualizations for outcome distribution, predictor distributions, ROC curve, confusion matrix, calibration curve, feature importance, and SHAP summary plot.

## Tools

- Python
- pandas
- NumPy
- scikit-learn
- XGBoost
- SHAP
- matplotlib
- Jupyter Notebook

## Skills Demonstrated

- Data cleaning
- Feature engineering
- Exploratory data analysis
- Train and test split
- Cross validation
- Logistic regression
- Random forest
- XGBoost
- AUC, accuracy, precision, recall, and calibration
- SHAP and feature importance
- Data visualization
- Reproducible documentation

## Project Status

This project is currently under development.

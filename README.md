# Rainfall Prediction Model Comparison

This project compares six different machine learning models for predicting rainfall using weather data from Australia. The models compared are:

1. Logistic Regression
2. Decision Tree
3. Neural Network
4. Random Forest
5. LightGBM
6. XGBoost

## Project Overview

The goal of this project is to predict whether it will rain tomorrow based on various weather parameters. We use a dataset containing Australian weather data and compare the performance of different machine learning models on this task.

## Dataset

The dataset used is the 'weatherAUS.csv' file, which contains daily weather observations from numerous Australian weather stations.

## Methodology

1. Data Preprocessing
   - Handling class imbalance through oversampling
   - Imputation of missing values
   - Feature encoding and scaling

2. Feature Selection
   - Using both filter (Chi-Square) and wrapper (Random Forest) methods

3. Model Training and Evaluation
   - Training six different models
   - Evaluating models using metrics such as Accuracy, ROC AUC, and Cohen's Kappa
   - Visualizing model performance and decision boundaries

## Results

The project includes visualizations comparing the performance of all models in terms of:
- Accuracy and execution time
- Area under ROC curve and Cohen's Kappa

## How to Use

1. Clone this repository
2. Ensure you have all required libraries installed (pandas, numpy, sklearn, matplotlib, seaborn, lightgbm, xgboost)
3. Run the Jupyter notebook to see the full analysis and results

## Future Work

- Hyperparameter tuning for each model
- Trying other advanced models or ensemble methods
- Deploying the best performing model as a web application

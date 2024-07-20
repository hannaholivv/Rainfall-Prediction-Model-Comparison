# 🌧️ Rainfall Prediction Model Comparison

This project compares six different machine learning models for predicting rainfall using weather data from Australia. The models compared are:

1. 📊 Logistic Regression
2. 🌳 Decision Tree
3. 🧠 Neural Network
4. 🌲 Random Forest
5. 💡 LightGBM
6. 🚀 XGBoost

## 🔍 Project Overview

The goal of this project is to predict whether it will rain tomorrow based on various weather parameters. We use a dataset containing Australian weather data and compare the performance of different machine learning models on this task.

## 📁 Dataset

The dataset used is the 'weatherAUS.csv' file, which contains daily weather observations from numerous Australian weather stations.

## 🛠️ Methodology

1. 🧹 Data Preprocessing
   - Handling class imbalance through oversampling using SMOTE (Synthetic Minority Over-sampling Technique)
   - Imputation of missing values using mean for numerical features and mode for categorical features
   - Feature encoding: One-hot encoding for categorical variables
   - Feature scaling: StandardScaler for normalizing numerical features

3. 🔮 Feature Selection
   - Chi-Square test for filter method: Selecting top K features based on their relationship with the target variable
   - Random Forest feature importance for wrapper method: Selecting features based on their importance in a Random Forest model

4. 🏋️ Model Training and Evaluation
   - Training six different models using scikit-learn and other libraries
   - Implementing cross-validation to ensure robust model evaluation
   - Evaluating models using metrics such as Accuracy, Precision, Recall, F1-score, ROC AUC, and Cohen's Kappa
   - Visualizing model performance using confusion matrices, ROC curves, and decision boundary plots

## 📊 Results

The project includes visualizations comparing the performance of all models in terms of:
- Accuracy and execution time
- Area under ROC curve and Cohen's Kappa

## 🚀 How to Use

1. Clone this repository
2. Ensure you have all required libraries installed (pandas, numpy, sklearn, matplotlib, seaborn, lightgbm, xgboost)
3. Run the Jupyter notebook to see the full analysis and results

## 🔮 Future Work

- Hyperparameter tuning for each model
- Trying other advanced models or ensemble methods
- Deploying the best performing model as a web application

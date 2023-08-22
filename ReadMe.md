# Telecom Customer Churn Analysis

This Jupyter Notebook explores a telecom customer churn dataset and performs various tasks such as data preprocessing, exploratory data analysis (EDA), predictive modeling using different algorithms, and hyperparameter tuning.

## Overview

The dataset contains information about telecom customers, including various attributes, and the target variable is the "Churn" column, which indicates whether a customer has churned (1) or not (0).

## Contents

1. **Import Libraries and Load Dataset**: In this section, necessary libraries are imported, and the dataset is loaded into a Pandas DataFrame.

2. **Exploratory Data Analysis (EDA)**: EDA involves understanding the dataset by checking its structure, summary statistics, and visualizations. It also includes examining the distribution of the target variable ("Churn") and creating pair plots and count plots for various features.

3. **Data Preprocessing**: This step involves converting categorical variables into numerical using dummy variables, normalizing the data, and preparing it for model training.

4. **Predictive Modeling**: Different predictive models are trained on the preprocessed data. The models used include:
   - Logistic Regression
   - Random Forest
   - Support Vector Machine (SVM)
   - AdaBoost
   - XGBoost

5. **Feature Importance**: Feature importance is visualized to identify which features have the most impact on model predictions.

6. **Hyperparameter Tuning**: Hyperparameter tuning is performed for the Random Forest and XGBoost models using GridSearchCV to find the best parameters.

7. **Model Comparison**: Models are compared based on accuracy scores, training scores, best parameters, and confusion matrices.

## How to Use

1. Download the dataset "WA_Fn-UseC_-Telco-Customer-Churn.csv" from the source and place it in the same directory as the Jupyter Notebook.

2. Install the required libraries if you haven't already by running: `!pip install pandas numpy matplotlib seaborn scikit-learn xgboost`.

3. Open the "Telecom Customer Churn.ipynb" notebook using Jupyter Notebook or Jupyter Lab.

4. Run each cell sequentially to perform data analysis, preprocessing, modeling, and evaluation steps.

5. Observe the results, including accuracy scores, confusion matrices, and comparisons between different models.

## Conclusion

This notebook provides a comprehensive analysis of the telecom customer churn dataset, starting from data loading to model evaluation and comparison. By following the steps outlined in the notebook, you can gain insights into customer churn behavior and develop predictive models to identify potential churners.
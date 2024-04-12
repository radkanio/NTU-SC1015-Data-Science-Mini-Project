# Flight Delay Prediction (Classification) Project

## Overview
This mini-project for SC1015 (Introduction to Data Science and Artificial Intelligence) aims to predict flight delays using machine learning techniques. The dataset used is from the US Department of Transportation. The project involves data extraction, manipulation, cleaning, exploratory data analysis (EDA), and building predictive models using Decision Tree, Random Forest, and Logistic Regression algorithms.

## Problem Definition
The project's goal is to predict flight delays (classification: delayed or not) based on various factors such as departure time, airport, and airline. Understanding these factors and patterns can help improve strategies for addressing delays.

## Models Used
1. Decision Tree
2. Random Forest
3. Logistic Regression

## Contributors
- Komiya Reiki: Data Extraction, Data Cleaning and Preprocessing, Random Forest
- Isabelle Chan: Exploratory Data Analysis, Logistic Regression, Decision Tree
- Tan Jin Yenn: Data Extraction, Exploratory Data Analysis

## Key Steps
1. **Data Preparation**: Cleaned the dataset by dropping irrelevant columns, handling missing values, and focusing on informative variables.
2. **Exploratory Data Analysis (EDA)**: Revealed insights into delay types, relationships between airports/airlines and delays, temporal patterns, and reasons behind larger delays.
3. **Model Building**: Three machine learning models were selected and evaluated: Decision Tree, Random Forest, and Logistic Regression.
4. **Conclusion**: Logistic Regression with weighting performed the best, prioritizing true positive rates over overall accuracy in predicting flight delays.
5. **Key Learning Points**: Covered basic data cleaning, EDA using external libraries, model evaluation, weighting variables, and collaboration using GitHub.

## References
- [US Department of Transportation Flight Delays Dataset](https://www.kaggle.com/datasets/usdot/flight-delays)
- [Random Forest Classifier Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
- [Decision Tree Documentation](https://scikit-learn.org/stable/modules/tree.html)
- [Logistic Regression Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
- [Basemap Documentation](https://matplotlib.org/basemap/stable/)
- [Flight Delays Tutorial](https://www.kaggle.com/code/fabiendaniel/predicting-flight-delays-tutorial)
- SC1015 Lab Preparation and Exercises Materials

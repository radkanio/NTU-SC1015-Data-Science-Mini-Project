# Flight Delay Prediction (Classification) Project

## Overview
This project aims to predict flight delays using various machine learning techniques, leveraging a dataset from the US Department of Transportation. The prediction task involves classifying flights as delayed or not based on factors such as departure time, airport, and airline. The project follows a structured approach including data extraction, manipulation, cleaning, exploratory data analysis (EDA), model building, and conclusion.

### Note
The preliminary csv's we used can be found in the link below(there were too much before we compiled, so github did not allow us to upload them all). You can see the main csv files we used in the google drive here (https://drive.google.com/drive/folders/1drJMdo4-1klXYdzWG9EHwledGYfsG2_4?usp=sharing).

### Contributors
- **Komiya Reiki**: Data Extraction, Data Cleaning and Preprocessing, Random Forest
- **Isabelle Chan**: Exploratory Data Analysis, Logistic Regression, Decision Tree
- **Tan Jin Yenn**: Data Extraction, Exploratory Data Analysis

## Problem Definition
The primary objectives of the project are:
1. Predict flight delays to improve understanding and strategies for addressing them.
2. Identify essential factors and patterns linked to flight delays.
3. Evaluate machine learning models to determine the most effective approach for predicting flight delays.

## Models Used
The project employs the following machine learning models:
- Decision Tree
- Random Forest
- Logistic Regression

## Key Steps
1. **Data Preparation**: Cleaning the dataset by dropping irrelevant columns, handling missing values, and focusing on informative variables.
2. **Exploratory Data Analysis (EDA)**: Revealing insights into delay types, relationships between airports/airlines and delays, temporal patterns, and reasons behind larger delays.
3. **Model Building**: Utilizing Decision Tree, Random Forest, and Logistic Regression models.
4. **Conclusion**: Discussing model performance, overfitting, biases, and the incorporation of weighing to improve predictions.

## Key Learning Points
- Cleaning data using basic techniques.
- Employing external libraries for EDA, such as Basemap and collections.
- Ensuring predictors used are legal and sensible.
- Utilizing various machine learning models beyond class material.
- Evaluating models effectively.
- Applying weighting to variables to influence true positive rates (TPR), true negative rates (TNR), etc.
- Collaborating using GitHub.

## References
- [US Department of Transportation Flight Delays Dataset](https://www.kaggle.com/datasets/usdot/flight-delays)
- [Random Forest Classifier Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
- [Decision Tree Documentation](https://scikit-learn.org/stable/modules/tree.html)
- [Logistic Regression Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
- [PyAirports Documentation](https://pypi.org/project/pyairports/)
- [Basemap Documentation](https://matplotlib.org/basemap/stable/)
- [Flight Delay Prediction Tutorial](https://www.kaggle.com/code/fabiendaniel/predicting-flight-delays-tutorial)
- Material from SC1015 Lab Preparation and Exercises

---

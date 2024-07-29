# Water Quality Classification Using Machine Learning Algorithms

# Overview
This project involves classifying water quality using machine learning algorithms. The goal is to develop a model that can predict the water quality index (WQI) based on various water parameters.

# Methodology
# Data Preprocessing:
Convert object data types to numeric.
Replace string 'NAN' values with actual np.nan.
Handle missing values by filling them with the median or manually based on location-specific conditions.

# Exploratory Data Analysis (EDA):
The final dataset consists of 1988 samples and 12 attributes.
Calculate the Water Quality Index (WQI) using the Weighted Arithmetic Water Quality Index Method.

# Parameters:
Standard values for parameters such as Dissolved Oxygen, pH, Conductivity, Biological Oxygen Demand, Nitrate, Fecal Coliform, and Total Coliform.
Calculation of unit weights and ideal values for these parameters.

# Classification:
Set contamination levels based on WQI:
Excellent (0-25)
Good (26-50)
Poor (51-75)
Very Poor (>75)

# Machine Learning Models:
Logistic Regression
Support Vector Machine (SVM)
Decision Tree
K-Nearest Neighbors (KNN)
RandomForest
CatBoost
XGBoost
Ensemble Methods (combining Random Forest, CatBoost, and MLPClassifier)

# Results
The project applies multiple machine learning models to predict water quality classification and evaluates their performance to determine the most effective model for this task.

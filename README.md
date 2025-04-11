# House Price Prediction using Regression and ANN
This project predicts house prices using a popular Kaggle dataset with 80 features. It applies both traditional regression models and deep learning (ANN) to identify the most accurate approach for real estate price estimation.

## Project Overview
Goal: Predict sale prices of houses based on various features

Dataset: Kaggle - House Prices: Advanced Regression Techniques

Models Used:

Ridge Regression

Artificial Neural Network (ANN)

## Key Results
Model	R² Score
Ridge Regression	88.98% 
ANN (Neural Network)	84.50%
## Technologies Used
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn (for regression models)

TensorFlow / Keras (for ANN)

## Steps Performed
Data Exploration

Analyzed all 80 features to understand data types, missing values, and distributions.

Preprocessing

Handled missing values

Converted categorical features

Feature scaling and normalization

Model Training

Applied multiple regression models

Tuned Ridge Regression for optimal performance

Built a simple ANN using Keras

Evaluation

Used R² score as the primary metric

Ridge outperformed other models

## Conclusion
Ridge Regression emerged as the best model for this dataset with 88.98% R².

ANN performed decently but under Ridge due to dataset size and feature type.

Project emphasizes the importance of feature engineering, model selection, and evaluation techniques in machine learning workflows.

## Author
Chayan Ghosh
Regression Model Analyst & Deep Learning Practitioner
Specializing in machine learning applications in real-world domains

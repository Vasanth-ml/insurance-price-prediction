# Insurance Price Prediction

## Problem Statement
Predict medical insurance charges based on patient 
information such as age, BMI, smoking status, 
and region using Machine Learning.

## Dataset
- Source: Kaggle - Medical Cost Personal Dataset
- Size: 1338 rows, 7 features
- Target: charges (insurance cost)

## Features
- age: Age of patient
- sex: Gender (male/female)
- bmi: Body Mass Index
- children: Number of children
- smoker: Smoking status (yes/no)
- region: Residential region in US

## Algorithm Used
Linear Regression

## Results
- R² Score: 0.78
- MAE: 4181
- MSE: 33,596,915

## Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Steps Performed
1. Data Loading and Exploration
2. Encoding Categorical Variables (pd.get_dummies)
3. Train Test Split (80/20)
4. Model Training
5. Model Evaluation (MAE, MSE,

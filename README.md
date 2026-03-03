# Student Score Prediction using Linear Regression

## Problem Statement
The goal of this project is to predict a student's final exam score based on study-related factors such as study hours, attendance, and previous performance.

## Dataset Description
The dataset contains 20 student records with the following features:
- Hours_Studied
- Attendance
- Previous_Score
- Study_Efficiency (engineered feature)

## Data Exploration
Performed:
- Head and tail inspection
- Shape and data types check
- Missing value check
- Scatter plot, histogram, and boxplot visualization

## Model Used
Linear Regression

## Evaluation Metrics
- Mean Absolute Error (MAE)
- R2 Score

## Experiments
1. Trained model with all features
2. Removed Attendance feature
3. Added Study_Efficiency feature
4. Checked overfitting by training on full dataset

## Results
- Original Model R2: ~0.9991
- Improved Model R2 (with engineered feature): ~0.9992
- MAE: Less than 0.5

## Conclusion
Feature engineering slightly improved performance. 
Using train-test split provides realistic evaluation and prevents overfitting.

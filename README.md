# Credit Card Dataset Final Project

Student ID: KriAgu7298

## Project Overview
This project analyzes a Credit Card dataset using machine learning. The goal is to explore customer characteristics, predict credit expenditure, and identify spending patterns.

## Machine Learning Models
- Logistic Regression for classification
- Ridge Regression for predicting expenditure
- K-Means for customer clustering

## Scenario Analysis
Three scenarios were tested using the optimized Ridge Regression model:
1. Customer income increases by 20%.
2. Customer income decreases by 20%.
3. Active credit accounts increase by one.

A sensitivity analysis was also performed to examine how income and active credit accounts affect predicted expenditure.

## Results
The optimized classification model achieved 93.15% accuracy, but its F1 score was 0. The optimized regression model had an RMSE of 251.54 and an R-squared value of 0.1709. The optimized clustering model achieved a silhouette score of 0.3920.

## Dependencies
- Python
- pandas
- numpy
- matplotlib
- scikit-learn
- Google Colab

## Project Files
- Credit_Card_Final_Project.ipynb
- Credit Card dataset CSV file

## Conclusion
This project helped demonstrate how machine learning and scenario analysis can be used to explore customer spending patterns. The results also showed the importance of understanding model limitations before using predictions for business decisions.

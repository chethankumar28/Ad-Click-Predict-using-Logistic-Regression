# Ad-Click-Predict-using-Logistic-Regression
Logisitc Regression is commonly used to estimate the probability that an instance belongs to a particular class. If the estimated probability that an instance is greater than 50%, then the model predicts that the instance belongs to that class 1, or else it predicts that it does not. This makes it a binary classifier.

## Project Overview
This project implements a **Logistic Regression binary classification model** to predict whether an internet user will click on an online advertisement. The prediction is based on user demographic and behavioral features.

## Objective
To build a machine learning model that predicts:
- **1** → User clicked on the ad  
- **0** → User did not click on the ad  

## Dataset Description
The dataset contains information about internet users, including:
- Daily Time Spent on Site
- Age
- Area Income
- Daily Internet Usage
- Gender (Male)
- Target Variable: Clicked on Ad

## Methodology
1. Data loading and exploration
2. Data preprocessing and feature selection
3. Correlation analysis to identify important features
4. Train-test split
5. Logistic Regression model training
6. Model evaluation using accuracy and confusion matrix
7. Prediction on unseen data

## Correlation Analysis (Key Insights)
- **Daily Internet Usage** and **Daily Time Spent on Site** showed strong negative correlation with ad clicks.
- **Age** had a moderate positive impact.
- **Gender** showed negligible influence and was excluded.

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Results
- Successfully classified user ad-click behavior
- Identified key behavioral patterns influencing ad engagement
- Demonstrated practical application of Logistic Regression in digital marketing analytics

## Author
Chethan Kumar S

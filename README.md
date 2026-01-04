# Ad-Click-Predict-using-Machine-Learning
Logisitc Regression is commonly used to estimate the probability that an instance belongs to a particular class. If the estimated probability that an instance is greater than 50%, then the model predicts that the instance belongs to that class 1, or else it predicts that it does not. This makes it a binary classifier.

## Project Overview
This project implements an **end-to-end machine learning pipeline** to predict whether a user will click on an online advertisement. It combines **Logistic Regression**, **advanced evaluation metrics**, **feature scaling**, **model comparison**, and **hyperparameter tuning** to build a production-ready binary classification system.

## Problem Statement
Predict whether a user will click on an online advertisement (**binary classification**) based on demographic and behavioral features.

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

## Machine Learning Workflow

### Exploratory Data Analysis
- Correlation analysis to identify influential features
- Removal of weak predictors

### Feature Engineering
- Numerical feature scaling using:
  - **StandardScaler**
  - **MinMaxScaler**
- Column-wise preprocessing using `ColumnTransformer`

### Logistic Regression (Baseline Model)
- Implemented Logistic Regression with **sigmoid activation**
- Trained using `liblinear` solver
- Evaluated using accuracy, precision, recall, F1-score, and confusion matrix

### Model Evaluation (Advanced)
- Precision–Recall Curve
- ROC Curve
- ROC–AUC Score
- Threshold-based precision–recall tradeoff analysis

### Model Comparison
- Trained **Random Forest Classifier**
- Compared performance against Logistic Regression to evaluate non-linear decision boundaries
- 
### Hyperparameter Tuning
- Applied **GridSearchCV (10-fold CV)**
- Tuned:
  - Regularization (L1, L2)
  - Regularization strength (C)
  - Class weights
  - Solver selection
- Optimized using **F1-score**
- 
## Key Results
- Logistic Regression achieved strong performance with optimized regularization
- Feature scaling significantly improved convergence and stability
- ROC–AUC confirmed strong discriminative ability
- Random Forest provided a comparative benchmark for non-linear learning

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Future Enhancements
- Model deployment using FastAPI
- Feature importance visualization
- Cost-sensitive learning
- Real-time ad click prediction system

## Author
Chethan Kumar S

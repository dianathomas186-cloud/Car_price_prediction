# Car_price_prediction
A machine learning project to predict car prices using multiple regression models, including data preprocessing, feature importance analysis, model comparison, and hyperparameter tuning to identify the most accurate model.

**Project Overview**

This project focuses on predicting car prices using machine learning regression models. It includes data preprocessing, feature engineering, model comparison, evaluation, feature importance analysis, and hyperparameter tuning to identify the best-performing model.

**Objective**

To build machine learning models for predicting car prices
To compare different regression algorithms
To evaluate model performance using R², MSE, and MAE
To identify important features affecting car price
To improve model performance using hyperparameter tuning


**The dataset includes features such as:**

Car brand
Engine size
Horsepower
Fuel type
Mileage


**Other specifications influencing car price**

**Technologies & Libraries**

Python
Pandas
NumPy
Scikit-learn

**Models Used**

The following regression models were implemented:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor (SVR)

**Model Evaluation Metrics**

The models were evaluated using:

R² Score → Measures how well the model explains variance
Mean Squared Error (MSE) → Measures squared prediction error
Mean Absolute Error (MAE) → Measures average prediction error

**Best Model Selection & Justification**

The best model was selected based on:

Highest R² Score
Lowest MSE
Lowest MAE

**Justification:**

The selected model performs better because:
It explains maximum variance in the dataset
It produces fewer prediction errors
It gives more accurate and reliable predictions compared to other models

**Feature Importance & Selection**

Feature importance was calculated using Random Forest.
All features were ranked based on importance scores
Top important features were selected


**Reason for Selection:**

Selected features have the highest importance scores
They contribute most to predicting car price
Removing low-importance features reduces noise
Improves model efficiency and accuracy

**Hyperparameter Tuning**

Hyperparameter tuning was performed using GridSearchCV.

Tuned Parameters:

Number of estimators
Maximum depth
Minimum samples split

**Result:**

Improved model performance
Better accuracy compared to default model


**Conclusion**

Multiple machine learning models were implemented
The best model was selected based on evaluation metrics
Feature importance helped identify key influencing variables
Hyperparameter tuning improved model performance

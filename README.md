# Customer-churn-prediction

This project focuses on predicting customer churn in the telecom industry using Machine Learning. The goal of this model is to classify customers as “Churn” or “No Churn” based on their information, subscription details, and usage patterns.

## Project Workflow

### Data Collection:

The dataset was sourced from a telecom customer database containing user gender, account information, and service usage statistics.
Dataset : https://www.kaggle.com/code/mehmetisik/telecom-churn-prediction-learning-ml-models/input

### Data Preprocessing:

Handled missing values.

Encoded categorical features using label/one-hot encoding.


### Exploratory Data Analysis (EDA):

Visualized churn distribution and correlations with customer attributes.

Identified key features influencing churn (e.g., contract type, tenure, monthly charges,total charges).

### Model Building:

Trained multiple models including DecisionTree, Random Forest, and XGBoost.

Used RandomizedSearchCV for hyperparameter tuning to optimize model performance.

###  Evaluation Metrics:

Accuracy, Precision, Recall, F1-Score were used to measure performance.

Confusion Matrix were included for model interpretation.

### Results

The XGBoost Classifier achieved the best performance with an Accuracy -  0.78




# Predicting-Heart-Disease
In this machine learning project, I have collected the dataset from kaggle
(https://www.kaggle.com/ronitf/heart-disease-uci) and I will be using Machine Learning to predict whether
any person is suffering from heart disease

There are some steps involved:-
### 1. Exploratory Data Analysis
  
  The main goal in exploratory data analysis is to find more about the data and become a 
  subject matter export on the dataset you're working with
  
  1. What questions are you trying to solve?
  2. What kind of data do we have and how do we treat different types?
  3. What is missing from the data and how do you deal with it?
  4. Where are the outliers and why should you care about them?
  5. How can you add, change or remove features to get more out of your data?

### 2. Correlation Matrix
  
    - After fbs and chol are the  lowest correlated with the target variable
    - All other variables have a significant correlation with the target variable

### 3. Data Processing
  After exploring the dataset, I observed that I need to convert some categorical         variables into dummy variables and scale all the values before training the Machine     Learning models. First, I'll use the get_dummies method to create dummy columns
  for categorical variables.

### 4. Applying machine learning algorithms
    
    We have applied 6 different machine learning models:
    
    1. Logistic Regression
    2. K-Nearest Neighbours Classifier
    3. Support Vector machine
    4. Decision Tree Classifier
    5. Random Forest Classifier
    6. XGBoost Classifier
    

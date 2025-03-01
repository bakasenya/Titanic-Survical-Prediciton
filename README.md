# Titanic Survival Prediction Using Machine Learning

## Overview

In this project, we aim to predict the survival of Titanic passengers using machine learning techniques. The model developed achieves an accuracy of 77%, demonstrating the ability to make reliable predictions based on historical data.

## Libraries Used
We utilized several Python libraries that played crucial roles in data manipulation, analysis, and visualization:
pandas: A versatile library for data manipulation and analysis, enabling efficient handling of tabular data structures.
numpy: A fundamental library for numerical operations, empowering us with mathematical operations on arrays.
seaborn: A powerful data visualization library based on matplotlib, simplifying the creation of statistical graphics.
matplotlib.pyplot: A widely used library for generating plots and charts, vital for visualizing data and analysis results.
scikit-learn: A machine learning library that provides various models and tools for data preprocessing, model training, and evaluation.

## Loading Data
The project begins by loading the Titanic passenger data from CSV files using the pandas library. The data is divided into two sets:
train.csv: Contains the training data, including the features (e.g., Age, Sex, Pclass) and the target variable (Survived).
test.csv: Contains the data for which predictions are made, without the target variable (Survived).

## Exploratory Data Analysis (EDA)
Exploratory Data Analysis (EDA) is performed to understand the dataset deeply. Key steps include:
Visualizing Distributions: We analyze key numerical features like age, number of siblings/spouses (SibSp), number of parents/children (Parch), and fare, uncovering trends and identifying outliers.
Exploring Relationships: By exploring relationships between different variables, we reveal correlations that may influence survival outcomes.

## Data Cleaning
In the data cleaning stage, we address several challenges:
Handling Missing Values: We use imputation methods to fill missing values in critical columns like Age and Fare.
Dropping Irrelevant Columns: Columns like PassengerId, Cabin, Name, and Ticket are dropped as they do not significantly contribute to the analysis.
Feature Engineering: New features are created, and existing features are transformed to enhance the predictive power of the model.

## Conclusion
With an accuracy rate of 77%, the model demonstrates its ability to effectively predict Titanic passenger survival. This project showcases the practical use of machine learning techniques on historical data, offering valuable insights into the factors influencing survival rates during the Titanic disaster.

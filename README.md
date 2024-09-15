# Boston-House-Price-Prediction
The the goal of this project is to predict the housing prices of a town or a suburb based on the features of the locality provided to us. In the process, we need to identify the most important features affecting the price of the house. We employed techniques of data preprocessing and built a linear regression model that predicts the prices for the unseen data.
# Table of content
* Project Overview
* Dataset
* Models Used
* Evaluation Metrics
* Results

# Project Overview
The Boston House Price Prediction project involves the following steps:

Exploratory Data Analysis (EDA): Understanding the dataset and visualizing relationships between features and house prices.
Data Preprocessing: Handling missing data, feature scaling, and data splitting.
Modeling: Building various machine learning models to predict house prices.
Evaluation: Using metrics like Mean Squared Error (MSE) and R² to evaluate model performance.

# Dataset
Each record in the database describes a house in Boston suburb or town. Detailed attribute information can be found below:

Attribute Information:

* CRIM: Per capita crime rate by town
* ZN: Proportion of residential land zoned for lots over 25,000 sq.ft.
* INDUS: Proportion of non-retail business acres per town
* CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
* NOX: Nitric Oxide concentration (parts per 10 million)
* RM: The average number of rooms per dwelling
* AGE: Proportion of owner-occupied units built before 1940
* DIS: Weighted distances to five Boston employment centers
* RAD: Index of accessibility to radial highways
* TAX: Full-value property-tax rate per 10,000 dollars
* PTRATIO: Pupil-teacher ratio by town
* LSTAT: % lower status of the population
* MEDV: Median value of owner-occupied homes in 1000 dollars

# Model Used
Linear Regression

# Evaluation Metrics
We evaluate the performance of our models using the following metrics:

Mean Squared Error (MSE): Measures the average squared difference between actual and predicted values.
R² (R-squared): Indicates how well the model fits the data, where 1.0 is a perfect fit.

# Result              
Linear Regression:	
MSE=22.18	
R^2=0.74

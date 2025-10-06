# Observations

# Data Cleaning:

Some of the data contained missing or invalid values, particularly in the horsepower column, which was marked by the '?' symbol.
These missing values were replaced with NaN, and the affected rows were removed to ensure the model is working with clean data.


# Correlation of Features:

By creating a correlation matrix, it became clear that some variables have a strong relationship with the target variable MPG:
Weight shows a strong negative correlation with MPG. This indicates that heavier cars tend to be less fuel-efficient.
Horsepower also shows a notable negative correlation with MPG, suggesting that cars with higher engine power tend to consume more fuel.
Acceleration and Displacement show a moderate to weak correlation with MPG.


# Linear Regression:

A simple linear regression model was used to learn the relationship between the selected features (Cylinders, Displacement, Horsepower, Weight, Acceleration) and the target variable (MPG).
The model was trained on 80% of the data and validated on the remaining 20%.

# ML-Regression-Techniques
This repository contains a set of examples and implementations of various machine learning regression techniques, with a focus on linear regression. The code demonstrates how to load and prepare data, split datasets, create and train regression models, visualize results, and evaluate model performance.

## Table of Contents
* Introduction
* Techniques Implemented
* Prerequisites
* Results
* Contributing


### Introduction
Regression analysis is a fundamental statistical technique used to understand the relationship between independent (predictor) variables and a dependent (target) variable. This repository primarily focuses on linear regression as a starting point for understanding more complex regression methods.

### Techniques Implemented
1. Data Preparation
Loading Data: Import data from CSV files.
Data Exploration: Inspect data using head(), info(), describe(), etc.
Reshaping Data: Convert Pandas Series to NumPy arrays and reshape to 2D arrays for model compatibility.
2. Data Splitting
Training and Testing Sets: Slicing technique to split data into training (80%) and testing (20%) sets.
3. Data Visualization
Scatter Plot: Visualize the relationship between the independent and dependent variables.
Regression Line: Plot the model's predictions to visualize the fit.
4. Model Creation and Training
Linear Regression Model: Using scikit-learn's LinearRegression to create and train the model on the training dataset.
5. Model Evaluation
R² Score: Calculate the R² score to determine how well the model explains the variability in the target variable. A value of R² = 1 indicates perfect predictions.

### Prerequisites
Make sure you have the following libraries installed:

Python 3.x
numpy
pandas
matplotlib
scikit-learn

### Results
After running the code, you will:

Visualize your dataset using scatter plots.
See the regression line fitted to your data.
Get an output of the R² score indicating model performance.
These steps provide a comprehensive understanding of how linear regression works and how it can be evaluated.

### Contributing
Contributions are welcome! If you have improvements, new techniques, or additional examples, feel free to fork this repository and submit a pull request.

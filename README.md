# Ecommerce Customer Analysis

This repository contains Python code for analyzing customer data from an ecommerce company. The analysis includes exploratory data analysis (EDA), visualization, and building a linear regression model to predict yearly amount spent by customers.

## Overview

The analysis is performed using the following steps:

1. **Data Loading**: The dataset 'Ecommerce Customers' is loaded into a pandas DataFrame.

2. **Data Exploration**: Descriptive statistics and information about the dataset are obtained to understand its structure and contents.

3. **Data Visualization**:
   - Relationships between variables are visualized using seaborn joint plots and pair plots.
   - Linear regression plots are created to explore the relationship between customer attributes and yearly amount spent.

4. **Model Building**:
   - Features (X) and target variable (y) are defined.
   - The dataset is split into training and testing sets.
   - A Linear Regression model is trained on the training data to predict yearly amount spent.

5. **Model Evaluation**:
   - Model coefficients are printed to understand the impact of each feature on yearly amount spent.
   - Predictions are made on the test data, and evaluation metrics such as Mean Absolute Error, Mean Squared Error, and Root Mean Squared Error are calculated.
   - The distribution of predicted values is visualized using a density plot.

## Files Included

- `Ecommerce Customers`: The dataset containing customer information.
- `Linear_Regression_Project.ipynb`: Jupyter Notebook containing the Python code for data analysis.

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run

To run the analysis, make sure you have Jupyter Notebook installed along with the required libraries. Then, simply open the `Linear_Regression_Project.ipynb` notebook and execute each cell sequentially.

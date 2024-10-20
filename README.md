# ML_LAB_1

Aim: Linear Regression with Gradient Descent
Project Overview
This project demonstrates the implementation of linear regression using gradient descent. The goal is to predict profits based on population data using a dataset provided in ex1data1.csv. The algorithm is implemented from scratch using Python and the numpy library.

Dataset
The dataset (ex1data1.csv) contains two columns:
Population: The population of a city (in 10,000s)
Profit: The profit for a company in that city (in $10,000s)

Dataset Summary
Total Rows: 97
Total Columns: 2 (Population, Profit)

Files in Repository
linear_regression.py: Contains the main code for loading the data, computing cost function, and performing gradient descent.
ex1data1.csv: The dataset used for training the linear regression model.
README.md: This file.

Steps
1)Data Loading: The data is loaded using pandas and a brief summary is printed to understand the structure and size.

2)Data Visualization: A scatter plot is created to visualize the relationship between population and profit.

3)Data Preparation:A column of ones is added to the data to represent the intercept term.
Data is split into input variables X and output variable Y.
Matrices are created using numpy for performing matrix operations.

4)Cost Function: The cost function is implemented to compute the error between predictions and actual values.

5)Gradient Descent: The gradient descent algorithm is implemented to minimize the cost function. 

6)Model Training:

The algorithm is trained using a learning rate(𝛼) of 0.001 and 1000 iterations.
The final optimized parameters (𝜃) are printed along with the cost value at each iteration.


Results
After running the gradient descent algorithm, the cost reduces significantly, and the optimized parameter values provide a linear fit for predicting profit based on population.

Final Parameters
𝜃 (zero): 5.049
𝜃1:  0.000 (due to the learning rate chosen)
Cost after final iteration
Cost: 32.07

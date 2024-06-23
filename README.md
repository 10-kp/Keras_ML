# Customer Churn Prediction Using Keras

This repository contains the analysis and model building for predicting customer churn at a telecom company named "Leo". The dataset used is 'Customer_Churn'. The main objective is to analyze the data, derive insights, and build predictive models to identify customers likely to churn.

## Project Notebooks

- [Capstone 2 - Project.ipynb](https://github.com/10-kp/Keras_ML/blob/a6620852eae24caaf38130df3972705e1744f1fb/Capstone%202%20-%20Project.ipynb)

### Dataset

The dataset Customer_Churn includes various customer details, and the target variable is whether the customer has churned or not.
## Data Transformations

### Domain Context

Customer churn refers to when customers stop doing business with a company. This is a critical issue in the telecom industry, and predictive models help identify customers who are likely to churn, allowing the company to take proactive measures.

### Environment
The analysis and modeling are performed using Jupyter Notebook.

### Objective
To perform data modeling by applying various transformations using Query Editor.

###Tasks

A) Data Manipulation
Find the total number of male customers.
Find the total number of customers whose Internet Service is ‘DSL’.
Extract all the female senior citizens whose Payment Method is Mailed check & store the result in new_customer.
Extract all those customers whose tenure is less than 10 months or their Total charges is less than $500 & store the result in new_customer.

B) Data Visualization
Build a pie-chart to show the distribution of customers who would be churning out.
Build a bar-plot to show the distribution of ‘Internet Service’.

C) Model Building

Model 1
Build a sequential model using Keras, to find out if the customer would churn or not, using ‘tenure’ as the feature and ‘Churn’ as the target column:
The visible/input layer should have 12 nodes with ‘Relu’ as the activation function.
This model would have 1 hidden layer with 8 nodes and ‘Relu’ as the activation function.
Use ‘Adam’ as the optimization algorithm.
Fit the model on the train set, with the number of epochs set to 150.
Predict the values on the test set and build a confusion matrix.
Plot the ‘Accuracy vs Epochs’ graph.

Model 2
Build the 2nd model using the same target and feature variables:
Add a drop-out layer after the input layer with a drop-out value of 0.3.
Add a drop-out layer after the hidden layer with a drop-out value of 0.2.
Predict the values on the test set and build a confusion matrix.
Plot the ‘Accuracy vs Epochs’ graph.

Model 3
Build the 3rd model using ‘Tenure’, ‘Monthly Charges’ & ‘Total Charges’ as the features and ‘Churn’ as the target column:
The visible/input layer should have 12 nodes with ‘Relu’ as the activation function.
This model would have 1 hidden layer with 8 nodes and ‘Relu’ as the activation function.
Use ‘Adam’ as the optimization algorithm.
Fit the model on the train set, with the number of epochs set to 150.
Predict the values on the test set and build a confusion matrix.
Plot the ‘Accuracy vs Epochs’ graph.

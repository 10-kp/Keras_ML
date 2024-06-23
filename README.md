# Customer Churn Prediction Using Keras

![image](https://github.com/10-kp/Keras_ML/assets/70857174/38307893-bc9f-4fd9-9938-9d5ac5bb704b)

This repository contains the analysis and model building for predicting customer churn at a telecom company named "Leo". The dataset used is 'Customer_Churn'. The main objective is to analyze the data, derive insights, and build predictive models to identify customers likely to churn

## Project Notebooks

- [Capstone 2 - Project.ipynb](https://github.com/10-kp/Keras_ML/blob/a6620852eae24caaf38130df3972705e1744f1fb/Capstone%202%20-%20Project.ipynb)

### Dataset

The dataset `Customer_Churn` includes various customer details, and the target variable is whether the customer has churned or not.

## About

This project aims to predict customer churn for the telecom company "Leo" using Keras. It involves data manipulation, visualization, and model building to identify customers likely to churn.

### Key Features

- **Data Manipulation**: Prepare the dataset for analysis and modeling.
- **Data Visualization**: Visualize customer distribution and service usage.
- **Model Building**: Develop and evaluate sequential models using Keras.

## Tasks

### A) Data Manipulation

- Find the total number of male customers.
- Find the total number of customers whose Internet Service is ‘DSL’.
- Extract specific customer segments based on criteria such as senior citizens and payment methods.

### B) Data Visualization

- Build a pie-chart to show the distribution of customers who would be churning out.
- Build a bar-plot to show the distribution of ‘Internet Service’.

### C) Model Building

#### Model 1

- Build a sequential model using Keras with tenure as the feature.
- Input layer: 12 nodes, 'Relu' activation.
- Hidden layer: 8 nodes, 'Relu' activation.
- Optimizer: 'Adam'.
- Epochs: 150.

#### Model 2

- Add dropout layers to Model 1 for improved robustness.

#### Model 3

- Use tenure, monthly charges, and total charges as features.

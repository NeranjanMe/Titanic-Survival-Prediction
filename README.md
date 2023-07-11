# Titanic Survival Prediction

This repository contains code for predicting the survival of passengers on the Titanic using logistic regression. The goal is to build a model that can accurately classify whether a passenger survived or not based on various features.

## Dataset

The dataset used for this project is the Titanic dataset, which contains information about the passengers onboard the Titanic, such as their age, gender, passenger class, fare, etc. The dataset is provided as a CSV file named `train.csv`.

## Setup

To run the code, you need to have Python installed on your machine. The code is written in Jupyter Notebook.

1. Clone the repository:

2. Install the required libraries:

3. Run the Jupyter Notebook:

## Exploratory Data Analysis

Before building the predictive model, it's important to explore the dataset and gain insights into the data. The following steps are performed in the notebook:

- Loading and inspecting the dataset
- Checking for missing data and handling missing values
- Visualizing the distribution of variables using bar plots and histograms
- Converting categorical data to numerical data

## Model Training and Evaluation

The logistic regression model is used for predicting survival. The following steps are performed:

- Splitting the data into training and testing sets
- Initializing and fitting the logistic regression model
- Making predictions on the training and test data
- Evaluating the model's accuracy on both training and test data

## Results

The accuracy score of the model on the training data is printed as: `Accuracy score of training data: X%`. Similarly, the accuracy score of the model on the test data is printed as: `Accuracy score of test data: X%`. The higher the accuracy score, the better the model's performance.

## Conclusion

The logistic regression model shows promising accuracy in predicting survival on the Titanic dataset. Further improvements and feature engineering can be explored to enhance the model's performance.

Feel free to explore the code, make changes, and experiment with different models or techniques!
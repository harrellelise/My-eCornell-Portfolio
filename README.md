
# My-eCornell-Portfolio: Airbnb Price Prediction with Random Forest
## Overview
Welcome to the My-eCornell-Portfolio repository! This is the final project for my Machine Learning Foundations course. In this project, I created a machine learning model to predict the price per night of Airbnb bookings using a Random Forest model. The project consists of two main parts:

**ChooseYourProblemAndData.ipynb**: This Jupyter notebook focuses on the data cleaning process. It includes data preprocessing techniques like one-hot encoding, handling missing values, and addressing large outliers through winsorization.

**ImplementMLProjectPlan.ipynb:** This notebook outlines the steps to build and train the machine learning model. The model was built using a Random Forest algorithm, followed by hyperparameter tuning using GridSearchCV and stepwise feature selection to select the most important features.

## Note:
Since this dataset is private, it is not included in this repository. However, the code and approach can be applied to similar datasets for predictive modeling tasks.

## Objective
The goal of this project is to predict the price per night of an Airbnb listing based on various features such as location, amenities, and other listing attributes. The model leverages a Random Forest algorithm to make predictions based on the cleaned and transformed dataset.

## Approach
### 1. Data Preprocessing
In the ChooseYourProblemAndData.ipynb notebook:

One-hot encoding was applied to categorical variables to convert them into a numerical format.
Winsorizing was used to address missing values and large outliers, ensuring that data is clean and robust for modeling.
### 2. Feature Selection & Engineering
I applied stepwise feature selection to identify the most relevant features for the prediction task, which helped improve model efficiency.
### 3. Model Creation & Hyperparameter Tuning
In the ImplementMLProjectPlan.ipynb notebook:

A Random Forest Regressor was trained on the preprocessed data.
I performed GridSearchCV to fine-tune the model's hyperparameters and select the best configuration for better predictive performance.
### 4. Model Evaluation
The performance of the model was evaluated using standard regression metrics (e.g., R-squared, Mean Squared Error), ensuring that the model was accurate and could generalize well to unseen data.

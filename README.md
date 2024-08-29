

# Logistic Regression Project: Predicting Purchase Behavior

## Project Overview

This project involves applying a Logistic Regression model to predict whether a user purchases a product based on their age and estimated salary. The dataset used for this analysis is a part of a social network's ad campaign data, where the dependent variable (`Purchased`) indicates whether a user bought the product (1) or not (0).

## Dataset Description

The dataset consists of 400 observations with the following features:

- **User ID**: Unique identifier for each user (not used in the model).
- **Gender**: Gender of the user (not used in the model).
- **Age**: Age of the user.
- **EstimatedSalary**: Estimated salary of the user.
- **Purchased**: Dependent variable indicating purchase behavior (1 for purchased, 0 for not purchased).

## Project Workflow

1. **Data Preparation**: 
   - The dataset was loaded, and the relevant features (`Age` and `EstimatedSalary`) were selected as independent variables.
   - The target variable was set as `Purchased`.

2. **Data Splitting**:
   - The dataset was split into training and test sets using an 80-20 split. This was achieved using `train_test_split` from `scikit-learn`.

3. **Feature Scaling**:
   - Feature scaling was applied to the independent variables to standardize the data, which improves the performance of the Logistic Regression model.

4. **Model Training**:
   - A Logistic Regression model was trained on the training data using `scikit-learn`.

5. **Model Evaluation**:
   - The model was tested on the test data, and its performance was evaluated using a confusion matrix and accuracy score.

## Results

The Logistic Regression model provided insights into how user age and estimated salary influence their purchasing decisions. The model's accuracy and confusion matrix provide a quantitative measure of its predictive power.

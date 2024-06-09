# Car Price Prediction Project

## Overview

This project aims to utilize Linear regression model to predict the prices of cars based on various features such as make, model, year, mileage, and more. By building a machine learning model, we can provide estimates of car prices to assist buyers, sellers, and dealerships in making informed decisions.

The data was sourced from Kaggle https://www.kaggle.com/datasets/CooperUnion/cardataset



## Features

1. Data Cleaning

 The dataset underwent thorough cleaning to handle missing values, outliers, and inconsistencies. This ensures the quality and reliability of the data used for modeling.

2. Exploratory Data Analysis (EDA)

 Exploratory data analysis was performed to gain insights into the relationships between different features and the target variable (car prices). Visualizations and statistical summaries were used to understand the distribution and patterns in the data.

3. Feature Engineering

 New features were created and existing features were transformed to enhance the predictive power of the model. 
 We applied category encoder's target encoding and feature scaling to prepare the data for modeling.

4. Model Building

 The linear regression machine learning algorithm, was trained on the prepared dataset to predict car prices. Hyperparameter tuning and regularization techniques were employed to optimize model performance and prevent overfitting.
 
5. Model Evaluation
 The trained model was evaluated using the Root Mean Squared Error (RMSE) on both training and validation datasets. 

## Results 

- After incorporating additional features and applying regularization, the RMSE improved to 51 on validation data.

- Despite regularization efforts, the model still exhibited signs of overfitting, as indicated by an increase in RMSE on the validation data compared to the training data.

- Further experimentation and model refinement are necessary to improve predictive performance and address overfitting issues.

## Next Steps

- Revisit feature engineering to capture more relevant information.
- Experiment with different machine learning algorithms and ensemble techniques.
- Fine-tune hyperparameters and explore advanced regularization techniques.
- Continuously evaluate and iterate on the model to improve its accuracy and generalization capability.

## Conclusion

Despite the challenges encountered in building an accurate car price prediction model, this project serves as a valuable learning experience in data preprocessing, feature engineering, model selection, and evaluation. By addressing the limitations and incorporating feedback from evaluation results, we can work towards building a more robust and reliable model for car price prediction.
More details on the model building and specific challenges are highlighted on the ipynb file.

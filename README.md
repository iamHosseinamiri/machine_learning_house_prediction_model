# House Price Prediction Model 🏠💰

This repository contains a machine learning model for predicting the price of each house in different parts of California. The model utilizes various algorithms and techniques to provide accurate predictions based on the provided dataset.

## Introduction ℹ️

The primary goal of this project is to develop a predictive model that can estimate the price of houses accurately. The model takes into account various features such as location, size, number of rooms, and median income to make predictions. These predictions can be valuable for real estate agents, homeowners, and potential buyers to make informed decisions about pricing and investment.

## Dataset 📊

The dataset used for training and testing the model contains information about houses in different parts of California. It includes features such as median income, housing median age, average rooms, average bedrooms, population, and more. This dataset serves as the foundation for training the machine learning model to predict house prices accurately.

## Implementation 🛠️

The machine learning model is implemented using Python and various libraries such as pandas, scikit-learn, and matplotlib. The model undergoes several stages including data preprocessing, feature engineering, model selection, and evaluation.

### Data Preprocessing and Exploration 🔍

- The dataset is loaded using pandas, and basic statistics and visualizations are generated to gain insights into the data.
- Data is split into training and testing sets using the train_test_split function from scikit-learn.
- Missing values are handled using techniques such as mean imputation.
- Feature scaling is performed to ensure that all features have a similar scale.
- Categorical variables are encoded using techniques such as one-hot encoding.

### Model Selection and Evaluation 📈

- Several machine learning algorithms are considered for the task, including Linear Regression, Decision Tree Regression, Random Forest Regression, Support Vector Machine Regression, and K-Nearest Neighbors Regression.
- Cross-validation is used to evaluate each model's performance and select the best one based on the mean squared error metric.
- Hyperparameter tuning is performed using GridSearchCV to find the optimal hyperparameters for the Random Forest Regression model.

### Model Deployment 🚀

- The final model, selected based on its performance during evaluation, is used to make predictions on the test set.
- The root mean squared error (RMSE) metric is calculated to evaluate the model's performance on unseen data.

## Results 📊

The final model achieves an RMSE of approximately 50069.90 on the test set, indicating its ability to predict house prices with reasonable accuracy.

## Usage 🚀

To use the model:

1. Clone the repository to your local machine.
2. Ensure that you have Python installed, version 3.12 or later.
3. Run the provided Jupyter notebook or Python script to train the model and make predictions.



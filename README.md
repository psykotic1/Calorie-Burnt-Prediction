# Calorie Burnt Prediction Project

## Introduction

This project aims to predict the number of calories burnt during physical exercise using the XGBoost Regressor algorithm. The prediction is based on a combined dataset of exercise and calorie information. By leveraging the powerful XGBoost algorithm, we aim to create a reliable model for calorie burnt prediction.

## Dataset

The project utilizes two datasets:
1. **Calorie Dataset:** Contains information about the number of calories burnt.
2. **Exercise Dataset:** Contains details about various physical exercises, including duration, intensity, and other relevant parameters.

These two datasets are combined to create a comprehensive dataset for training the model. The combined dataset includes features such as age, gender, exercise duration, heart rate, and the target variable (calories burnt).

## Algorithms Used

### XGBoost Regressor

XGBoost (Extreme Gradient Boosting) is an optimized gradient boosting library designed to be highly efficient, flexible, and portable. It implements machine learning algorithms under the Gradient Boosting framework. In this project, we use the XGBoost Regressor for predicting the number of calories burnt.

## Usage

1. Ensure that both datasets (calorie and exercise data) are placed in the appropriate directory (e.g., `data/calories.csv` and `data/exercise.csv`).

2. Combine the datasets and preprocess the data:
    - Load the datasets.
    - Merge them on a common attribute.
    - Handle missing values and perform any necessary data cleaning.

3. Train the XGBoost Regressor model:
    - Split the combined dataset into training and testing sets.
    - Train the model on the training set.
    - Evaluate the model on the testing set.

4. Predict calories burnt for new data using the trained model.

## Results

The performance of the XGBoost Regressor model is evaluated using metrics such as Mean Absolute Error (MAE). The results indicate that the model accurately predicts the number of calories burnt based on the input features from the combined dataset.

## Conclusion

This project demonstrates the application of the XGBoost Regressor algorithm for predicting calorie burnt during physical exercises. By combining the calorie and exercise datasets, we created a robust model that provides reliable predictions. The results highlight the effectiveness of XGBoost in regression tasks, making it a suitable choice for similar predictive modeling problems.

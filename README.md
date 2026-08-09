# Electricity Consumption Prediction

## 1. Project Overview

This project uses Machine Learning to predict electricity consumption based on environmental and time-related factors.

The project uses the Tetouan City Power Consumption dataset and applies Linear Regression to predict Zone 1 Power Consumption.

## 2. Problem Statement

Electricity consumption changes according to factors such as temperature, humidity, wind speed, and time of day.

The objective of this project is to build a machine learning model that can predict electricity consumption using these factors.

## 3. Dataset

The dataset used in this project is the Tetouan City Power Consumption dataset.

It contains information about:

- Date and time
- Temperature
- Humidity
- Wind speed
- General diffuse flows
- Diffuse flows
- Zone 1 Power Consumption
- Zone 2 Power Consumption
- Zone 3 Power Consumption

For this project, Zone 1 Power Consumption is used as the target variable.

## 4. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Linear Regression
- GitHub

## 5. Methodology

The project follows these steps:

1. Load the dataset.
2. Convert the DateTime column.
3. Extract hour, day, month, and day of week.
4. Select input features.
5. Select Zone 1 Power Consumption as the target.
6. Split the dataset into training and testing data.
7. Train a Linear Regression model.
8. Predict electricity consumption.
9. Evaluate the model.
10. Visualize actual and predicted consumption.

## 6. Input Features

The model uses:

- Temperature
- Humidity
- Wind Speed
- General Diffuse Flows
- Diffuse Flows
- Hour
- Day
- Month
- Day of Week

## 7. Machine Learning Model

Linear Regression is used because electricity consumption is a continuous numerical value.

The model learns the relationship between the input features and Zone 1 Power Consumption.

## 8. Evaluation Metrics

The model is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## 9. Results

The model performance obtained during testing was:

| Metric | Value |
|---|---:|
| MAE | 4208.61 |
| MSE | 21640555.54 |
| RMSE | 4651.94 |
| R² Score | 0.4309 |

The R² score indicates that the model captures a portion of the variation in electricity consumption.

## 10. Visualization

The project includes an Actual vs Predicted Power Consumption graph.

The graph compares the actual electricity consumption values with the values predicted by the machine learning model.

## 11. Conclusion

This project demonstrates how machine learning can be used for electricity consumption prediction.

The Linear Regression model was trained using environmental and time-based features. The model produced predictions that were compared with the actual electricity consumption values using different evaluation metrics.

This project provides a basic machine learning approach for understanding and predicting electricity consumption.

## 12. Files in this Repository

- `power_consumption_prediction.ipynb` – Jupyter/Google Colab notebook containing the complete Python code.
- `actual_vs_predicted.png` – Actual vs Predicted electricity consumption graph.
- `README.md` – Project documentation.

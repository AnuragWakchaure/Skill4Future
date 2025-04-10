# 🔋 Energy Consumption Prediction and Optimization

This project focuses on forecasting and optimizing energy usage in buildings using machine learning techniques. We leverage historical energy consumption data and weather conditions to predict future usage patterns and provide actionable insights for optimization.

## 📌 Project Overview

- **Objective**: Predict hourly energy consumption for a commercial building and suggest energy optimization strategies.
- **Approach**: Data preprocessing → Feature engineering → KNN Regression → Forecasting → Optimization insights.
- **Dataset**: Hourly energy usage and weather data from 2016–2017.

## 📁 Dataset

- **Building Energy Data**: Hourly electricity usage (kWh) for over 500 buildings.
- **Weather Data**: Hourly temperature, humidity, wind speed, and more.
- **Focus Building**: `Panther_office_Hannah` for targeted forecasting.

## 🧪 Methods Used

- **Data Cleaning**: Handling missing values, filtering outliers, and resampling.
- **Feature Engineering**:
  - One-hot encoding for hour and weekday
  - Time and temperature as key predictors
- **Model**: `K-Nearest Neighbors (KNN)` for regression
- **Evaluation Metric**: Mean Absolute Percentage Error (MAPE)

## 📊 Results

- **Test Month**: July 2017
- **MAPE**: ~33.59%
- Predictions closely followed daily consumption trends.

## ⚡ Optimization Strategies

- Suggest load shifting to off-peak hours
- Recommend HVAC and lighting automation schedules
- Identify peak usage windows for predictive maintenance
- Forecast when to rely on renewable sources (e.g., solar)

## 🚀 Future Work

- Integrate LSTM or hybrid ML models
- Add features like occupancy, appliance usage, or solar irradiance
- Real-time dashboard with IoT data
- Deploy as web-based energy management system

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy, Scikit-learn, Matplotlib
- PowerPoint for report/presentation


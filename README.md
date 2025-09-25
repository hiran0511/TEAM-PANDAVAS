# Rainfall Prediction Project 🌧️
This project aims to predict rainfall patterns for Indian cities using historical rainfall data from 2022 to 2024. It demonstrates the use of both statistical and deep learning models for short-term rainfall forecasting.

## 📊 Dataset

The dataset contains daily observations for multiple cities in India with the following columns:

date

city

region

rainfall (mm)

temperature (°C)

humidity (%)

wind speed (km/h)

pressure (hPa)

cloud cover (%)

dew point (°C)

## 🧠 Models Implemented

1. ARIMA (AutoRegressive Integrated Moving Average)

Classical time-series forecasting model.



2. LSTM (Long Short-Term Memory)

Deep learning model for sequential data.

## Description
This project aims to predict rainfall patterns for Indian cities using historical rainfall data from 2022 to 2024. The dataset includes daily observations for multiple cities and contains columns such as date, city, region, rainfall in millimeters, temperature, humidity, wind speed, pressure, cloud cover, and dew point. The project implements both ARIMA, a time-series statistical model, and LSTM, a deep learning model, to forecast rainfall for the next 7 days. Users can select any city in the dataset, and the script will display static rainfall trend plots using Seaborn as well as interactive plots using Plotly. The project also demonstrates data cleaning, visualization, model training, and forecasting in a single, modular Python script. This workflow allows for easy extension to other cities, additional features, or longer forecasting horizons, making it suitable for analyzing seasonal patterns and supporting decision-making in areas affected by rainfall variability.

<img width="1897" height="1004" alt="image" src="https://github.com/user-attachments/assets/bd0abc10-13d4-4944-891a-4b58a8931339" />

<img width="1481" height="829" alt="image" src="https://github.com/user-attachments/assets/2d3f255e-02f2-4d13-af3a-bf762ffc735d" />




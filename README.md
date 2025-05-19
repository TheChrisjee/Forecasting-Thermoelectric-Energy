# Time-Series Thermoelectric Energy Forecasting for Powering Agricultural IoT Sensors
## Project overview
This repository contains code used in the thesis project “Time-Series Thermoelectric Energy Forecasting for Powering Agricultural IoT Sensors.” The goal of the project is to investigate how well short-term meteorological data can predict the hourly energy output of a soil-to-air thermoelectric generator (TEG), and to compare the predictive performance of different machine learning models across agricultural seasons. The analysis includes data preprocessing, feature engineering, model training, and evaluation using Random Forest, XGBoost Regression, and Long Short-Term Memory (LSTM) networks. The repository also includes a subset of the original dataset and seasonal performance evaluations across multiple forecast horizons (30 minutes to 24 hours), as well as feature importance analyses using permutation methods.

## Language
Python

## Algorithms and models
- Random Forest (scikit-learn)
- XGBoost Regression (xgboost)
- LSTM sequence network (TensorFlow / Keras)
- Mean Baselin

## Libraries
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Statsmodels
- Sklearn
- XGBoost
- Tensorflow
- Optuna

## Data Source
The thermoelectric energy dataset (TEG Data) used in this research was acquired from the IEEE DataPort repository, as published by Bancik et al. (2024). The weather data (Weather Data) was purchased by the author from Meteomatics, a commercial weather data provider, through licensed API access. This data is not publicly accessible and is used in accordance with the licensing terms set by Meteomatics. As a result, the full dataset cannot be shared publicly. However, interested parties may contact the author directly with questions or requests related to data access.
https://ieee-dataport.org/documents/temperature-and-energy-output-data-teg-energy-harvesting-prototype
https://www.meteomatics.com/en/download-weather-data/


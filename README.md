# SOLAR POWER TIME SERIES FORECASTING

## PROJECT OVERVIEW
This repository contains code, data, and documentation for a time series analysis project focused on forecasting solar power output. Completed as part of an internship, the project demonstrates how advanced deep learning models can be leveraged for energy prediction and resource planning.

-**Objective**: Predict hourly solar power generation using plant sensor data (temperature, humidity, power readings).

-**Data Processing**: Merging data on nearest timestamps, cleaning missing values, outlier removal, and normalization for deep learning inputs.

-**Feature Engineering**: Created time-based features (hour, minute) alongside environmental variables to capture seasonal and cyclical effects.

-**Modeling**:
**I**Implemented LSTM and GRU architectures with TensorFlow-Keras for sequential data modeling.

**II**Used early stopping and careful train-test partitioning to ensure generalizable results.

**III**Evaluated models using MSE and MAE; best model achieved test MAE of 0.009–0.15 on unseen data.

**IV**Visualization: Performed exploratory analysis (pairplot, boxplots, 3D scatter plots) and visualized loss curves over training epochs.

## Outcomes: 
Produced accurate forecasts of solar power; insights inform operational decision-making and sustainability efforts.

## Tech Stack: 
Python, pandas, NumPy, Scikit-learn, TensorFlow/Keras, Matplotlib, Seaborn

## Project Highlights:

- Robust real-world data cleaning and integration techniques

- Modern deep learning methods for time series forecasting

- Visualization and interpretability for stakeholders

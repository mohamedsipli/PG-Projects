# Stock Market Prediction in PySpark

This project implements a time series forecasting solution using Long Short-Term Memory (LSTM) neural networks to predict stock market trends, integrating PySpark for data handling and feature engineering.

## Project Description

The objective was to build a model capable of forecasting daily stock closing prices. This involved setting up a data pipeline using PySpark to process historical stock data, preparing the data into sequences suitable for LSTM models, constructing and training an LSTM, and evaluating its predictive accuracy.

## Domain

Finance / Time Series Forecasting / Big Data Analytics / Deep Learning

## Key Techniques & Skills Demonstrated

* **Big Data Processing (PySpark):**
    * Data Ingestion from local file (`.csv`).
    * Data Cleaning (Handling Missing Values, Type Casting).
    * Chronological Data Sorting.
    * Feature Engineering: Calculating a 50-day Moving Average using **Spark Window Functions**, demonstrating scalable data transformation.
* **Time Series Analysis & Data Preparation:**
    * Data Scaling (MinMaxScaler) for numerical features.
    * Creation of Time Series Sequences/Windows (using a 60-day look-back period) required for LSTM input.
    * Maintaining Chronological Split for Train/Test sets.
* **Deep Learning (LSTM):**
    * Building a Sequential LSTM model using TensorFlow/Keras, designed for processing sequential data.
    * Model Compilation and Training.
    * Time Series Forecasting (Regression).
* **Model Evaluation:** Assessed forecast accuracy using Regression Metrics:
    * Root Mean Squared Error (RMSE)
    * Mean Absolute Error (MAE).
* **Visualization:** Plotting Actual vs. Predicted stock prices over the test period to visually inspect the forecast quality and trend capture.
* **Libraries:** `PySpark`, `TensorFlow`, `Keras`, `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `findspark`.

## Dataset

Historical AAPL Stock Data (`AAPL_Data.csv`). Contains daily Open, High, Low, Close, Volume, and Date.

## Outcome

Developed and evaluated an LSTM model capable of capturing trends and forecasting stock prices, successfully integrating a PySpark data pipeline for preparing time-series data, including advanced feature engineering like moving averages using Spark Window Functions.

## Project Highlights

* Leveraged **PySpark** for efficient data handling and feature engineering (Moving Average) on time-series data, a key skill for big data environments.
* Applied **LSTM** networks, a powerful deep learning model for time series forecasting, capable of capturing temporal dependencies.
* The approach demonstrates skills transferable to forecasting sequential data in other domains, such as predicting disease trends or demand forecasting.

## Project Context

This project was completed as coursework for the **Big Data Analytics (CAS7A1)** course during the **Master of Science (M.Sc.) in Computer Science** program at the **Department of Computer Applications, National Institute of Technology, Tiruchirappalli** in **Spring 2016**, under the guidance of **Prof. Nicholas**.

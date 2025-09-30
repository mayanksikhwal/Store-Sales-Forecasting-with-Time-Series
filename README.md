# Store-Sales-Forecasting-with-Time-Series

## Project Description

This project focuses on analyzing and forecasting time series data, specifically using the monthly airline passenger dataset. The goal is to understand the components of the time series (trend, seasonality, residuals), make the series stationary through transformations (log transformation, differencing, seasonal differencing), and build forecasting models. The project demonstrates the importance of accounting for seasonality by comparing the performance of a non-seasonal ARIMA model with a Seasonal ARIMA (SARIMA) model.

## Tech Stack

* **Python:** The primary programming language used for the analysis and model building.
* **pandas:** Used for data loading, manipulation, and time series operations.
* **NumPy:** Used for numerical operations, particularly the log transformation.
* **Matplotlib:** Used for creating static visualizations of the time series and model results.
* **Seaborn:** Used for enhancing the aesthetics of the visualizations.
* **statsmodels:** The primary library used for time series analysis, including decomposition, ADF testing, ARIMA, and SARIMA modeling.
* **scikit-learn:** Used for evaluating model performance (RMSE).
* **Google Colab:** The environment where the notebook was developed and executed.
* **Git:** Used to clone the dataset from a GitHub repository.

## How to Run

1. **Open the notebook in Google Colab:** Upload or open the notebook file (`.ipynb`) in your Google Colab environment.
2. **Install dependencies:** Ensure you have the necessary libraries installed. You can install them using pip (refer to the `requirements.txt` file generated earlier).
3. **Run all cells:** Execute all the code cells in the notebook sequentially from top to bottom. This will perform the data loading, exploratory data analysis, stationarity testing, data transformations, model building (ARIMA and SARIMA), forecasting, and evaluation.

## Screenshots

1. **Seasonaally Differenced Time Series (p_value<0.05)**

<img width="676" height="485" alt="image" src="https://github.com/user-attachments/assets/29ab8291-c8dc-4c79-8269-27322ea1228f" />

2. **Non-Seasonal ARIMA Model Forecast (Log transformed Data)**

<img width="878" height="463" alt="image" src="https://github.com/user-attachments/assets/925edcb9-7580-4fc2-9181-1267187828e4" />

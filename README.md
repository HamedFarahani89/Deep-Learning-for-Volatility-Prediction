# Forecasting Volatility Using Deep Learning Models

## Project Overview
This project aims to forecast the volatility of the SPY ETF using deep learning models, particularly focusing on Long Short-Term Memory (LSTM) and Deep Neural Networks (DNN). The model is trained on historical price data, along with computed realized volatility (RV) using log returns.

## Problem Statement
Accurate forecasting of volatility is essential for risk management and trading strategies. This project utilizes deep learning techniques to predict volatility over various timeframes, helping financial analysts and traders make informed decisions.

## Data
- The dataset used in this project is obtained from Yahoo Finance using the `yfinance` library.
- The data includes historical daily close prices of the SPY ETF from 1970 to the present.
- Realized volatility (RV) is calculated using the rolling standard deviation of log returns.

## Metrics
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Percentage Error (MAPE)**
- **R-squared (R²)**
- **Root Mean Squared Percentage Error (RMSPE)**

## Libraries Used
- `yfinance` for financial data retrieval
- `tensorflow` for building deep learning models
- `sklearn` for data preprocessing and model evaluation
- `matplotlib` for data visualization
- `pandas`, `numpy` for data manipulation

## Project Files
- **`data/`**: Raw and processed datasets.
- **`scripts/`**: Python scripts for data preprocessing, model creation, and evaluation.
- **`notebooks/`**: Jupyter notebooks for EDA and model development.
- **`results/`**: Model evaluation metrics and predictions.

## Instructions
1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the scripts or Jupyter notebooks to explore the data, build and evaluate models.

## Results
The model was evaluated using multiple performance metrics, including MAE, RMSE, MAPE, and R². The results show a significant improvement over baseline models, demonstrating the effectiveness of deep learning in forecasting volatility.
## Published 
https://medium.com/@hameddfarahanii/predicting-financial-volatility-with-deep-learning-a-dnn-approach-ba7bddf9f8a0

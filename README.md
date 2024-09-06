# Stock and Cryptocurrency Price Prediction using Cryptocurrency Dynamics and Macroeconomic Indicators

## Overview

This project explores the integration of cryptocurrency dynamics (Bitcoin, Ethereum, etc.) and macroeconomic indicators (GDP, CPI, Unemployment Rate, etc.) to enhance stock price predictions for major U.S. indices like NASDAQ, S&P 500, and DJI. The study applies advanced econometric models and machine learning techniques, including Long Short-Term Memory (LSTM) networks, Random Forest, and Dynamic Conditional Correlation GARCH (DCC-GARCH), to examine correlations and predictive relationships.

## Features

- **Data Sources**: Cryptocurrency data from Yahoo Finance and macroeconomic data from the Federal Reserve Economic Data (FRED).
- **Data Preprocessing**: Interpolation of data frequencies, normalization using Z-score, and handling missing data.
- **Statistical Models**:
  - Multivariate Vector Autoregression (VAR)
  - Dynamic Conditional Correlation GARCH (DCC-GARCH)
- **Machine Learning Models**:
  - Long Short-Term Memory (LSTM) networks
  - Random Forest
  - Feedforward Neural Networks (FNN) using PyTorch
- **Metrics**: Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE), and Directional Accuracy (DA) to evaluate model performance.

## Project Structure

- `Stocks_Crypto_Analysis.ipynb`: Jupyter notebook containing code for data analysis, preprocessing, and model training.
- `Dissertation_Paper_Stock_Prediction.docx`: Comprehensive research paper detailing the methodologies, findings, and future directions of the project.
- `data/`: Folder containing datasets for cryptocurrencies, stock indices, and macroeconomic indicators.

## Key Findings

- **Cryptocurrency-Stock Correlations**: Bitcoin showed a strong positive correlation with the S&P 500, and Ethereum exhibited significant predictive power for NASDAQ.
- **Macroeconomic Impact**: Macroeconomic variables like GDP and CPI positively correlate with stock indices, while unemployment negatively impacts cryptocurrencies.
- **Model Performance**: The LSTM model performed best for capturing the sequential nature of time-series data, with a high Directional Accuracy of 97% for BTC-S&P 500 predictions.

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Stock-Crypto-Prediction.git

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook Stocks_Crypto_Analysis.ipynb

## Future Work

- Explore real-time market trading strategies.
- Enhance prediction accuracy with additional macroeconomic variables.
- Study dynamic relationships during periods of market volatility using regime-switching models.

## References

Syed Farhan Haider, Dissertation Paper: "Enhancing Stock Price Predictions by Integrating Cryptocurrency Dynamics and Macroeconomic Indicators."

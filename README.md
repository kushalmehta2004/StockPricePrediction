# StockPricePrediction

## Overview
This project is designed to predict stock prices based on recent trends using machine learning techniques. The model is trained on historical stock price data fetched from Yahoo Finance and provides various visualizations of the data. Finally, it generates a plot predicting the future price of a selected stock.

## Features
1. Fetch historical stock price data from Yahoo Finance
2. Visualize the stock's historical performance with various plots
3. Train a machine learning model to predict future stock prices
4. Generate and display a plot of the predicted future prices


## Prerequisites
1. Python 3.x
2. Jupyter Notebook
3. Required Python libraries: yfinance, pandas, numpy, matplotlib, scikit-learn
   ```s
   pip install yfinance pandas numpy matplotlib scikit-learn

## Usage
1. Clone the repository:
    ```s
    git clone https://github.com/kushalmehta2004/StockPricePrediction.git
    cd StockPricePrediction
2. Open the Jupyter Notebook:
    ```s
    jupyter notebook LSTM.ipynb
3. Run the Notebook:

    Execute each cell in the notebook to fetch data, visualize historical trends, train the model, and predict future stock prices.

## Notebook Workflow
1. Import Libraries:
    1. Import all necessary Python libraries.

2. Fetch Data:
    1. Fetch historical stock price data from Yahoo Finance.

3. Data Preprocessing:
    1. Clean and prepare the data for analysis.

4. Data Visualization:
    1. Plot different graphs to visualize the stock's historical performance.

5. Model Training:
    1. Train a machine learning model (e.g., Linear Regression, LSTM) on the historical data.

6. Prediction:
    1. Predict future stock prices and plot the results.


## Example Output
After running the notebook, you will see plots visualizing the historical stock prices like moving day average of 100 days, 200 days, and a final plot showing the predicted future prices.

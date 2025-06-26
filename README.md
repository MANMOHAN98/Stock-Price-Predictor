Stock Price Predictor (Linear Regression)

A simple machine learning project that uses *Linear Regression* to predict the *next day's closing stock price* using historical OHLCV data.

 Features

- Loads stock price data from an Excel file
- Uses Open, High, Low, Close, and Volume as input features
- Predicts the *next day’s closing price*
- Visualizes actual vs predicted prices using a line chart
- Saves predictions to a new Excel file

 Dataset

- **synthetic_stock_data.xlsx**  
  Simulated stock data for 200 days with columns:  
  Date, Open, High, Low, Close, Volume

- **stock_predictions_with_actuals.xlsx**  
  Output file that includes both actual and predicted closing prices

 Model

- *Type*: Linear Regression
- *Library*: scikit-learn
- *Features*: Open, High, Low, Close, Volume
- *Target*: Next day's Close price

 Requirements

Install required libraries using:

```bash
pip install pandas numpy matplotlib scikit-learn openpyxl
python predictor_linear_regression.py

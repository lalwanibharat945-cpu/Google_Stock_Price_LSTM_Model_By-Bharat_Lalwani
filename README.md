# Google_Stock_Price_LSTM_Model_By-Bharat_Lalwani
# Google Stock Price Prediction using LSTM

## Project Overview
This project predicts Google stock prices using a Long Short-Term Memory (LSTM) deep learning model.  
The model is trained on historical stock price data to learn time series patterns and forecast future Closing prices.

## Dataset
Dataset Source: Kaggle  
Google Stock Price Training and Test Data

Already given a train and test split
train shape = 1258 rows, 5 columns
test Shape = 20 rows, 5 columns
Columns Given = Date, Close, Open, High, Low, Volume

## Technologies Used
Python  
Pandas  
NumPy  
Matplotlib  
Seaborn
TensorFlow / Keras  
Scikit-learn

## Model Architecture
The model uses an LSTM neural network, which is well-suited to time-series forecasting problems.

Steps:
1. Data preprocessing
2. Feature scaling using MinMaxScaler
3. Creating time sequences
4. Training the LSTM model
5. Predicting stock prices
6. Visualizing predictions vs actual prices

## Results
The model successfully learns the trend of Google stock prices and predicts future price movements.

RMSE: 7.1
MAE: 5.58
R2 Score: 0.65

## Visualization
The project compares predicted prices with actual prices using line charts.

<img width="1134" height="501" alt="image" src="https://github.com/user-attachments/assets/654f8bb3-ac8c-42a2-9740-82ad8082f66f" />




## Author
Bharat Lalwani

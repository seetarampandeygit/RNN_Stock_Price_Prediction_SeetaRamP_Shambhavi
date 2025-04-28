# RNN_Stock_Price_Prediction_SeetaRamP_Shambhavi
This is a RNN Prediction model on Stock Prices of four major tech companies

## OBJECTIVE
The objective of this assignment is to try and predict the stock prices using historical data from four companies IBM (IBM), Google (GOOGL), Amazon (AMZN), and Microsoft (MSFT). 
We use four different companies because they belong to the same sector: Technology. Using data from all four companies may improve the performance of the model. This way, we can capture the broader market sentiment.

## PROBLEM STATEMENT
Given the stock prices of Amazon, Google, IBM, and Microsoft for a set number of days, predict the stock price of these companies after that window.

## BUSINESS VALUE
Data related to stock markets lends itself well to modeling using RNNs due to its sequential nature. 
We can keep track of opening prices, closing prices, highest prices, and so on for a long period of time as these values are generated every working day.
The patterns observed in this data can then be used to predict the future direction in which stock prices are expected to move.
Analyzing this data can be interesting in itself, but it also has a financial incentive as accurate predictions can lead to massive profits.

## Table of Contents
* [Data Loading and Preparation ](#data-loading)
* [Data Preparation](#data-preparation)
* [Model Building and Evaluation](#model-building)
* [Otional_Models](#optional-models)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## Data Understanding
- This is a programming assignment in which we build a RNN python model to predict stock prices.
- Import necessary libraries
- Understanding data and null value treatment
  
## Data Preparation
- Load and pre-process the data
- Training and Testing data
- Visualise sample window sizes
- Analysing sample stocks
  
## Model Building and Evaluation
- SimpleRNN model building, training and evaluation on optimal hyperparameters for a single stock
- LSTM model building, training and evaluation on optimal hyperparameters for a single stock
- Optional SimpleRNN model building, training and evaluation on optimal hyperparameters for multiple stocks
- Oprional LSTM model building, training and evaluation on optimal hyperparameters for multiple stock

 
## Conclusions (Major)
- 1.For both the cases (1- Single stock predictions and 2- Multiple stock predictions):
  - LSTM models were better (<font color = 'Red'> and very close to the actual values <font color = 'Black'>) in predictions with lower 'Mean Squared Error' (MSE).
  - The MSE for LSTM models were almost half of the SimpleRNN models..
    
- GOOGL: The model captures the overall trend well but lags slightly during some volatile periods (noticeable deviations around peaks and valleys).

- MSFT: Predictions are very close to actuals. Slight under/overshoots exist, but overall the model fits extremely well.

- IBM: Model captures broad trends but struggles a bit during high fluctuations (ups and downs around points 20–80).

- AMZN: The model tracks actual prices very closely, even during volatility.
 
  
## Acknowledgements

- This project was inspired by ML-AI couse at UpGrad and IIIT-B
- References: UpGrad and IIIT-B
- This project was based on [RNN Assignment]([[https://learn.upgrad.com/course/5811/segment/60414/369869/1115042/5565470](https://learn.upgrad.com/course/5811/segment/60414/372309/1122070/5597470)]).


## Contact
Created by [@seetarampandeygit] and [@shambhavin31]  - feel free to contact me!

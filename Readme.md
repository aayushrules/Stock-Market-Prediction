# Stock price prediction

All the codes required to run the prediction models are in the Python Notebook file named *'Stock_Market_Prediction_Final.ipynb'* .
The code is divided into following parts.

 1. Install
 2. Libraries
 3. Importing Data
 4. EDA
 5. Pre Processing
 6. Building & Prdeicting LSTM model
 7. Building & predicting LSTM + CNN model


## Install
Run all the codes under Install to install all the necessary packages which are required to run the codes.

## Libraries
This Block imports all the Libraries and methods required for codes to run smoothly.

## Importing Data
The block of codes under this section contains all the codes to download the data

## EDA
This block of codes contains all the code for visualizing the dataset. This block is further divided into :
 1. Google 
 2. Apple 
 3. Microsoft 
 4. Comparing stocks

Google, Apple and Microsoft, contains EDA for the respective companies while 'comparing stocks' contains EDA for comparisons between 3 companies stocks.

## Pre Processing
This portion of code starts preparing datset into training and test dataset.
Mainly has 2 methods namely 'train_test_lstm' and 'train_test_lstm_cnn' which makes train and test dataset for LSTM and LASTM + CNN model respectively.

## Building & Predicting LSTM model
This Block contains all the methods for hyperparameter tuning, building model, predicting and scoring of LSTM model.

## Building & Predicting LSTM model
This Block contains all the methods for hyperparameter tuning, building model, predicting and scoring of LSTM + CNN model.
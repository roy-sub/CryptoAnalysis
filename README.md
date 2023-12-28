# CryptoAnalysis

![banner](https://github.com/roy-sub/CryptoAnalysis/blob/main/Images/banner.jpg)

## Overview

This project focuses on analyzing and predicting the prices of various cryptocurrencies using exploratory data analysis (EDA), transfer learning with time series models, and creating an interactive visualization dashboard.

## Project Structure

The project is organized into three main phases:

### 1. Exploratory Data Analysis (EDA)

- Conducted end-to-end EDA for the following cryptocurrencies:
  - Bitcoin
  - Ethereum
  - Binance Coin
  - Dogecoin
  - Tether
  - Solana
  - Cardano
  - US Dollar Coin
  - Polkadot
  - XRP

- Utilized various statistical and visual techniques to gain insights into the historical data.

- Implemented easy-to-understand data visualizations to represent key trends and patterns.

### 2. Transfer Learning for Price Prediction

Implemented transfer learning using three different models:

#### a. ARIMA (AutoRegressive Integrated Moving Average)

- Applied ARIMA model for time series forecasting of cryptocurrency prices.

#### b. Facebook Prophet

- Utilized Facebook Prophet for time series prediction with additional features.

#### c. LSTM (Long Short-Term Memory)

- Employed LSTM neural networks for deep learning-based price prediction.

### 3. Tableau Dashboard [Click Here](https://public.tableau.com/views/TrackingCryptocurrency/Dashboard3?:language=en-US&:display_count=n&:origin=viz_share_link)
- Scraped the data from [CoinMarketCap](https://coinmarketcap.com/) for the top 5 cryptocurrency

- Pre-processed the data to create a single [Data Source](https://github.com/roy-sub/CryptoAnalysis/blob/main/Tableau%20Visualization/Cryptocurrency%20Tableau%20Visualizationn%20Data%20Source.xlsx) for the Tableau Dashboard

- Created an interactive and easy-to-understand Tableau dashboard to visualize top 5 cryptocurrency daily trading prices, volume and market cap.

- Integrated the predicted prices from the transfer learning models into the dashboard for comprehensive analysis.

![image](https://github.com/roy-sub/CryptoAnalysis/blob/main/Tableau%20Visualization/Tableau%20Visualization.png)

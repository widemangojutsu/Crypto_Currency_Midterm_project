# Cryptocurrency Market Analysis Project

## Introduction
This project focuses on analyzing historical data of the top cryptocurrencies to uncover market trends and predict future price movements. Our aim is to derive meaningful insights from the data and provide a comprehensive understanding of the cryptocurrency market dynamics.
btc close and eth,xrp,ada,bnb using bitfinex exchange from 2018-2023

## Goals
The primary goals of this project are:

To analyze historical price, volume and number of trades data of major cryptocurrencies.
To identify key trends, visualization, and patterns in the cryptocurrency market.
To develop models to forecast future cryptocurrency prices.
To present findings through interactive visualizations and dashboards.

## Technologies Used
Python: For data processing and analysis.
Pandas & NumPy: For data manipulation.
Matplotlib & Seaborn: For data visualization.
Jupyter Notebook: For interactive code execution and presentation.
Tableau: For creating interactive dashboards 

## Data Source
The dataset for this project was obtained from the Binance API. It includes historical price data for five main cryptocurrencies named Bitcoin (BTC), Ethereum (ETH), Binance coin(BNB), XRP (formerly known as Ripple), Cardano(ADA) covering the period from [2018-05-02] to [2024-01-10]. The dataset contains columns for open time, open price, high price, low price, close prices, trading volumes, Close time, Quote asset volume, Number of trades,	Taker buy base asset volume,	Taker buy quote asset volume. The interval of the data is one day which means we are getting those attributes like open price, high price, volume... for each days between the start time and the end date.

## Methodology
Cleaning: The raw data was cleaned in a way that removes missing values and unnecessary data.
Exploratory Data Analysis: Conducting thorough analysis of the data to examine trends, distributions, and correlations.
Visualization: Developing various visualizations to represent findings clearly and intuitively.
Modeling: We were able to conduct a linear regression for each of the crypto currencies by creating a new csv file for each of the crypto currencies and were able to see the influences of each attributes on the dependent variable we chose. 
Creating Dashboard: The last thing we did on the project is interactive dashboards were created in Tableau to visualize our findings.



## Findings

We were able to get a lot of results and finding to highlight some of them, we will provide it as follows.

Number of trades did not have significant effect.
<img width="702" alt="image" src="https://github.com/widemangojutsu/finexBTCUSDTclosemidterm/assets/90173140/946698d4-0c3e-4acc-82cf-b5c2a03e43e0">

We found BTC close and BNB close price had significant pvalue of 0.026
<img width="417" alt="image" src="https://github.com/widemangojutsu/finexBTCUSDTclosemidterm/assets/90173140/4b5aa9c8-a9a3-43e3-b86c-84675123df05">

# Financial Planner

## This Python Notebook contains code to analyze the performance of assets
The goal of the analysis is to determine 1) if the value of the assets covers emergency expenses, and 2) simulate the performance in the futurethe performs a quantitative analysis of the a variety of portfolios for comparison

## Code and Dependencies
This code is to be run on 
`Python 3.7.13`

The following Python Libraries were also imported and used

`import pandas as pd`

`import os`

`import requests`

`from dotenv import load_dotenv`

`import alpaca_trade_api as tradeapi`

`from MCForecastTools import MCSimulation`

`%matplotlib inline`


## Alpaca Trade API
The Alpaca Trade API was used to retrieve price information for both Crypto Currencies and Stocks.

## Monte Carlos Simulation
Monte Carlos Simulations were run using code contained in MCForecastTools.py. This program contains built in fuctions for running the simulations.


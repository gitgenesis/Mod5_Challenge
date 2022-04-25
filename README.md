# Mod5_Challenge
Repository for Module 5 Challenge / Fintech Bootcamp Columbia


# Financial Simulation with APIs / Predicting the Future with Monte Carlo Simulations

## Applicable scenario 
The project entails building a tool to help credit union members evaluate their financial health. Specifically, the credit union board wants the members to be able to do two things. First, they should be able to assess their monthly budgets. Second, they should be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. The chief technology officer (CTO) of the credit union wants you to develop a prototype application to present at its next assembly.

This tool helps you create two financial analysis tools by using a single Jupyter notebook:

    - A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

    - A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

You’ll use the information from the Monte Carlo simulation to answer questions about the portfolio in your Jupyter notebook.

---

# Instructions 
Our Financial analysis includes the following:

- Evaluate the Cryptocurrency Wallet by Using the Requests Library

- Evaluate the Stock and Bond Holdings by Using the Alpaca SDK

- Evaluate the Emergency Fund

- Create the Monte Carlo Simulation

- Analyze the Retirement Portfolio Forecasts

- Forecast Cumulative Returns in 10 Years

---

## Technologies
see requierement.txt

## Programing and financial libraries
Imports and required libraries and dependencies. 

        import os
        import requests
        import json
        import pandas as pd
        from dotenv import load_dotenv
        import alpaca_trade_api as tradeapi
        from MCForecastTools import MCSimulation

        %matplotlib inline

You will need to create an account with Alpaca(https://alpaca.markets/). in order to get an API ID and Secret Key. (see SAMPLE.env for your dotenv file)




---

## Contributors

Drissa Compaore email: misterdrissa@gmail.com

## License

This code is created for educational purposes, and it usage therein has no commerical application. It is designated as free-use thusly, and shall remain as such.

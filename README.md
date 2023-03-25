# financial-planner-API

<img src="./Images/financial-planner.png" alt="isolated" width="700"/>

## Project Objective

Two financial analysis tools created in Jupyter notebook

1. A financial planner for emergencies. The members will be able to use this tool to visualise their current savings. The members can then determine if they have enough reserves for an emergency fund.

2. A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

## Part 1: Create a Financial Planner for Emergencies

To develop the prototype, assume the following:

- The average monthly household income for each credit union member is $12,000.

- Each credit union member has a savings portfolio that consists of a cryptocurrency wallet, stocks, and bonds.
- use the valuations for the cryptocurrency wallet and for the stock and bond portions of the portfolio to determine if the credit union member has enough savings to build an emergency fund into their financial plan.


## Part 2: Create a Financial Planner for Retirement

We’ll use the Alpaca API to get historical closing prices for a retirement portfolio. We’ll then run Monte Carlo simulations to forecast the portfolio performance 30 years, 10 years, 5 years from now. 

- Create the Monte Carlo Simulation
- Analyze the Retirement Portfolio Forecasts

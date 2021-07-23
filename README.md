# Homework_5_APIs
#### This project is completed for Fintech Bootcamp Fall 2021.
#### Vincent Xin Wen

## Homework Background

You decided to start a FinTech consultancy firm, and you want to make a difference by working on projects with high social impact in local communities. You just won your first contract to help one of the biggest credit unions in your area. They want to create a tool that helps their members enhance their financial health. The Chief Technology Officer (CTO) of the credit union asked you to develop a prototype application to demo in the next credit union assembly.
The credit union board wants to allow the union's members to assess their monthly personal finances, and also be able to forecast a reasonably good retirement plan based on cryptocurrencies, stocks, and bonds.

In this homework activity, you will use all the skills you have learned until now - focusing on using APIs as part of the technical solution - to create two financial analysis tools.
The first will be a personal finance planner that will allow users to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money as an emergency fund.

The second tool will be a retirement planning tool that will use the Alpaca API to fetch historical closing prices for a retirement portfolio composed of stocks and bonds, then run Monte Carlo simulations to project the portfolio performance at 30 years. You will then use the Monte Carlo data to calculate the expected portfolio returns given a specific initial investment amount.

## Resources

This homework will utilize two APIs:

* The **Alpaca Markets API** will be used to pull historical stocks and bonds information.  
    
* The **Alternative Free Crypto API** will be used to retrieve Bitcoin and Ethereum prices.

The documentation for these APIs can be found via the following links:

* [Free Crypto API Documentation](https://alternative.me/crypto/api/)

* [AlpacaDOCS](https://alpaca.markets/docs/)

## Conculsion
Personal Finance Planner

using our Personal Finance Planner we can create a portfolio of crypto currency and stock share and find the value of a specific date. and determine the Savings Health of the family, for example, if a house hold monthly_income = 12000, after buying 1.2 btc and 5.3 eth and 200 egg shares and 50 spy shares, on 2021-06-22, their portfoilo is worth crypto = 50309.018. shares = 44175.000. doing pretty well.

Retirement Planning

we used monte carlo simulation to create and test a retirement plan with initial investment of 20,000. the expected portfolio return in dollars at the 95% lower and upper confidence intervals between 408819.07 dollars and 2751159.01 dollars

the expected portfolio return at the 95% lower and upper confidence intervals based on a 50% increase in the initial investment is between 613228.6 dollars and 4126738.52 dollars.

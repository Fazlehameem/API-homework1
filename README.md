# Financial Planning



## Background

I decided to start a FinTech consultancy firm, and wanted to make a difference by working on projects with high social impact in local communities. I just won our first contract to help one of the biggest credit unions in your area. They want to create a tool that helps their members enhance their financial health. The Chief Technology Officer (CTO) of the credit union requested a prototype application to demo in the next credit union assembly.

The credit union board wants to allow the union's members to assess their monthly personal finances, and also be able to forecast a reasonably good retirement plan based on cryptocurrencies, stocks, and bonds.


The finance planner will allow users to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money as an emergency fund.

The second tool will be a retirement planning tool that will use the Alpaca API to fetch historical closing prices for a retirement portfolio composed of stocks and bonds, then run Monte Carlo simulations to project the portfolio performance at 30 years. I will use the Monte Carlo data to calculate the expected portfolio returns given a specific initial investment amount.

---

### Files

* [Personal Finance Planner starter code](Starter_Code/financial-planner.ipynb)

* [MCForecastTools toolkit](Starter_Code/MCForecastTools.py)

---

### Resources

This homework will utilize two APIs:

* The **Alpaca Markets API** will be used to pull historical stocks and bonds information.  
    
* The **Alternative Free Crypto API** will be used to retrieve Bitcoin and Ethereum prices.

The documentation for these APIs can be found via the following links:

* [Free Crypto API Documentation](https://alternative.me/crypto/api/)

* [AlpacaDOCS](https://alpaca.markets/docs/)
---

## Instructions

### Part 1 - Personal Finance Planner

#### Collect Crypto Prices Using the `requests` Library

#### Collect Investments Data Using Alpaca: `SPY` (stocks) and `AGG` (bonds)

#### Savings Health Analysis


### Part 2 - Retirement Planning


#### Monte Carlo Simulation


#### Retirement Analysis


---

### Hints and Considerations

* To allow for quicker work during the Monte Carlo simulation, start out by running `100` simulations for one year of returns, and when you have the code worked out, run the full `500` simulations for `30` years. 

* Remember to add the `.env` files to the `.gitignore` configuration to avoid exposing your API keys in your GitHub repository.

* A `.gitignore` file contains file names and extensions of files that you don't want pushed to your repository. For more information on how a `gitignore` works, you can read the documentation [here](https://docs.github.com/en/github/using-git/ignoring-files).

---


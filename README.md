# Crypto-Trading-and-Analysis

### Objective
I want to perform exploratory data analysis on the cryptocurrency market to compare the historical returns and to better understand the relationship between several large market cap coins. After I have a good understanding of the historical returns of the coins, I will test and optimize a trading strategy that can be implemented into an algorithmic trading bot.

### The Exploratory Data Analysis notebook details the process I used to:
1. Scrape pricing data from the Poloniex exchange
2. Create visualizations of the historical returns of several cryptocurrencies
3. Implement common statistical methods, including linear regression and correlation, to analyze the relationship between Ethereum and Ethereum Classic

### The Trading Strategy notebook details the process I used to:
1. Scrape exchange rate data
2. Formulate a trading strategy using a simple moving average crossover
3. Backtest that strategy using historical data
4. Evaluate and determine the values that could potentially yield the best returns
#### Conlusions:
If this strategy was used for BTC and XRP and implemented in an algorithmic trading bot, a trader could've had a return of at least 200000% if they implemented it sometime in early 2017 (returns as of Jan 2018).
In a future project I will code an algorithmic trading bot that implements this strategy and interacts with an exchange's API to send buy and sell signals.
#### Recommendations:
These incredible returns are caused by a number of factors, including the alt coin boom, XRP's boom in particular, and assumptions that there are no transaction costs.
This strategy worked well with historical data, but past performance is not indicative of future results.

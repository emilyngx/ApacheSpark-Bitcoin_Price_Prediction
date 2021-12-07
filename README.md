# BTCUSDT price prediction
## About this project
This is a group project of Emily Nguyen and Nhi Tran.

We expect the outcome to be a plotting chart of the training model showing the Bitcoin price trend in the next 1 hour. We will compare RSME rate to the standard deviation of the dependent variables and generate visualizations for the BTC/USDT prices with Moving Average and Bollinger Band, as well as an automated indicator instructed by the model.

## Data
The data set used in this project was retrieved from AWSmarketplace’s “Binance Crypto Currency | Crypto Data Download” product provided by Rearc. The data shows Bitcoin prices based on Tether (USDT). Tether is a stable coin which is a type of cryptocurrency aiming to keep cryptocurrency values stable. USDT is popular due to its pegging to fiat currency USD.

In details, the data set includes the Bitcoin/Tetherus (BTC/USDT) pair prices from 08/17/2017 4AM to 06/24/2021 12AM, with 36,399 rows and 9 columns indicating these variable measures:
* Date and Time: Date and time of price with time interval of 1 hour
* Open: BTC/USDT price first trade upon the start of the time period
* Close: BTC/USDT price at the end of the time period
* High: Highest BTC/USDT price during the 1 hour time period
* Low: Lowest BTC/USDT price during the 1 hour time period
* Volume BTC: Measure of how much of a given BTC has traded in the time
period
* Volume USDT: Measure of how much of a given USDT has traded in
the time period
* Tradecount: Number of trades

### Descriptive Statistics
![alt text](https://github.com/emilyngx/Big_Data/blob/main/images/0.png)
This table provides basic information such as count, mean, standard deviation, minimum value, percentiles, and maximum value of all the variables.

### Histogram of BTCUSDT prices
![alt text](https://github.com/emilyngx/Big_Data/blob/main/images/1.png)
The grey line shows the close price of BTC/USDT during the time period. Each blue column represents the BTC volume of each specific date and time. By observing the above chart, we can see BTC has been through some cycles.

## Method of Analysis
* Regression and Classification
* Dependent variable: Closing price of the next 1 hour period
* Independent variable: Volume BTC, Volume USDT, net change, MA, RSI and the Ichimoku computed values,...

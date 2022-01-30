# Crypto Arbitrage

Welcome to my Crypto Arbitrage, here we will be compairing Bitcoin data from two different trading platforms: Bitstamp and Coinbase.

COLLECT THE DATA!

Using the Pandas read_csv function and the Path module, import the data from bitstamp.csv file, and create a DataFrame called bitstamp. Set the DatetimeIndex as the Timestamp column, and be sure to parse and format the dates.

Use the head (and/or the tail) function to confirm that Pandas properly imported the data.

Repeat Steps 1 and 2 for coinbase.csv file.

PREPARE THE DATA!

For the bitstamp DataFrame, replace or drop all NaN, or missing, values in the DataFrame.

Use the str.replace function to remove the dollar signs ($) from the values in the Close column.

Convert the data type of the Close column to a float.

Review the data for duplicated values, and drop them if necessary.

Repeat Steps 1–4 for the coinbase DataFrame.

ANALYZE THE DATA!

Choose the columns of data on which to focus your analysis.

Get the summary statistics and plot the data.

Focus your analysis on specific dates.

Calculate the arbitrage profits.

FOCUS OUR ANALYSIS ON SPECIFI DATES!

Select three dates to evaluate for arbitrage profitability. Choose one date that’s early in the dataset, one from the middle of the dataset, and one from the later part of the time period.

For each of the three dates, generate the summary statistics and then create a box plot. This big-picture view is meant to help you gain a better understanding of the data before you perform your arbitrage calculations.

CALCULATE THE ARBITRAGE PROFITS!

For each of the three dates, measure the arbitrage spread between the two exchanges by subtracting the lower-priced exchange from the higher-priced one. Then use a conditional statement to generate the summary statistics for each arbitrage_spread DataFrame, where the spread is greater than zero.

For each of the three dates, calculate the spread returns. To do so, divide the instances that have a positive arbitrage spread (that is, a spread greater than zero) by the price of Bitcoin from the exchange you’re buying on (that is, the lower-priced exchange). Review the resulting DataFrame.

For each of the three dates, narrow down your trading opportunities even further. To do so, determine the number of times your trades with positive returns exceed the 1% minimum threshold that you need to cover your costs.

Generate the summary statistics of your spread returns that are greater than 1%. How do the average returns compare among the three dates?

For each of the three dates, calculate the potential profit, in dollars, per trade. To do so, multiply the spread returns that were greater than 1% by the cost of what was purchased. Make sure to drop any missing values from the resulting DataFrame.

Generate the summary statistics, and plot the results for each of the three DataFrames.

Calculate the potential arbitrage profits that you can make on each day. To do so, sum the elements in the profit_per_trade DataFrame.

Using the cumsum function, plot the cumulative sum of each of the three DataFrames.


THANK YOU FOR USUING MY CRYPTO ARBITRAGE TOOL!

HAPPY CODING!

-----------------------------------------------------------------------

## Contributors

Sean Harrington-
    Linkedin: www.linkedin.com/in/sean-harrington16

-----------------------------------------------------------------------

## License

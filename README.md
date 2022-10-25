# Stock-Market-Prediction
To predict whether a stock is worth buying depending on 77 various factors such a opening & closing value, company name, etc.

PURPOSE
Non-professional investors usually try to find an interesting stock among many from an index (like Standard and Poor's 500, Nasdaq, etc). They wish to ensure that it will give them good returns.
Our project is a predictive model which uses a binary classifier, whether a stock is worth buying or not.

CONTEXT
Most projects I found to predict the price of a stock (investing) is targeted to find the price for the following day, and just for that stock.
But in practical terms, people like to find the best stock to buy from a index, and wait some days expecting to get a price increase from this investment.

CONTENT OF THE DATASET
Rows are grouped by companies and their age (from newer to older) to a common date.
The first column is the company. Next ones are the age, market, date (separated by year, month, day, hour, minute), volume of shares, several traditional prices from that stock (close, open, highest…), some statistics from price and volume, and target.
The target is mainly defined as 1 when close price increases a 15% in 20 days (market days). The detailed definition of the target is:
1: when price increases a 15% in 20 market days, with no loss higher than a 10% from the starting price in every day in that period.
0: otherwise.

ALGORITHMS
Decision Tree:
Decision Tree is the most powerful and popular tool for classification and prediction.
It is a flowchart-like tree structure, where each internal node denotes a test on an attribute, each branch represents an outcome of the test, and each leaf node (terminal node) holds a class label. 

PYTHON MODULES
1) pandas
2) sklearn
3) numpy

ACCURACY
95.2727804 %

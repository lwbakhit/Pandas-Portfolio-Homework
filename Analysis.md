# Which portfolios are riskier than the S&P 500?

cumulative_returns.std()
SOROS FUND MANAGEMENT LLC       4.141413
PAULSON & CO.INC.               0.857016
TIGER GLOBAL MANAGEMENT LLC    11.642719
BERKSHIRE HATHAWAY INC          1.016634
Algo 1                          3.925305
Algo 2                          8.790255
S&P 500                         1.986530

Taking the standard deviation chart above we can see that the only individual companies that are less risky than the S&P 500 are Berkshire Hathaway Inc and Paulson & CO Inc because they have a smaller standard deviation than the S&P.  If we were to look at each Portfolio as a whole then all given Portfolios are considered riskier than the S&P 500.


# Does the risk increase for each of the portfolios at the same time risk increases in the S&P?

Looking at the graph in the python file, you will see that all of the portfolios follow the same trends in terms of gains/losses. Due to the correlation within the graph, it is safe to say the portfolios' risk increases along with the S&P500. 

# Which returns most closely mimic the S&P?
Algo 2 most closely mimics the S&P 500. 

# Does the portfolio seem sensitive to movements in the S&P 500?
Looking at the graph of the rolling 60-day beta for Algo 2, I can see there is high volatility within a short time period. Based on this 60 day period, the portfolio is sensitive to movements in the S&P 500. 

# On the basis of this performance metric, do our algo strategies outperform both 'the market' and the whales? 

Algo one has a significantly higher sharper ratio than any other competitor on the chart, meaning that it has better returns given the amount of risk taken on compared to the other companies. If we look at the Algo strategies combined they would also outperform the "whales" and the "market".

# How does your portfolio fair?
My "custom" portfolio outperforms the market and other portfolios in the given timeframe, however its' volatility is significantly higher. Its Sharpe Ratio is in the middle making it an average risk when compared to the other portfolios. Overall when compared to the S&P500 and the other portfolios, the returns are higher, but would be for the more aggressive investor that doesn't mind high volatility along the way. 
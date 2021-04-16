# Pairs_Trading
Involves implementation of a statistical arbitrage strategy, by identifying pairs of stocks that move together, and taking advantage of the spread divergence

Pairs trading is a stat arb strategy
Step 1: Identify pairs of stocks that move together based on metrics such as cointegration, sum of squared deviation
Step 2: Calculate the z spread between the stocks and enter the trade if the absolute value of z is greater than a threshold. The z spread's mean and standard deviation are based on historical observations.
Step 3: Setup a stoploss if the stocks diverge too much
Step 4: Calculate metrics such as max drawdown, sharpe ratio etc to gauge the performance of the portfolio

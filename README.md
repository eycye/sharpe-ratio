# sharpe-ratio

Calculating the reward-to-variability ratio, introduced by William Sharpe in 1966, of Facebook and Amazon stocks in 2016. S&P 500 data as benchmark.

1. Daily stock returns: % change in value from one day to next ( `stock_returns` and `sp_returns`)
2. Compare Facebook and Amazon's respective difference in daily returns w.r.t. those of S&P 500, namely `excess_returns`
3. Calculate `average` and `std` of Facebook and Amazon's `excess_returns`
4. `daily_sharpe_ratio = avg_excess_return.div(sd_excess_return)`, *annualize* by `sqrt(252)`, 252 being the number of tradings days
5. Amazon's Sharpe Ratio was 2x that of Facebook's due to its higher returns. Cool insight into optimal investment decisions back in 2016.

# Ichimoku Cloud Trading Strategy (Beginner Version)

![Cover Image](https://github.com/Brianhulela/ichimoku_cloud_trading_strategy/blob/master/figures/AAPL_ichimoku_cloud.png)

A beginner-friendly trend-following strategy using the **Ichimoku Cloud**. This strategy generates **buy signals** when the price closes above the cloud and the **Tenkan-sen crosses above the Kijun-sen**, and **sells** when the price closes below the cloud.

I go into the details of this implementation in a [Medium Article](https://medium.com/insiderfinance/i-tried-the-ichimoku-cloud-trading-strategy-and-this-is-what-happened-70fafc998a7c).

I highly recommend you also check out the [Bayesian Optimized Version of this strategy](https://github.com/Brianhulela?tab=repositories).

## Features

- **Ichimoku Lines:** Tenkan-sen, Kijun-sen, Senkou Span A & B, Chikou Span.
- **Signal Generation:** Based on cloud position and Tenkan/Kijun crossover.
- **Trade Identification:** Clean buy → sell pairs to avoid overlapping positions.
- **Backtesting:** Simulates a $10,000 portfolio, tracks equity curve, total return, and max drawdown.
- **Visualizations:**
  - Price with Ichimoku Cloud
  - Buy and sell signals on the price chart
  - Equity curve over time
  - Drawdowns and max drawdown highlighted

This strategy illustrates how a **single technical indicator** can provide actionable signals while showing the risk-reward dynamics of trend-following trading.

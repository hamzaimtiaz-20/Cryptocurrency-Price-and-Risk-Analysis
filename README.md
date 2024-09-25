# Cryptocurrency-Price-and-Risk-Analysis: A Study of the Top 10 by Market Cap (excl. stablecoins) (2022-2024)
### The goal of this project is to perform a comprehensive analysis of the price performance, volatility, and risk characteristics of the top 10 cryptocurrencies by market cap (excl. stablecoins) — Bitcoin (BTC), Ethereum (ETH), Binance Coin (BNB), Solana (SOL), Ripple (XRP), and Dogecoin (DOGE) — from January 2022 to August 2024. By investigating historical price data, returns, and inter-crypto correlations, this analysis aims to provide insights into the volatility, returns distribution, and risk dynamics of each asset and offer recommendations for constructing a well-balanced cryptocurrency portfolio.

## Data Source
Historical price data for Bitcoin (BTC), Ethereum (ETH), Binance Coin (BNB), Solana (SOL), Ripple (XRP), and Dogecoin (DOGE) was sourced using the yfinance library in Python. yfinance is a widely-used library that enables users to access historical market data from Yahoo Finance.

![1  data source](https://github.com/user-attachments/assets/e99db71d-bac4-4d48-8b0a-a187528dfb59)

## Insights Summary
### To analyze the price performance and risk dynamics of each asset the focus went to the following key areas:
- Returns
- Volatility
- Correlations
- Risk-Adjusted Returns

### Returns
- SOL experienced the most significant mean daily returns.
- BTC exhibited substantial growth, trailed by DOGE, BNB, and XRP.
- ETH had the least significant mean daily returns.

  
### Volatility
- SOL exhibited the highest volatility (0.28) followed closely by DOGE (0.24), potentially indicating higher risk.
- BTC displayed the lowest volatility (0.15), suggesting lower risk.
- ETH, BNB, and XRP demonstrated varying levels of volatility.

### Correlations
- The correlation heatmap shows BTC and ETH have the highest positive correlation, indicating their price movements tend to follow similar trends.
- SOL, BNB, XRP, and DOGE exhibit the strongest correlation with ETH, indicating that ETH may be a leading indicator for these altcoins

### Risk-Adjusted Returns
- SOL has the highest Sharpe Ratio at 0.360890, indicating the most favorable risk-adjusted returns among the cryptocurrencies analyzed, suggesting it offers the best trade-off between risk and reward in this dataset.
- BTC follows with a Sharpe Ratio of 0.350683, reflecting relatively high risk-adjusted returns, which reinforces its reputation as a stable and potentially rewarding investment.
- BNB and DOGE have moderate Sharpe Ratios of 0.261249 and 0.188223, respectively, suggesting they offer lower risk-adjusted returns compared to BTC and SOL.
- XRP and ETH have lower Sharpe Ratios of 0.167882 and 0.103561, indicating that their risk-adjusted returns are less favorable, with ETH showing the least favorable profile.

## Recommendations
- Prioritize Stability: Allocating a significant portion of the portfolio to an established blue-chip cryptocurrency in Bitcoin (BTC) can be beneficial. Its higher market capitalization and lower volatility (0.15), coupled with favorable risk-adjusted returns (0.350683), can help mitigate the high risk associated with the volatile cryptocurrency market.
- Balance with Growth Opportunities: While focusing on blue-chip cryptocurrencies for stability, it’s also valuable to balance the portfolio with smaller or emerging assets among the top 10 by market cap that have higher potential for returns such as SOL or DOGE. This approach allows you to capture growth potential while maintaining overall portfolio stability, achieving a blend of stability and growth.
- Monitor Correlations: Regularly assess correlations between cryptocurrencies to identify potential diversification opportunities and avoid excessive concentration.
  
## Presentation Sample
The presentation created walks through the insights and recommendations above and can be found [here](https://docs.google.com/presentation/d/16KD2TspWldCATwapCEvcSeeKYP_ny0vU/edit?usp=sharing&ouid=105728372417079201864&rtpof=true&sd=true). Some extracts are presented below for easy viewing.

![volatility](https://github.com/user-attachments/assets/6663c372-c9b2-43e8-8970-d8c51058903c)
![correlation](https://github.com/user-attachments/assets/d06235bb-4fc2-4754-b345-b78a623ff3f6)
![recommendations](https://github.com/user-attachments/assets/fd11050e-5c16-4406-bbac-2652e6f06ea6)

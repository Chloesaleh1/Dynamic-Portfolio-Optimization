# Dynamic Portfolio Optimization

This project involves the development of a portfolio optimization model utilizing historical S&P 500 stock price data. Our objective is to enhance investment strategies by leveraging technical indicators, machine learning clustering, and modern portfolio theory principles. The workflow includes:

1. **Data Acquisition**: Downloading historical price data for stocks listed in the S&P 500 index.
2. **Feature Engineering**: Calculating a variety of technical indicators for each stock and aggregating them on a monthly level, focusing on the 150 most liquid stocks to ensure robustness and trading feasibility.
3. **Return Calculation**: Computing monthly returns for stocks across different time horizons, which are then included as features to provide a comprehensive view of each stock's performance trends.
4. **Risk Modeling**: Integrating Fama-French Factors into the analysis by calculating rolling factor betas for each stock to capture their market sensitivities.
5. **Asset Clustering**: Implementing a K-means clustering algorithm each month to group similar assets based on their features, facilitating the identification of correlated behaviors and diversification opportunities.
6. **Portfolio Construction**: Selecting assets based on their cluster grouping each month and forming a diversified portfolio using Efficient Frontier analysis to maximize the Sharpe ratio, indicating the most efficient risk-return trade-off.
7. **Performance Visualization**: Comparing the optimized portfolio's returns against the benchmark S&P 500 returns to assess the model's effectiveness in outperforming market averages.

# Trade-Ahead
Problem Statement:
Context

The stock market has consistently proven to be a good place to invest in and save for the future. There are a lot of compelling reasons to invest in stocks. It can help in fighting inflation, create wealth, and also provides some tax benefits. Good steady returns on investments over a long period of time can also grow a lot more than seems possible. Also, thanks to the power of compound interest, the earlier one starts investing, the larger the corpus one can have for retirement. Overall, investing in stocks can help meet life's financial aspirations.

It is important to maintain a diversified portfolio when investing in stocks in order to maximise earnings under any market condition. Having a diversified portfolio tends to yield higher returns and face lower risk by tempering potential losses when the market is down. It is often easy to get lost in a sea of financial metrics to analyze while determining the worth of a stock, and doing the same for a multitude of stocks to identify the right picks for an individual can be a tedious task. By doing a cluster analysis, one can identify stocks that exhibit similar characteristics and ones which exhibit minimum correlation. This will help investors better analyze stocks across different market segments and help protect against risks that could make the portfolio vulnerable to losses.

Objective:

Trade&Ahead is a financial consultancy firm who provide their customers with personalized investment strategies. They have hired you as a Data Scientist and provided you with data comprising stock price and some financial indicators for a few companies listed under the New York Stock Exchange. They have assigned you the tasks of analyzing the data, grouping the stocks based on the attributes provided, and sharing insights about the characteristics of each group.


Results and Findings:

K-Means Clustering Results

Cluster 0: Consisted of 277 companies with moderate stock prices and low volatility, experiencing an average 5% price increase. These companies had low cash ratios and net incomes, along with low P/E ratios and outstanding shares.

Cluster 1: Included 11 companies characterized by low stock prices and volatility, with a 6% average price rise. They exhibited low cash ratios but high net incomes and outstanding shares, along with low P/E ratios.

Cluster 2: Comprising 27 companies, this cluster had low stock prices and high volatility, with a 15% average price drop. These companies showed low cash ratios, negative net incomes, high P/E ratios, and low outstanding shares.

Cluster 3: Encompassed 25 companies with high stock prices and moderate volatility, experiencing a 13.5% average price increase. They had high cash ratios, low positive net incomes, moderate P/E ratios, and low to moderate outstanding shares.

Hierarchical Clustering Results

Ward Linkage Method: Utilizing the Ward linkage method with Euclidean distance, four clusters were identified:
Cluster 0: 29 companies with low stock prices and high volatility, experiencing an 11% average price drop. These companies had low cash ratios and negative net incomes, high P/E ratios, and low outstanding shares.
Cluster 1: 15 companies with high stock prices and moderate volatility, witnessing a 10.5% average price rise. They exhibited high cash ratios and low positive net incomes, high P/E ratios, and low outstanding shares.
Cluster 2: 11 companies characterized by low stock prices and low volatility, with a 6% average price drop. These companies had moderate cash ratios and high positive net incomes, low P/E ratios, and high outstanding shares.
Cluster 3: 285 companies with moderate stock prices and low volatility, experiencing a 5% average price rise. They had moderate cash ratios and positive net incomes, moderate P/E ratios, and low outstanding shares.
Key Takeaways:

Diversification Strategy: Investors can use these clusters to build diversified portfolios by selecting stocks from different clusters, thereby minimizing risk and maximizing potential returns.
Risk Assessment: Clusters with high volatility and negative financial indicators (e.g., Cluster 2) may indicate higher risk investments, suitable for risk-tolerant investors seeking potential high returns.
Stable Investments: Clusters with low volatility and positive financial indicators (e.g., Cluster 1) may represent stable investment opportunities, appealing to conservative investors seeking steady growth.
Sector Analysis: Further analysis of the sectors represented within each cluster can provide insights into industry-specific trends and opportunities.

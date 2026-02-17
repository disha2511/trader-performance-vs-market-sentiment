# trader-performance-vs-market-sentiment
Project Overview
This project explores the relationship between market sentiment and trading performance using historical execution data and the Bitcoin Fear & Greed Index.
\Key goals:
Understand how trader profitability changes across sentiment regimes.
Identify behavioral patterns such as trade size and frequency shifts.
Segment traders into meaningful groups for deeper analysis.

Propose practical strategy recommendations based on findings.
Tech Stack:
Python
Pandas & NumPy
Matplotlib & Seaborn
Google Colab

Dataset Description:
1)Market Sentiment Dataset
Daily Fear/Greed classification
2️) Hyperliquid Trader Dataset
Account activity, trade size, direction, execution price, and Closed PnL.

Methodology:
1)Parsed timestamps and aligned datasets at daily level.
2)Cleaned and validated merged data.
3)Engineered behavioral features:
 *Trade size segments
 *Trade frequency segments
 *Long/short activity metrics
4)Performed sentiment-based performance analysis and visualization.

Key Insights:
1)Larger trade-size segments consistently achieve higher average PnL.
2)Extreme Fear negatively impacts small traders more than larger traders.
3)Trading behavior (trade size and activity level) shifts with sentiment regimes.
4)Behavioral segmentation provides clearer insight than aggregate averages.

Strategy Recommendations:
1)Adaptive risk management based on sentiment conditions.
2)Segment-based trading rules for high vs low frequency traders.
3)Sentiment-aware position sizing to improve risk-adjusted returns

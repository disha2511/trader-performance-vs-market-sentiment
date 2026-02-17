
🚀 Project Overview

This project explores the relationship between market sentiment and trading performance using historical execution data and the Bitcoin Fear & Greed Index.

Key goals:

Understand how trader profitability changes across sentiment regimes.

Identify behavioral patterns such as trade size and frequency shifts.

Segment traders into meaningful groups for deeper analysis.

Propose practical strategy recommendations based on findings.

🧰 Tech Stack

Python

Pandas & NumPy

Matplotlib & Seaborn

Google Colab / Jupyter Notebook

📂 Dataset Description

1️⃣ Market Sentiment Dataset

Daily Fear/Greed classification.

2️⃣ Hyperliquid Trader Dataset

Account activity, trade size, direction, execution price, and Closed PnL.

⚙️ Methodology

Parsed timestamps and aligned datasets at daily level.

Cleaned and validated merged data.

Engineered behavioral features:

Trade size segments

Trade frequency segments

Long/short activity metrics

Performed sentiment-based performance analysis and visualization.

📊 Key Insights

Larger trade-size segments consistently achieve higher average PnL.

Extreme Fear negatively impacts small traders more than larger traders.

Trading behavior (trade size and activity level) shifts with sentiment regimes.

Behavioral segmentation provides clearer insight than aggregate averages.

🧠 Strategy Recommendations

Adaptive risk management based on sentiment conditions.

Segment-based trading rules for high vs low frequency traders.

Sentiment-aware position sizing to improve risk-adjusted returns.

▶️ How to Run

Open Trader_Performance_vs_Sentiment.ipynb

Run all cells sequentially.

Charts and insights will be generated automatically.

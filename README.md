rader Performance vs Market Sentiment Analysis
🔎 Project Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear/Greed Index) and trader performance on Hyperliquid.
The objective is to identify behavioral changes across sentiment regimes and extract actionable strategy insights.
This project was completed as part of the Data Science Intern assignment.

🎯 Objectives
Measure how trader performance varies between Fear and Greed days
Analyze behavioral changes in leverage, trade frequency, and position bias
Segment traders into behavioral groups
Propose data-driven strategy recommendations

📂 Datasets
1️⃣ Bitcoin Market Sentiment Dataset
Date
Classification (Fear / Greed)

2️⃣ Hyperliquid Historical Trader Data
account
symbol
execution price
size
side
time
closedPnL
leverage
event
start position

🛠 Data Preparation
Checked dataset dimensions (rows & columns)
Removed duplicates
Handled missing values
Converted timestamps to daily format
Merged datasets on Date
Created derived metrics:

📌 Engineered Features
Daily PnL per trader
Win rate
Average trade size
Leverage distribution
Trades per day
Long/Short ratio
Drawdown proxy

📊 Exploratory Analysis
1️⃣ Performance vs Sentiment
Compared average PnL during Fear vs Greed
Compared win rates
Evaluated volatility differences

2️⃣ Behavioral Changes
Trade frequency by sentiment
Leverage changes across regimes
Long vs Short positioning bias

3️⃣ Trader Segmentation
Identified behavioral groups:
High leverage vs Low leverage traders
Frequent vs Infrequent traders
Consistent vs Inconsistent performers

💡 Key Insights
Higher volatility in trader PnL during Fear periods
Increased trade frequency during Greed sentiment
High-leverage traders experience larger drawdowns
Consistent low-leverage traders show more stable returns

🚀 Strategy Recommendations
Reduce leverage exposure during Fear sentiment periods.
Increase trade frequency selectively during Greed days with controlled position sizing.
Favor low-to-moderate leverage strategies for long-term consistency.

🧠 (Optional) Predictive Modeling
If implemented:
Built simple classification model to predict next-day profitability bucket
Used sentiment + behavioral features
Evaluated using accuracy / F1-score

🛠 Tech Stack
Python
Pandas
NumPy
Matplotlib

Seaborn

Scikit-learn

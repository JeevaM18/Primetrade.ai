# Primetrade.ai

# 📊 Trader Performance vs. Market Sentiment

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance from Hyperliquid. It identifies behavioral patterns, builds sentiment-aware profitability scores, and extracts insights that can guide smarter trading strategies.

---

## 🔍 Objectives

- Explore how fear or greed in the market correlates with trader profitability
- Engineer a sentiment-weighted profitability metric
- Visualize trends and statistical relationships
- Generate actionable insights for strategic trading
- (Bonus) Use clustering and rolling/lags to uncover hidden behavioral patterns

---

## 📁 Project Structure

project/

├── trader_sentiment_analysis.py # 🔧 Main script for data processing, scoring, visualization

├── final_insights.txt # 📄 Strategy insights and statistical summary

├── profitability_by_sentiment.png # 📊 Avg. profitability score by sentiment

├── pnl_distribution.png # 📊 PnL distribution by sentiment

├── README.md # 📘 This documentation

├── requirements.txt # ⚙️ Required Python libraries

│

├── enhanced_analysis/ # 🧪advanced visualizations

│ ├── rolling_trends.png

│ ├── scatter_profitability_sentiment.png

│ ├── win_rate_by_sentiment.png

│ └── heatmap_sentiment_cluster.png



## Key Insights
 Traders often perform better during “Fear” phases than “Greed”
 Sentiment momentum (lagged effect) has noticeable correlation with profitability
 Volume and PnL vary widely by sentiment volatility
 Clustering reveals distinct behavioral patterns across sentiment bands

## Requirements.txt
pandas
numpy
matplotlib
seaborn
scipy
scikit-learn

## Author:
Jeeva M
Data Science Intern – 2025
 For feedback or collaboration, reach out via LinkedIn or GitHub.




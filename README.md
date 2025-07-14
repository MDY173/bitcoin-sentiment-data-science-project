# Market Sentiment vs Trader Performance

This project explores the relationship between Bitcoin market sentiment (Fear/Greed Index) and trader performance (Closed PnL) using historical trading data from Hyperliquid.

## 📊 Data Sources

- `fear_greed_index.csv`: Contains daily market sentiment (Extreme Fear, Fear, Neutral, Greed, Extreme Greed)
- `historical_data.csv`: Includes trade-level data (Account, Coin, PnL, Leverage, etc.)

## 🔍 Objective

To uncover hidden patterns between:
- Market sentiment and Closed PnL
- Time-based trading behavior under varying sentiments

## 📈 Key Insights

- Highest trader performance (PnL) occurs during Fear and Extreme Greed.
- Neutral and Extreme Fear periods see weaker trading returns.
- Visualizations reinforce strategic timing aligned with sentiment.

## 📁 Files

- `sentiment_analysis.ipynb`: Full Python notebook
- `merged_trader_sentiment_analysis.xlsx`: Cleaned and merged dataset
- `plots/`: PNG images of summary plots

## 🛠️ Tools Used

- Python (Jupyter Notebook)
- pandas, seaborn, matplotlib

## ✅ Requirements

- To install required packages:
     pip install -r requirements.txt

## ✅ Next Steps

- Analyze per-account or per-symbol behavior
- Integrate real-time sentiment feed
- Extend to predictive modeling with ML

## ✅ Conclusion

- Trader performance is noticeably higher during periods of **Fear** and **Extreme Greed**, suggesting that volatility or strong sentiment may create more trading opportunities.
- Average Closed PnL is lowest during **Neutral** sentiment periods, indicating less opportunity or lower risk-taking.
- Incorporating sentiment data into trading strategies could help optimize entry and exit decisions.
- Future extensions could explore per-symbol performance, leverage effects, or predictive modeling using sentiment data.


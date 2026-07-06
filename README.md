# Bitcoin Market Sentiment vs Hyperliquid Trader Performance

**Primetrade.ai Data Science Assignment**

## Objective
Explored relationship between Bitcoin market sentiment (Fear/Greed Index) and trader performance using the datasets provided in the assignment.

## Datasets Used (Original Links)
- Historical Trader Data: https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing
- Fear & Greed Index: https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

## Key Findings
- Traders perform significantly better during **Greed** and **Extreme Greed** periods.
- More losses and conservative behavior during **Fear** phases.
- Buy-side trades dominate in positive sentiment; shorts increase in fear.
- Strong opportunity to use sentiment for dynamic risk management and strategy optimization.

## Insights & Recommendations
- Use sentiment as a filter for trading decisions.
- Incorporate sentiment_score in ML models.
- Identify regime-specific outperforming traders.

Full analysis, code, and visualizations available in the Jupyter notebook.# bitcoin-sentiment-trader-analysis
Analysis of Bitcoin Fear &amp; Greed Index vs Hyperliquid Trader Performance (Primetrade.ai Assignment)
## Technical Details
- Data Preprocessing & Merging on Date
- Sentiment Encoding
- Feature Engineering (PnL, trade direction, size-normalized metrics)
- Exploratory Analysis & Visualizations

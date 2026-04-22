# Crypto-Trading-Analysis
Analysis of trader performance vs market sentiment (Fear/Greed) using Python and Power BI, uncovering behavioral patterns and strategy insights.

**Objective**
Analyze how market sentiment (Fear vs Greed) impacts trader behavior and performance.
**Methodology**

- Cleaned and merged trader + sentiment datasets using Python
- Converted timestamps to daily level
- Created key metrics:
  - Daily PnL per trader
  - Win rate
  - Average trade size
  - Trade frequency
  - Long/Short ratio
- Built interactive dashboard in Power BI for visualization
##  Key Analysis & Findings

### 1. Performance: Fear vs Greed

- Total PnL is higher during **Greed** periods compared to Fear periods
- Win rate slightly improves during Greed sentiment
- Fear periods show lower profitability and higher uncertainty
- **Conclusion:** Traders perform better in bullish (Greed) market conditions
- ### 2. Behavioral Changes Based on Sentiment

- Trade frequency increases during **Greed** periods
- Average position size is larger during Greed
- Traders take more **Long positions** in Greed and more cautious positions during Fear

 Conclusion: Traders become more aggressive in Greed and conservative in Fear

---

### 3. Trader Segmentation

#### a) Frequent vs Infrequent Traders
- Frequent traders execute more trades but have slightly lower win rates
- Infrequent traders show more stable performance

#### b) Consistent vs Inconsistent Traders
- Consistent traders maintain steady PnL across sentiments
- Inconsistent traders show high volatility in returns

 Conclusion: Higher activity does not always lead to better performance

 ##  Key Insights

- Traders generate higher profits during Greed periods
- Fear periods reduce trading activity and profitability
- High-frequency trading does not guarantee higher success
- Consistent traders outperform volatile traders over time
- ##  Strategy Recommendations

1. **Adjust risk based on sentiment**
   - Reduce position size during Fear periods
   - Increase exposure during Greed cautiously

2. **Focus on consistency over frequency**
   - Avoid overtrading during volatile (Fear) markets
   - Maintain disciplined trading strategy

   ##  Tools Used

- Python (Pandas, NumPy)
- Power BI (Dashboard & Visualization)

---

##  How to Run

1. Clone the repository
2. Open `Crypto_trading.ipynb` and run all cells
3. Open `crypto dashboard.pbix` in Power BI to view visuals

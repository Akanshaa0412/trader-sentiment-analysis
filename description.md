Trader Behavior vs Market Sentiment Analysis

A. Methodology
1. Loaded and cleaned both datasets (trades + sentiment)
2. Converted timestamps into a consistent date format
3. Aligned datasets using date and handled mismatches using forward-fill
4. Created key metrics:
	PnL (Closed PnL)
	Win rate (profitable trades %)
	Trade frequency
	Position size (Size USD as leverage proxy)
5. Performed analysis across sentiment categories (Fear, Greed, etc.)
8. Segmented traders based on:
	Position size (High vs Low)
	Trading frequency (Frequent vs Normal)
	Consistency (Stable vs Volatile performance)


B. Key Insights
1. Performance varies with sentiment
	Traders generally achieve higher average PnL and win rates during Greed phases, while Fear phases are associated with lower profitability and higher downside risk.

2. Behavior changes based on market sentiment
	During Greed periods, traders:
		Trade more frequently
		Take larger positions
		Show a stronger bias toward long trades

	In contrast, Fear periods show reduced activity and more cautious behavior.

3. Trader segmentation reveals performance differences
	High position size traders exhibit higher returns but also higher risk
	Frequent traders tend to perform more consistently
	Consistent traders outperform volatile (inconsistent) traders over time

C. Strategy Recommendations
1. Adjust risk based on sentiment
	During Fear: reduce position size and avoid overtrading
	During Greed: increase participation but control risk exposure
2. Prioritize consistency over aggression
	Focus on steady trading strategies rather than large, high-risk positions
	Frequent and consistent traders tend to achieve better long-term performance


D. Conclusion

Market sentiment plays a significant role in shaping both trader behavior and performance. Combining sentiment awareness with disciplined risk management can improve trading outcomes and reduce downside risk.
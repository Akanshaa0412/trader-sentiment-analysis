# Trader Behavior vs Market Sentiment Analysis

## Objective
Analyze how market sentiment impacts trader performance and behavior.

## Methodology
- Cleaned and processed trade and sentiment data
- Handled date mismatch using forward-fill approach
- Created key metrics: PnL, win rate, trade frequency, position size
- Segmented traders based on size, frequency, and consistency

## Key Insights
- Traders perform better during Greed vs Fear phases
- Trade frequency and position size increase during Greed
- Consistent and frequent traders outperform high-risk traders

## Strategy Recommendations
- Reduce risk during Fear periods
- Increase participation but control risk during Greed
- Focus on consistent trading behavior over aggressive strategies

## How to Run
1. Install required libraries:
   pip install pandas matplotlib seaborn
2. Run the notebook: analysis.ipynb
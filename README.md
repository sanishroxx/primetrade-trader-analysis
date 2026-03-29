# primetrade-trader-analysis
# Trader Performance vs Market Sentiment
Primetrade.ai — Data Science Intern Assignment

## How to Run
1. Open `primetrade_analysis.ipynb` in Google Colab
2. Upload both CSV files:
   - `fear_greed_index.csv`
   - `historical_data.csv`
3. Run all cells top to bottom

## What I Did
- Loaded and cleaned both datasets
- Merged datasets on date column
- Analyzed PnL, win rate, trade size by sentiment
- Segmented traders by behavior
- Built a Random Forest model (74% accuracy)

## Key Insights
1. Fear days had most trades (61,837) with biggest
   trade size ($7,816) — panic trading behavior

2. Extreme Greed days had lowest trade size ($3,112)
   and more SELL than BUY — smart profit booking

3. SELL trades were higher than BUY in every sentiment
   — traders have overall bearish bias

## Strategy Recommendations
1. Fear days → reduce position size by 50%
2. Extreme Greed → start booking profits, avoid new BUY

## Author
Sanish Kumar
GitHub: github.com/sanishroxx

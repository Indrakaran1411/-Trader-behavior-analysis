# Trader Behavior & Market Sentiment Analysis

# Project Overview
This project explores the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance data from Hyperliquid. The objective is to uncover hidden patterns in trader behavior, specifically focusing on profitability, risk appetite, and position sizing during different market phases.

# Key Insights & Patterns Uncovered

# 1. "Extreme Greed" is the Most Profitable Phase
* Finding: Traders achieve their highest average Profit and Loss (PnL) during periods of "Extreme Greed" (~$67.89/trade).
* Contrast: In "Neutral" or "Extreme Fear" markets, average profitability drops significantly (~$34.50/trade), suggesting traders struggle when market direction is unclear or panic-driven.

# 2. The "Buy the Dip" Risk Appetite
* Finding:Traders take their largest position sizes (Avg: ~$7,816 USD) during "Fear" phases, not Greed.
* Interpretation: This indicates high-conviction "dip buying" behavior. Conversely, during "Extreme Greed," position sizes drop to their lowest (~$3,112 USD), showing caution as prices peak.

# 3. Smart Money Sells into Euphoria
* Finding: During "Extreme Greed," the market sees a shift to net selling (Buy/Sell Ratio: 0.81).
* Interpretation:** Experienced traders appear to be offloading positions (taking profits) while sentiment is euphoric, rather than chasing the rally.

## Technical Approach
Data Sources:** Merged daily Fear & Greed Index data with high-frequency Hyperliquid trade logs.
* Methodology:
    * Standardized timestamps to align daily sentiment with intraday trades.
    * Performed an Inner Join on dates to link specific trade outcomes with that day's sentiment.
    * Analyzed PnL distributions, leverage usage, and order side ratios using Pandas and Seaborn.



## Author
Indra Karan Gajula
* **Email:gajulapravan@gmail.com

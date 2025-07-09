
# Zimbabwe Maize Market Analysis for Food Security

This project analyzes maize price trends in Zimbabwe and forecasts future prices using time series modeling. It also compares price changes across provinces and calculates monthly price growth. The analysis is tailored for food security insights, aligning with the goals of organizations such as the World Food Programme (WFP).

---

## Project Objectives

- Analyze maize price trends nationally and by province.
- Forecast prices using SARIMA time series modeling.
- Calculate monthly price growth rates.
- Support data-driven food security and market monitoring decisions.

---

## Dataset

- Source: Market monitoring dataset from FEWS NET and public repositories.
- Fields: `period_date`, `admin_1` (province), `value` (maize price in USD).
- Range: 2015–2024 (filtered for clean forecasting).

---

## Key Analyses

1. National Maize Price Trend
2. Provincial Price Comparisons
3. 3-Month Rolling Average Smoothing
4. Monthly Growth Rate Calculation
5. 12-Month Price Forecast (SARIMA Model)

---

## Tech Stack

- Python (Pandas, Matplotlib, Seaborn, Statsmodels)
- Jupyter/Colab
- Time Series Modeling (SARIMA)
- Data Visualization and Cleaning

---

## Visual Insights

- Line plots of national and provincial maize price trends
- Rolling averages to show smoothed patterns
- Bar chart of monthly % growth in price
- 12-month future forecast with confidence intervals

---

## How to Run This Notebook

1. Upload your dataset (e.g., `maize_prices.csv`)
2. Run each section in sequence
3. SARIMA forecast may require tweaking if data structure changes

---

## Forecast Interpretation

- Forecasts indicate continued maize price increases into the next year.
- Wide confidence intervals reflect price volatility, useful for early warning systems.
- Regional disparities suggest localized market behavior that requires targeted interventions.

---

## Author

**Vanessa Chinhengo**  
Financial Mathematics Graduate | Data Enthusiast | Community Builder  
[LinkedIn](https://linkedin.com/in/vanessachinhengo)  
vanessachinhengo@gmail.com

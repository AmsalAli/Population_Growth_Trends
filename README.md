# Global Trends in Population Growth (Annual %)

This repository explores global trends in **annual population growth rate**, based on the de facto definition of population. The dataset provides insights into population dynamics and demographic changes over time. It is sourced from the **World Bank** and covers multiple decades and regions.

## 🌍 Dataset Overview
- **Metric**: Annual population growth rate (%).
- **Source**: [World Bank](https://data.worldbank.org/)
- **Time Span**: Varies by country but spans several decades.
- **Geographical Coverage**: Worldwide.
- **Periodicity**: Annual.
- **Aggregation Method**: Weighted average.

## 📊 Key Questions to Explore
1. Which countries or regions experience the highest and lowest population growth rates?
2. How have global and regional population growth rates evolved over time?
3. What factors contribute to varying population growth rates across countries?

## 🚀 Potential Applications
- **Demographic Analysis**: Identify global and regional trends in population dynamics.
- **Regional Comparisons**: Explore disparities in population growth across countries.
- **Correlation Studies**: Study relationships between population growth and economic or health indicators.

## 📈 Sample Visualizations
- Line charts showing population growth trends over time.
- Heatmaps highlighting disparities in population growth rates by region.
- Scatterplots correlating population growth with GDP, health, or literacy rates.

## 📜 Methodology
The **population growth rate** is calculated using the exponential growth formula:  
`r = ln(pn/p0)/n`,  
where:  
- `r` is the exponential rate of growth.  
- `pn` is the end period population.  
- `p0` is the beginning period population.  
- `n` is the number of years between periods.

This approach assumes constant growth between two points in time.

## 🛠️ Tools for Analysis
- Python libraries: `pandas`, `matplotlib`, `seaborn`, `plotly`.
- Jupyter Notebook for exploratory data analysis (EDA).

## 💻 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/AmsalAli/Population_Growth_Trends.git

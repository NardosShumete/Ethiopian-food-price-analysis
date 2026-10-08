# Ethiopian Food Price Analysis

## Project Overview

This project explores how retail food prices vary across commodities and markets in Ethiopia using Python and Pandas.

The main objective is to compare food prices, identify differences between markets, and measure price variation using descriptive statistics and visualizations.

## Dataset and Methodology

The original dataset contained 77,017 records covering 20 commodities and 22 markets, from January 2020 to June 2023.

The data was cleaned to focus on retail prices measured in kilograms (kg), denominated in Ethiopian Birr (ETB), with valid price values.

The final dataset contained **32,504 observations covering 12 commodities across 22 markets**.

The analysis included:
- Data exploration and cleaning
- Average price comparison by commodity
- Average price comparison by market
- Price variation using standard deviation and coefficient of variation (CV)

## Key Findings

### 1. Market Price Differences

- **Warder** had the highest average observed price at 68.73 ETB/kg.
- **Nekemte** had the lowest average observed price at 31.80 ETB/kg.
- The difference between their average observed prices was 36.93 ETB/kg.

Four commodities—white maize grain, refined sugar, white sorghum, and wheat grain—were available across all 22 markets, allowing comparisons using a common set of commodities.

### 2. Commodity Price Variation

- **Beans (Haricot)** had the highest standard deviation at 36.41 ETB/kg.
- **White maize grain** had the lowest standard deviation at 14.58 ETB/kg.
- **Firewood** had the highest coefficient of variation at 119.74%.
- **Horse beans** had the lowest coefficient of variation at 32.15%.

These results demonstrate that absolute and relative price variation can produce different rankings.

### 3. Market Price Variation

- **Warder** had the highest market-level standard deviation at 37.43 ETB/kg.
- **Chereti** had the lowest market-level standard deviation at 15.50 ETB/kg.
- **Mekele** had the highest market-level coefficient of variation at 68.34%.
- **Chereti** had the lowest market-level coefficient of variation at 36.71%.

## Key Visualizations

### Location & Market Analysis

**Average Price by Market**
![Average Price by Market](images/average_price_by_market.png)
*Figure 1: Displays the overall average retail food price (ETB/kg) across 22 Ethiopian markets. It highlights which markets tend to be generally more expensive (e.g., Warder) versus cheaper (e.g., Nekemte).*

**Commodity by Market Heatmap**
![Commodity Market Heatmap](images/commodity_market_heatmap.png)
*Figure 2: A heatmap showing the average price (ETB/kg) of four widely available commodities across all tracked markets. Darker colors indicate higher prices.*

### Price Variation Analysis

**Commodity Price Variation (Standard Deviation)**
![Commodity Price Variation STD](images/commodity_price_variation_std.png)
*Figure 3: Highlights the absolute price variation (in ETB/kg) across different commodities. Commodities with higher standard deviations experience wider price spreads.*

**Commodity Price Variation (Coefficient of Variation)**
![Commodity Price Variation CV](images/commodity_price_variation_cv.png)
*Figure 4: Shows the relative price variation (CV %) for different commodities. This reveals how much a commodity's price fluctuates relative to its own average price, with Firewood showing massive relative volatility.*

**Market Price Variation (Standard Deviation)**
![Market Price Variation STD](images/market_price_variation_std.png)
*Figure 5: Compares how much prices fluctuate within each market. Warder shows the highest absolute price variation across the items sold there.*

## Limitations

This is a descriptive analysis. It identifies observed price differences and variation but does not establish their causes.

Results depend on the commodities, markets, dates, and observations available in the cleaned dataset. The analysis does not establish that every commodity was equally available in every market, except for the four identified common commodities.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git and GitHub

## Conclusion

The analysis reveals differences in average observed food prices across Ethiopian markets and demonstrates that price variation depends on whether it is measured in absolute or relative terms. The project provides a practical example of data cleaning, exploratory data analysis, descriptive statistics, and data visualization using Python.

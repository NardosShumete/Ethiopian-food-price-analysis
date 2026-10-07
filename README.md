# Ethiopian Food Price Analysis

## Project Overview

This project analyzes food prices in Ethiopia using a food price dataset containing information about commodities, markets, dates, units, currencies, and prices.

The project focuses on understanding how food prices vary across different commodities and Ethiopian markets.

## Project Question

How do food prices vary across commodities and Ethiopian markets?

## Objectives

### 1. Commodity Analysis
Understand how prices differ between food commodities.

### 2. Market Analysis
Compare food prices across different Ethiopian markets.

### 3. Price Variation
Identify commodities and markets with larger differences in price.

## Dataset

The dataset contains Ethiopian food price observations with fields such as:

- Country
- Market
- Administrative region
- Commodity/Product
- Date
- Price type
- Unit
- Currency
- Price value
- Geographic coordinates

The dataset will be stored locally in:

data/raw/

## Project Structure

```text
ethiopian-food-price-analysis/
│
├── data/
│   ├── raw/          # Original dataset
│   └── processed/    # Processed dataset
│
├── notebooks/        # Jupyter notebooks
│
├── images/           # Project charts and visualizations
│
├── README.md
├── requirements.txt
└── .gitignore
```

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

# Retail Sales EDA — Superstore Dataset

**Prepared by Group 22** · July 8, 2026

## Overview

Exploratory data analysis of Superstore retail sales data, uncovering trends across time, categories, geography, and customer segments to produce actionable business recommendations.

## Dataset

- `train.csv` — 9,800 orders, 18 fields, Jan 2015–Dec 2018
- 11 missing Postal Codes (filled with "Unknown"), 0 duplicates

## Tools

Python 3 · pandas · numpy · matplotlib · seaborn · Jupyter Notebook

## Analysis

12 charts covering: monthly sales trend, sales by category/region/city/state/segment, top products, region × category, shipping mode by segment, regional sales share, sales distribution, and a monthly regional heatmap.

## Key Findings

1. Sales grow ~$888/month (2015–2018), peaking every Sep–Dec.
2. Technology leads categories ($827K), ahead of Furniture ($729K) and Office Supplies ($705K).
3. West leads regions (31.4%); South lags (17.2%) year-round.
4. Sales concentrate in NYC, LA, Seattle, California, New York, Texas.
5. One product (Canon imageCLASS 2200 Copier) made $61.6K — 2x the next best.
6. Consumer segment drives $1.15M in sales; Standard Class dominates shipping.
7. Orders are right-skewed (skew ≈ 13): median $54 vs. mean $230.

## Recommendations

1. Protect the West's lead; investigate the South's underperformance.
2. Staff up for Sep–Dec demand spikes.
3. Focus marketing on top markets; test growth elsewhere.
4. Bundle Technology with Furniture/Office Supplies.
5. Prioritize Consumer segment marketing.
6. Upsell faster shipping options.
7. Forecast using median, not mean, sales values.

## How to Run
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook Task.ipynb

Run all cells, charts save automatically to `charts/`.

## Deliverables

`Task.ipynb` · `charts/` · `Superstore_Sales_EDA.pptx`

## Authors

**Group 22**

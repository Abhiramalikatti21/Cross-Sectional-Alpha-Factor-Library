# Cross-Sectional Alpha Factor Library

A modular Python framework for engineered alpha factors, preprocessing, and statistical validation (Information Coefficient).

## Features
- **Modular Factor Design**: Easily extensible classes for Momentum, Volatility, and Value.
- **Robust Preprocessing**: Cross-sectional Z-scoring and Winsorization to handle outliers and signal stationarity.
- **Statistical Evaluation**: Daily Spearman Rank IC calculation and Information Ratio (IR) analysis.

## Methodology
- **Universe**: Mock equity panel data (MultiIndex: Date, Ticker).
- **Signal Logic**: Factors are ranked cross-sectionally to ensure market neutrality.
- **Bias Mitigation**: 1-day forward-shifting of returns to prevent look-ahead bias.

## How to Run
1. Clone the repo.
2. Install dependencies: `pip install -r requirements.txt`
3. Run `Alpha Factory Library.ipynb` to see factor performance plots.

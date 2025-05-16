# Price Optimization Analysis Using Random Forest

## Overview

This project analyzes pricing and sales data for our store versus the competition, using data visualization and machine learning to recommend an optimal pricing strategy.

We use visual analytics and Random Forest Regression to determine the best price point that maximizes revenue while remaining competitive.

## Project Goals

- Explore price and sales quantity relationships
- Compare price distributions between our store and the competition
- Build a predictive ML model to estimate sales amount
- Simulate and recommend an optimal price
- Provide actionable business insights

## Key Insights from the Project

### 1. Price Distribution Analysis
- Our store and the competitor had overlapping but differently shaped price distributions.
- The competitor’s price range showed more frequent use of higher price points.
- This indicates that the competitor may be anchoring customers at more strategic price levels.

### 2. Sales vs Price
- A scatter plot revealed wide dispersion in our store’s sales amount at different price levels.
- The competitor’s pricing showed tighter grouping around higher sales amounts, suggesting a more consistent pricing strategy.

### 3. Random Forest Regression
- A machine learning model was built using **Random Forest Regressor** to predict sales amount from price.
- **R² Score**: `0.840` – Indicates that the model explains 84% of the variation in sales.
- **Mean Squared Error**: `548.26` – The model performs well in approximating sales trends.

### 4. Price Simulation
- Using the model, we simulated sales revenue across different price points.
- **Optimal Predicted Price**: `KSh 168`
- **Maximum Predicted Revenue**: `KSh 71,181.60`

### 5. Comparison with Competition
- A final simulation compared potential revenue at our original average price, competitor price, and optimized price.
- The optimized price performed significantly better than the current pricing and slightly below the competitor's top revenue.


## Recommendations

- **Adjust Our Store’s Price to KSh 168**: This point yielded the highest predicted revenue and aligns closely with the competitor’s pricing range.
- **Adopt Data-Driven Pricing**: Periodically simulate price-performance to remain competitive.
- **Monitor Competitor Strategies**: Their consistent sales suggest strategic clustering around high-performing prices.
- **Test and Validate**: Consider A/B testing this optimized price in real-world scenarios before full rollout.


## Technologies Used

- Python (Jupyter Notebooks)
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Random Forest Regression)

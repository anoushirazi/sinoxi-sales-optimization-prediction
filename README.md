# sinoxi-sales-optimization-prediction 📈💼
## Overview

Welcome to **Sinoxin-Sales-Optimization-Prediction**, a data analysis project designed to unlock the power of sales data for smarter business decisions. Using Python, I’ve performed in-depth analysis, built predictive models, and delivered actionable insights to optimize profitability, inventory, and customer strategies. This project showcases my skills in data analysis, machine learning, and business intelligence—perfect for driving real-world impact.

---

## 🚀 Project Highlights

- **Exploratory Data Analysis (EDA):** Uncovered trends, correlations, and statistical insights from sales data.
- **Feature Engineering:** Created time-based features, lag variables, and profitability metrics.
- **Visualizations:** Generated 9 stunning plots to reveal key patterns (e.g., top customers, seasonality, sales trends).
- **Machine Learning:** Built a Random Forest model to forecast sales with high accuracy (R²: 0.91).
- **Business Recommendations:** Provided strategies for customer retention, inventory management, and cross-selling.

---

## 📂 Project Structure

Here’s how the project is organized:

- **`src/`**: Core Python script (`sales_analysis.py`) that drives the entire analysis.
- **`data/`**: Raw dataset (`sales_data.csv`) and processed data (`engineered_sales_data.csv`).
- **`images/`**: 9 visualization outputs (used as presentation slides).
- **`requirements.txt`**: List of Python dependencies to run the project.
- **`notebooks/`**: Contains the Jupyter Notebook (`Sinoxin-Sales-Optimization-Predictioin.ipynb`) with the full analysis.
- **`README.md`**: You’re reading it!

---

## 📊 Visualizations (Slides)

These 9 visualizations tell the story of the data and are saved in the `images/` folder:

1. **Correlation Heatmap** (`images/correlation_heatmap.png`): Identifies relationships between sales variables.
2. **Top 10 Customers by Sales** (`images/top_customers.png`): Highlights high-value customers for targeted strategies.
3. **Profit by Product Line** (`images/profit_by_product.png`): Pinpoints high-margin products.
4. **Top 10 Products by Quantity Ordered** (`images/stock_movement.png`): Guides inventory stocking decisions.
5. **Average Sales by Month (Seasonality)** (`images/seasonality.png`): Reveals peak sales periods for marketing campaigns.
6. **Order Frequency per Customer** (`images/repeat_customers.png`): Analyzes customer loyalty patterns.
7. **Sales by Country** (`images/sales_by_country.png`): Identifies top-performing markets.
8. **Sales Over Time** (`images/daily_sales_time_series.png`): Tracks sales trends across the dataset.
9. **Actual vs Predicted Sales** (`images/actual_vs_predicted_sales.png`): Demonstrates the accuracy of the ML model.

---

## 🛠️ Tech Stack

- **Python Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `scikit-learn`
- **Analysis Techniques:** EDA, feature engineering, T-tests, time series analysis
- **Machine Learning:** Random Forest regression with cross-validation
- **Tools:** GitHub, GitHub Desktop for version control

---

## 💡 Business Recommendations

Here’s how the insights can drive business value:

- **Customer Strategy:** Retain top customers with loyalty programs; upsell to the medium segment.
- **Profit Optimization:** Focus on high-margin product lines like those identified in the profit analysis.
- **Inventory Planning:** Stock top products (e.g., from `stock_movement.png`) for peak seasons.
- **Marketing Timing:** Boost campaigns in high-sales months (see `seasonality.png`).
- **Geographic Expansion:** Prioritize markets with strong sales (e.g., from `sales_by_country.png`).
- **Cross-Selling:** Bundle frequently paired products (identified via market basket analysis).
- **Forecasting:** Use the ML model for demand planning (R²: 0.91, MSE: 397,109.52).

# Fashion_Retail_Analytics
# 🛍️ Fashion Retail Analytics Project

A data-driven solution for dynamic pricing and inventory optimization in a fashion retail context.

## 📁 Dataset
- Source: [Fashion_Retail_Sales.csv](data/raw/Fashion_Retail_Sales.csv)
- Fields: Customer ID, Item Purchased, Purchase Amount, Date, Review Rating, Payment Method

## 🎯 Project Objectives
- Analyze sales performance and customer behavior
- Simulate a dynamic pricing strategy based on demand
- Optimize inventory using RFM and ABC analysis
- Visualize insights via an interactive Power

## 📊 Exploratory Data Analysis (EDA) Summary
📈 Sales Trends: Peak purchasing occurred in [insert peak month], with higher sales on weekends.

🛍️ Top Items: "Handbag", "Tank Top", and "Leggings" were the highest-revenue products.

💳 Payment Behavior: Credit Card was the most preferred method, followed by Cash.

⭐ Review Impact: Higher-rated products (4.5+) showed slightly higher purchase amounts, indicating positive feedback may influence spending.

📅 Weekday Behavior: Saturday had the highest revenue; Tuesday was the lowest.

## 📈 Modeling & Optimization Summary
🧠 RFM Segmentation
Recency: Days since last purchase

Frequency: Total transactions per customer

Monetary: Total purchase value per customer

🛒 ABC Classification
Class A: Top ~20% items → generate 80% revenue

Class B: Middle 15% items

Class C: Remaining items → low ROI, high risk

🌪️ Demand Volatility
Calculated via standard deviation of weekly sales per product

High-volatility products flagged for lean inventory strategies

💰 Dynamic Pricing Simulation
+10% price for high-rated (4.5+) items

−10% discount for poorly rated (<3.0) items

Tracked simulated price change impact across product categories

## 📦 Outputs
cleaned_fashion_sales.csv

inventory_strategy_summary.csv

simulated_pricing.csv

3 modular notebooks: data_cleaning, EDA, pricing_inventory_model

## 📊 Dashboard Preview

![Dashboard](images/Dashboard.png)

## 🧰 Tools Used:
Python (pandas, matplotlib, seaborn)

Jupyter Notebooks

Git & GitHub

Power BI/Tableau for dashboard visualization

## 🚀 Outcomes:

💳 Payment Behavior

Credit Cards account for the majority of purchases, followed by Cash.

Payment method preference could guide checkout UX optimizations.

⭐ Customer Reviews

Products with higher review ratings (~4–5 stars) show slightly higher purchase values.

Encouraging reviews might indirectly boost revenue.

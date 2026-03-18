
[README.md](https://github.com/user-attachments/files/26074505/README.md)
Walmart Sales Analysis \& Demand Forecasting
🔹 Project Overview

This project analyzes Walmart retail sales data to identify patterns in store performance and evaluate factors influencing demand. The goal is to generate business insights and build a basic predictive model for weekly sales.

🎯 Objectives

Analyze sales performance across stores

Identify seasonal and holiday trends

Measure variability in store performance

Build a regression model to forecast demand

📁 Dataset

The dataset contains weekly sales data from multiple Walmart stores, including:

Store ID

Date

Weekly Sales

Holiday Flag

Temperature

Fuel Price

CPI (Consumer Price Index)

Unemployment Rate

🛠️ Tools \& Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📈 Key Insights

🏆 Top Performing Store:
Store 20 generated the highest total sales (\~$301M)

📊 Sales Variability:
Store 14 shows the highest fluctuation in sales
Store 35 shows the highest relative variability

🎄 Holiday Impact:
Holiday weeks generate higher average sales than non-holiday periods

📅 Seasonality Trends:

July has the highest sales

January has the lowest sales

Second semester (Jul–Dec) outperforms the first

🤖 Predictive Model

A Linear Regression model was built using:

CPI

Fuel Price

Unemployment

Time (Day Number)

Result:

R² Score ≈ 0.01

👉 The model has very low predictive power

🧠 Key Takeaways

Macroeconomic variables alone are not sufficient to predict weekly retail sales

Sales are likely driven by:

Promotions

Seasonality

Store-specific behavior

🚀 Future Improvements

Include promotional and markdown data

Add holiday-specific features

Use advanced models (Random Forest, XGBoost)

Perform time series forecasting

▶️ How to Run
pip install -r requirements.txt

Open the notebook:

jupyter notebook


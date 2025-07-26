# 🛍️ Shopping Trends Analysis

This project analyzes customer shopping trends using Python (Pandas, Matplotlib) and visualizes key insights like demographics, gender distribution, and most purchased items.

## 📊 Project Overview
- **Data Source:** `shopping_trends.csv` (customer shopping data)
- **Tools Used:**
  - Python (Pandas, NumPy, Matplotlib)
  - Power BI (Interactive dashboard)
  - SQLAlchemy + MySQL (optional DB connection)

## 📊 What’s Inside?

- **Data Cleaning** → Removed duplicates, dropped unused columns  
- **Exploratory Data Analysis (EDA)**  
  - Age distribution  
  - Gender split (Bar & Pie charts)  
  - Top purchased items  
- **Visualizations** → Matplotlib-based plots  

## 📂 Project Structure
- `data/shopping_trends.csv` → Raw dataset
- `notebooks/shopping_trends_analysis.ipynb` → Jupyter Notebook with analysis
- `notebooks/connect_to_sql_server.ipynb` → SQL connection example
- `reports/shopping_trends.pbix` → Power BI dashboard

## 🛠️ Requirements
Install dependencies:
```bash
pip install -r requirements.txt
# Amazon-analysis

# Amazon Sales Data Analysis 📊

A comprehensive data analysis project examining Amazon sales performance metrics to provide actionable business insights for merchant decision-making.

## 🎯 Project Overview

This project analyzes Amazon sales data to help a merchant understand their sales performance across different dimensions including categories, fulfillment methods, and transaction amounts. The analysis provides key metrics and visualizations to support business strategy and investor reporting.

## 📋 Business Requirements

The merchant requested analysis on the following key areas:
- High-value transactions (sales > 1000)
- Category-specific performance ("Tops" category with quantity 3)
- Sales distribution across product categories
- Performance metrics by category and order status
- Fulfillment and shipment analysis

## 🔧 Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **OpenPyXL** - Excel file handling
- **Jupyter Notebook** - Interactive development environment

## 📊 Key Analysis Components

### 1. High-Value Sales Analysis
- Identified sales transactions exceeding $1,000
- Calculated percentage of high-value sales vs total transactions

### 2. Category-Specific Filtering
- Analyzed "Tops" category performance
- Filtered sales with specific quantity requirements (quantity = 3)

### 3. Sales Performance Metrics
- **Total Sales by Category**: Revenue breakdown across all product categories
- **Average Amount by Category and Status**: Performance analysis segmented by order status
- **Sales by Fulfillment and Shipment**: Operational efficiency analysis

## 📈 Key Findings

```python
# Sample insights from the analysis
High-value sales: X transactions
Tops category (qty=3): Y sales
Top performing category: Category Name (Z revenue)
Most efficient fulfillment method: Method Name
```

## 🏗️ Project Structure

```
amazon-sales-analysis/
│
├── data/
│   └── sales_data.xlsx          # Raw sales data
│
├── notebooks/
│   └── amazon_sales_analysis.ipynb
│
├── reports/
│

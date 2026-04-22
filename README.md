# Tableau Sales Dashboard

A comprehensive Tableau project featuring interactive sales performance and customer analytics dashboards designed to provide actionable insights for sales managers and executives.

**Part of the [Data With Baraa Tableau Course](https://www.datawithbaraa.com/wiki/tableau#welcome-to-tableau-course)**

## 📊 Project Overview

This project implements two main dashboards:

### Sales Dashboard

- **KPI Overview**: Total sales, profits, and quantity metrics for current and previous years
- **Sales Trends**: Monthly performance analysis with highlighted high/low periods
- **Product Analysis**: Subcategory comparisons and sales vs. profit analysis
- **Weekly Trends**: Sales and profit tracking with average benchmarks

### Customer Dashboard

- **Customer Metrics**: Total customers, sales per customer, and order counts
- **Customer Trends**: Monthly customer behavior analysis
- **Customer Segmentation**: Distribution analysis by order frequency
- **Top Customers**: Profit-based ranking with detailed customer profiles

## 🎯 Key Features

- **Interactive Visualizations**: Drill-down capabilities and dynamic filtering
- **Year-over-Year Analysis**: Historical data comparison functionality
- **Geographic Filtering**: Region, state, and city-based data segmentation
- **Product Category Analysis**: Performance breakdown by product hierarchies
- **Real-time Insights**: Highlighted performance indicators and trends

## 📁 Dataset Structure

```
datasets/
├── eu/           # European market data
│   ├── Customers.csv
│   ├── Location.csv
│   ├── Orders.csv
│   └── Products.csv
└── non-eu/       # Non-European market data
    ├── Customers.csv
    ├── Location.csv
    ├── Orders.csv
    └── Products.csv
```

## 🚀 Getting Started

1. **Prerequisites**: Tableau Desktop or Tableau Public
2. **Data Connection**: Connect to the CSV files in the `datasets/` folder
3. **Dashboard Creation**: Follow the specifications in `docs/user_story.md`
4. **Interactivity**: Implement filters for year, region, and product categories

## 📋 Requirements

- Tableau Desktop/Public (latest version recommended)
- CSV data files (included in repository)
- Basic understanding of Tableau interface and visualizations

## 🎓 About This Project

This project is part of the **Data With Baraa Tableau Course**, a comprehensive program for learning modern data visualization and dashboard design best practices.

- **Course Link:** [Data With Baraa - Tableau Course](https://www.datawithbaraa.com/wiki/tableau#welcome-to-tableau-course)
- **Topics Covered:** Dashboard Design, Data Visualization, Interactive Analytics, KPI Development, Customer Segmentation

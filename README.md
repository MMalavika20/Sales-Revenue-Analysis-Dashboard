# Chocolate Sales & Revenue Analysis Dashboard

## 📊 Project Overview

An interactive Power BI dashboard developed to analyze chocolate sales,
revenue, products, countries, and salesperson performance.

## 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- CSV Dataset

## 📈 Dashboard Features

- Total Revenue KPI
- Total Boxes Sold KPI
- Average Sale KPI
- Products Sold KPI
- Monthly Revenue Trend
- Sales by Country
- Top 10 Products by Revenue
- Top 10 Salespeople by Revenue
- Date Filter
- Country Filter
- Product Filter
- Sales Person Filter
- Interactive Cross-filtering

## 🧹 Data Preparation

The dataset was prepared using Power Query.

- Removed `$` currency symbols
- Removed commas from Amount values
- Converted Amount to numeric format
- Verified date and numerical fields
- Prepared the dataset for analysis

## 📐 DAX Measures

```DAX
Total Revenue = SUM('Chocolate Sales'[Amount])

Total Boxes = SUM('Chocolate Sales'[Boxes Shipped])

Average Sale = AVERAGE('Chocolate Sales'[Amount])

Products Sold = DISTINCTCOUNT('Chocolate Sales'[Product])

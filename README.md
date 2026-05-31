# Predictive Analytics Using Historical Data with Power BI

## Project Overview

This project focuses on building a predictive analytics solution using historical sales data in Power BI. The objective is to analyze past sales performance, identify trends, and forecast future sales using data-driven techniques.

The project demonstrates the complete analytics workflow, including data cleaning, preprocessing, visualization, trend analysis, and forecasting.

---

## Objectives

* Clean and preprocess historical sales data.
* Analyze sales, profit, and order performance.
* Identify historical trends and patterns.
* Create interactive dashboards using Power BI.
* Forecast future sales using predictive analytics techniques.
* Support data-driven business decision-making.

---

## Dataset

**Dataset Used:** Sample Superstore Dataset

The dataset contains information related to:

* Orders
* Sales
* Profit
* Discount
* Product Categories
* Regions
* Customer Transactions
* Order Dates

---

## Tools and Technologies

* Power BI Desktop
* Power Query Editor
* DAX (Data Analysis Expressions)

---

## Data Preprocessing

The following data cleaning steps were performed:

* Verified data types for all columns.
* Checked for missing values.
* Removed duplicate records.
* Validated sales, profit, and discount fields.
* Created a Date Table for time-based analysis.
* Established relationships between tables.

---

## Measures Created

### Total Sales

```DAX
Total Sales = SUM('Sample - Superstore'[Sales])
```

### Total Profit

```DAX
Total Profit = SUM('Sample - Superstore'[Profit])
```

### Total Orders

```DAX
Total Orders = DISTINCTCOUNT('Sample - Superstore'[Order ID])
```

---

## Dashboard Components

### KPI Cards

* Total Sales
* Total Profit
* Total Orders

### Visualizations

* Monthly Sales Trend Analysis
* Sales Forecasting Chart
* Sales by Category
* Sales by Region

---

## Key Findings

* Total sales exceeded $2.30 million.
* Total profit reached approximately $286.40 thousand.
* More than 5,000 customer orders were processed.
* Monthly sales exhibited noticeable fluctuations and seasonal patterns.
* Historical trends showed overall business growth.
* Forecasting predicted stable future sales performance.
* Confidence intervals highlighted possible future sales variations.
* Predictive analytics supported better business planning and decision-making.

---

## Conclusion

This project successfully applied predictive analytics techniques to historical sales data using Power BI. The dataset was cleaned, transformed, and analyzed to uncover business insights and sales trends. Interactive dashboards and forecasting models were developed to predict future sales performance. The project enhanced understanding of predictive modeling, trend analysis, business intelligence, and data-driven decision-making using Power BI.

---

## Skills Gained

* Data Cleaning and Preprocessing
* Power BI Dashboard Development
* DAX Calculations
* Data Visualization
* Trend Analysis
* Forecasting
* Predictive Analytics
* Business Intelligence Reporting

---

## Future Improvements

* Implement advanced forecasting models.
* Incorporate machine learning-based predictions.
* Add customer segmentation analysis.
* Build automated reporting workflows.
* Integrate real-time business data sources.

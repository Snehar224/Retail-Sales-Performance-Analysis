# **Retail Sales Performance Analysis – Power BI**

This project is a complete Power BI dashboard built to analyze retail sales across regions, product categories, and customer segments.
It includes data cleaning, modeling, DAX calculations, and interactive visual insights.

##  Project Overview

The goal of this project is to understand:

* Which products and categories drive the most revenue & profit
* How sales vary across different regions
* Which items have low profit margins
* Customer segment performance
* Return patterns and product performance trends


##  What’s Included

* Cleaned & validated Sales dataset
* Star Schema data model (Orders, Product, Customer, Date)
* DAX measures for Sales, Profit, Margin %, Trends
* 4-page interactive Power BI dashboard
* Final business insights & recommendations


##  Data Cleaning

Performed in Power Query:

* Removed duplicates
* Fixed missing values
* Standardized date formats
* Cleaned product, region, and category fields
* Created a proper Date table


## Data Model (Star Schema)

**Fact Table:**

* Orders

**Dimension Tables:**

* Product
* Customer
* Date

This model improves performance and makes DAX easier.


##  Dashboard Pages

* **Sales Overview** — KPIs, sales trends, category/region performance
* **Customer & Region Analysis** — segment performance, regional sales
* **Return Analysis** — return quantity, trends, return %
* **Product Profitability** — margin %, best/worst products, final insights
  

##  Key DAX Measures

```DAX
Total Sales = SUM(Orders[Sales])
Total Profit = SUM(Orders[Profit])
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)
```


##  Key Insights

* A few categories drive most revenue and profit
* Some regions show strong performance; others lag
* Several products have low profit margins
* Customer buying behavior varies by segment
* Returned products highlight potential quality issues

##  Recommendations

* Promote high-profit, high-demand products
* Review low-margin and frequently returned items
* Focus marketing on low-performing regions
* Improve quality checks on high-return products


##  Tools Used

* Power BI Desktop
* Power Query
* DAX
* Data Modeling

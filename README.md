# Customer Insights & Sales Analytics Dashboard

## Overview

This project is an interactive **Power BI dashboard** designed to provide a comprehensive view of sales performance, customer behaviour, product performance, and returns.

The dashboard brings together multiple business perspectives to help answer questions such as:

* How much revenue is being generated?
* Which products and categories perform best?
* Where are customers located?
* Who are the customers making purchases?
* What payment methods are being used?
* How many new customers are being acquired?
* Which regions and cities generate the most sales?
* How frequently are orders being returned?
* Which products and regions may require further investigation?

The project demonstrates how business data can be transformed into interactive visual insights that support data-driven decision-making.

---

## Dashboard Pages

The Power BI report contains four main analytical pages.

### 1. Sales Overview

The **Sales Overview** page provides a high-level view of overall sales performance.

Key metrics and visualisations include:

* Total Revenue
* Average Revenue per Sale
* Units Sold
* Sales by Month
* Quantity Sold by Month
* Sales by Category
* Sales by Region
* Top 5 Cities

Users can also filter the analysis by:

* Year
* Region
* Category
* Product

This page provides a starting point for understanding overall business performance and identifying important sales trends.

---

### 2. Customer Insights

The **Customer Insights** page focuses on customer behaviour and purchasing patterns.

Key metrics and visualisations include:

* Total Customers
* Average Purchase Value
* Percentage of New Customers
* Sales by Customer Type
* Sales by Payment Type
* Sales by Region
* Sales by Category
* Sales by City
* Salesperson-level revenue

The page can help identify differences between customer groups and provide insight into customer acquisition, purchasing behaviour, and geographic performance.

---

### 3. Return Analysis

The **Return Analysis** page focuses on product and order returns.

Key metrics include:

* Total Returns
* Total Returned
* Percentage of Orders Returned
* Returns by Region
* Returns by Month
* Percentage of Returns by City

The analysis can be used to identify locations and periods experiencing higher levels of returns and to support further investigation into potential operational or product-related issues.

---

### 4. Details by Product

The **Details by Product** page provides a more granular view of individual transactions and products.

The detailed table includes information such as:

* Category
* Customer Type
* Delivery Status
* Payment Method
* Product
* Region
* Salesperson
* Revenue
* Unit Price
* Units Sold

Additional metrics include:

* Total Revenue
* Total Units Sold
* Total Products

This page allows users to move from high-level business insights into more detailed product and transaction-level analysis.

---

## Key Business Questions

The dashboard is designed around several practical business questions:

### Sales Performance

* What is the overall revenue performance?
* Which months generate the highest sales?
* Which categories contribute the most revenue?
* Which regions and cities are performing strongly?
* Which products generate significant sales?

### Customer Behaviour

* How many customers are purchasing?
* What proportion of customers are new?
* What is the average purchase value?
* How do customer types differ in their purchasing behaviour?
* Which payment methods are most commonly used?

### Product Performance

* Which products generate the most revenue?
* Which products have the highest unit sales?
* How do products perform across different regions and customer types?

### Returns

* What percentage of orders are returned?
* Which regions experience more returns?
* Are returns increasing or decreasing over time?
* Which cities have a higher proportion of returns?

---

## Tools & Technologies

* **Microsoft Power BI**
* Power BI Data Model
* DAX measures
* Interactive data visualisation
* Business intelligence and reporting
* Data filtering and drill-down analysis

---

## Dashboard Structure

```text
Customer Insights Power BI Dashboard
│
├── Sales Overview
│   ├── Total Revenue
│   ├── Average Revenue per Sale
│   ├── Units Sold
│   ├── Sales by Month
│   ├── Sales by Category
│   ├── Sales by Region
│   └── Top 5 Cities
│
├── Customer Insights
│   ├── Total Customers
│   ├── Average Purchase Value
│   ├── New Customers
│   ├── Customer Type
│   ├── Payment Type
│   ├── Sales by Region
│   └── Sales by Category/City
│
├── Return Analysis
│   ├── Total Returns
│   ├── Returned Orders
│   ├── Return Percentage
│   ├── Returns by Region
│   ├── Returns by Month
│   └── Returns by City
│
└── Details by Product
    ├── Product Performance
    ├── Revenue
    ├── Units Sold
    ├── Customer Type
    ├── Delivery Status
    ├── Payment Method
    └── Salesperson
```

---

## How to Use the Dashboard

1. Open the `.pbix` file using **Microsoft Power BI Desktop**.
2. Navigate between the four report pages using the page navigation.
3. Use the available filters to analyse specific:

   * Years
   * Regions
   * Categories
   * Products
4. Select individual visual elements to cross-filter other visuals.
5. Use the **Details by Product** page for more granular analysis.
6. Refresh the dataset when connected to the relevant source to update the report.

---

## Business Value

The dashboard provides a consolidated view of sales, customers, products, and returns rather than requiring users to analyse each area separately.

It can support:

* Sales performance monitoring
* Customer segmentation
* Product performance analysis
* Regional performance analysis
* Customer acquisition monitoring
* Return monitoring
* Management reporting
* Identification of areas requiring deeper investigation

The overall analytical flow is:

**Sales → Customers → Products → Returns → Business Insights**

---

## Potential Future Improvements

The dashboard could be extended with additional analysis such as:

* Customer lifetime value (CLV)
* Customer retention and churn analysis
* Repeat-purchase rate
* Product profitability
* Gross margin analysis
* Sales forecasting
* Return-rate analysis by product
* Customer segmentation
* RFM analysis
* Salesperson performance targets
* Year-over-year growth
* Month-over-month growth
* Automated anomaly detection

---

## Project Purpose

This project demonstrates the application of **business intelligence and data visualisation techniques to convert business data into actionable insights**.

Rather than focusing only on individual KPIs, the dashboard connects sales, customer, product, geographic, and return information to provide a broader view of business performance.

---

## Author

**Hellen Mati Moses**

Data Analyst | Data Engineer | Business Intelligence

GitHub: https://github.com/Hmati
LinkedIn: https://www.linkedin.com/in/hellen-mati/

---

## Note

The dashboard's KPI values and visual outputs depend on the underlying Power BI dataset and model. Users should refresh the report against the relevant data source before using the dashboard for current business reporting.

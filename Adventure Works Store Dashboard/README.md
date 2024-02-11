# Adventure Works Store Dashboard<img src="..\_assets\power-bi.png" align="right" width="80" /><!-- omit in toc -->


# Table Of Content<!-- omit in toc -->
- [Dashboard](#dashboard)
- [Dataset](#dataset)
- [Data Model](#data-model)
- [Solution](#solution)
  - [Executive Summary Page](#executive-summary-page)
  - [Customer Details Page](#customer-details-page)


# Dashboard

<div style="display: flex; justify-content: center;">
  <div style="margin-right: 20px;">
    <img src="Assets\exec_summary_page.jpg" width="800">
  </div>
  <div>
    <img src="Assets\customer_detail_page.png" width="800">
  </div>
</div>


# [Dataset](https://github.com/hossam-elshabory/MS-Power-BI-Projects/tree/main/Adventure%20Works%20Store%20Dashboard/Dataset)
The Adventure Works public dataset is a robust collection of CSV files containing essential data for analyzing sales and customer behavior. It includes:

- Sales files spanning three years (2015-2017).
- `AdventureWorks_Calendar.csv`
- `AdventureWorks_Customers.csv`
- `AdventureWorks_Products.csv`
- `AdventureWorks_Product_Categories.csv`
- `AdventureWorks_Product_Subcategories.csv`
- `AdventureWorks_Territories.csv`
- `AdventureWorks_Returns.csv`

This dataset provides a rich source of information for building insightful and actionable dashboards using Power BI, allowing users to gain valuable insights into customer trends and sales performance.

****

# Data Model

<img src="data_model.png" alt="Data Model" width="500" style="display: block; margin: auto;" />
</p>

The Adventure Works Power BI dashboard solution uses a data model consisting of **two fact tables** and **six lookup tables**. 

The **sales** and **returns** fact tables provide detailed information on sales and returns over time. 

The lookup tables, such as the calendar and product tables, provide additional context and are linked together using primary and foreign keys to create a relational structure. 

This structure allows for flexible data analysis and insightful visualizations, providing users with actionable insights into sales trends, customer behavior, and product performance to support informed business decisions.

****

# Solution
The Adventure Works dashboard solution is a two-page Power BI report.

## Executive Summary Page

<details>
<summary>Click To View The Page</summary>

<div style="text-align:center"><img src="Assets\exec_summary_page.jpg" /></div>
</details>

The Adventure Works executive summary provides a comprehensive overview of monthly revenue, orders, and returns, as well as total orders by subcategory. 

This page includes dynamic visualizations, including a tree graph and a horizontal bar chart, which allow users to drill down into specific regions and time periods. 

Additionally, the dashboard features two cards displaying the top products by profit and orders, respectively. 

With its interactive filters, this dashboard solution enables Adventure Works stores to make informed business decisions based on the latest sales trends and metrics.

## Customer Details Page

<details>
<summary>Click To View The Page</summary>

<div style="text-align:center"><img src="Assets\customer_detail_page.png" /></div>
</details>

The Adventure Works customer details page is a comprehensive Power BI report that provides insight into customer behavior. 

This page includes two doughnut charts showing orders by income level and gender, a line and bar chart displaying total orders and revenue by month, a table showing customer names, total orders, and revenue, and a card highlighting the top customer in terms of revenue. 

With its interactive filters, this dashboard solution enables Adventure Works stores to gain a deeper understanding of their customer base and make informed business decisions based on customer behavior and preferences.

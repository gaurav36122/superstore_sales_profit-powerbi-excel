# 🛒 Superstore Sales & Profit Dashboard – Power BI Project

## 📊 Overview

This **Superstore Power BI Dashboard** provides a comprehensive overview of sales and profit data to help businesses make data-driven decisions.
It enables tracking of key metrics such as total sales, total cost, total profit, total orders, returns, and customer insights across categories, sub-categories, regions, and people.
## 📸 Dashboard Preview

![Sales Dashboard](https://github.com/gaurav36122/superstore_sales_profit-powerbi-excel/blob/main/Dashboard-%20By%20Sales.png?raw=true)

![Profit Dashboard](https://github.com/gaurav36122/superstore_sales_profit-powerbi-excel/blob/main/Dashborad%20by%20profit.png?raw=true)

---

---

## 🎯 Objectives

* To analyze overall **sales performance** across categories, sub-categories, and regions.
* To monitor **profit trends** and identify high-performing products, customers, and regions.
* To track **returns, costs, and quantities** for better financial insights.
* To create interactive dashboards for **dynamic business decision-making**.
* To visualize data using **charts, KPIs, and slicers** for easy interpretation.

---

## 🧠 Key Insights

* Total sales, cost, profit, and total orders.
* Sales performance by **category, sub-category, segment, region, and person**.
* Profit analysis by **top customers, cities, states, and regions**.
* Trend analysis for **top sub-categories and years**.
* Interactive visualizations for **quarterly and yearly insights**.

---

## 🧩 Tools & Technologies Used

* **Power BI** – Data visualization and dashboard creation
* **Microsoft Excel / CSV** – Data cleaning and preparation
* **Power Query** – Data transformation and loading
* **DAX (Data Analysis Expressions)** – Calculated measures and KPIs

---

## 🗂️ Dataset Information

### Orders Sheet Columns

| Column Name   | Description                                         |
| ------------- | --------------------------------------------------- |
| Order ID      | Unique identifier for each order                    |
| Order Date    | Date the order was placed                           |
| Ship Date     | Date the order was shipped                          |
| Ship Mode     | Mode of shipment                                    |
| Customer ID   | Unique ID for each customer                         |
| Customer Name | Name of the customer                                |
| Segment       | Customer segment (Consumer, Corporate, Home Office) |
| Country       | Country of the customer                             |
| City          | City of the customer                                |
| State         | State of the customer                               |
| Postal Code   | Postal code of the customer                         |
| Region        | Sales region                                        |
| Product ID    | Unique product identifier                           |
| Category      | Product category                                    |
| Sub-Category  | Product sub-category                                |
| Product Name  | Name of the product                                 |
| Sales         | Sale amount                                         |
| Quantity      | Number of products sold                             |
| Discount      | Discount applied                                    |
| Profit        | Profit from the order                               |

### Returns Sheet Columns

| Column Name | Description                         |
| ----------- | ----------------------------------- |
| Returned    | Indicates if the order was returned |
| Order ID    | Unique order identifier             |

### People Sheet Columns

| Column Name | Description                    |
| ----------- | ------------------------------ |
| Person      | Name of the person responsible |
| Region      | Region assigned to the person  |

---

## 📈 Dashboard Features

* **KPIs / Cards:** Total Sale, Total Cost, Total Profit, Total Orders, Total Returns
* **Sales Dashboard:** Year slicer, Column chart for Sales by Category & Segment, Map by Region, Line chart for Top 5 Sub-Categories, Bar chart for Sales by Top States, Donut chart for Sales by Category %, Column chart for Sales by Region
* **Profit Dashboard:** Quarter slicer, Decomposition Tree for Profit by Category & Sub-Category, Column chart for Sales & Profit by Top 5 Customers, Bar chart for Profit by Top 6 Cities, Donut chart for Profit by Top 6 States, Column chart for Profit by Year, Column chart for Profit by Category
* **Interactive View:** Users can filter by year, quarter, region, category, customer, or person

---

## 🧾 DAX Measures Used

* `Total Cost = SUM(Superstore[Cost])`
* `Total Sale = SUM(Superstore[Sales])`
* `Total Orders = COUNT(Superstore[Order ID])`
* `Total Return = SUM(Superstore[Return])`
* `Total Profit = SUM(Superstore[Profit])`

---



## 💡 Conclusion

This Superstore Power BI dashboard empowers business analysts to:

* Monitor **sales, profit, and returns trends** effectively.
* Identify **top-performing categories, customers, regions, and people**.
* Make informed **data-driven business decisions** using interactive dashboards.

---

## 🏷️ Hashtags

#PowerBI #Superstore #DataVisualization #BusinessIntelligence #DAX #Dashboard #SalesAnalysis #ProfitAnalysis #Returns #PeopleAnalysis

---

## 👤 Author

**Gaurav Singh**
📧 Email: *(gaurav36122@email.com)*
💼 LinkedIn: (www.linkedin.com/in/gaurav-singh-692b24273)

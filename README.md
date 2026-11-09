# Adventure Works Sales Analytics Dashboard

An interactive Power BI report that analyses sales performance across products, regions, salespeople and customers, built on Microsoft's AdventureWorks sample data.

> **Note:** This project uses the public AdventureWorks sample dataset. It demonstrates report design, KPI definition and DAX, not real business results.

## Report pages

### 1. Overview
An executive snapshot of sales performance.
- KPI cards: Revenue, Orders, Profit, Profit Margin and Growth
- Revenue by region
- Year-over-year revenue and profit trend
- Profit by product category
- Year slicer and page navigation


### 2. Product & Sales Performance
Product and sales-ownership analysis.
- Top contributing salespeople by revenue
- Units sold by region
- Orders with vs without discount
- Orders booked by month
- Year slicer


### 3. Customer Analytics
Customer-side analysis.
- KPI cards: Total Customers, New Customers and Returning Customers
- Customers by region
- Top 5 customers by revenue


## Measures
The report uses custom DAX measures in a `calculations` table:

| Measure | Used for |
|---|---|
| Revenue | Sales value across regions, years, salespeople and customers |
| Profit | Profit by year and product category |
| Profit Margin | Overview KPI card |
| Growth | Overview KPI card |
| Orders | Order volume by month and by discount status |
| Units Sold | Units by region |
| Total Customers | Customer counts overall and by region |
| New Customers | Customer Analytics KPI card |
| Returning Customers | Customer Analytics KPI card |

## Data model
The model combines these AdventureWorks entities: sales order details, sales territory, product subcategory and category, person (salespeople), customer, and a date table.

## Business questions the report answers
- How are revenue and profit changing year over year?
- Which regions and product categories drive revenue and profit?
- Which salespeople contribute the most revenue?
- How do orders with and without a discount compare?
- How many customers are new vs returning, and who are the top customers?

## Interactivity
- Year slicer to change the reporting period
- Navigation buttons to move between the three pages

## How to open
1. Download `Adventure_Works.Siddarth.pbix`
2. Open it in Power BI Desktop

## Tools
Power BI Desktop, DAX

## Documentation
See `Adventure_Works_Dashboard_Documentation.Siddarth.pdf` for a 2-page overview of the report structure, data flow and the business questions each page supports.

## Author
Siddarth Varma Epuri | [LinkedIn](https://linkedin.com/in/siddarthve) | [GitHub](https://github.com/siddarth-hub)

# Sales Performance Dashboard (Power BI)

An interactive Power BI dashboard analysing sales, profit and margin across regions, categories and products. It is the Power BI rebuild of the sales dataset I first analysed in [Excel and SQL](https://github.com/aarond0796/sales-analysis).

## Preview

A PDF export is  included

## Objective

Give a clear, at-a-glance view of business performance so a user can quickly see:

- How much sales, profit and margin we are generating
- Which regions, categories and products perform best
- How sales and profit change month to month

## Data Model

| Table | Purpose |
|-------|---------|
| **Orders** | Fact table with the sales transactions (Category, Region, Product, sales, profit, units) |
| **Calendar** | Date table used for month-based analysis |

## Measures

Total Sales, Total Profit, Total Orders, Units Sold, Profit Margin %

## Dashboard Features

- **KPI cards:** Total Sales, Total Profit, Profit Margin % and Total Orders
- **Line chart:** Total Sales and Total Profit by month
- **Bar chart:** Total Sales by region
- **Donut chart:** Total Sales share by category
- **Product table:** Units Sold, Total Sales, Total Profit and Profit Margin % per product
- **Slicers:** Filter the whole page by Region, Category and Month
- **Key insights panel:** Summary of the main findings

## Key Insights

- Electronics drives about 80% of sales (£8,680 of £10,840).
- London is the top region at £3,210 in sales.
- February profit (£2,140) beat January (£1,755).
- Headphones have the highest margin (50%) and laptops the lowest (30%).

## Tools Used

- Power BI Desktop
- DAX
- Excel (data source)

## How to Open

1. Download `Sales_Performance_Dashboardv2.pbix` from this repo.
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows only).
3. If prompted, update the data source to point to your local copy of the Excel file.


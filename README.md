# retail-sales-performance-dashboard
This project features a retail sales performance dashboard built in Excel. It tracks key KPIs (sales, profit, cost, quantity), analyzes product and category profitability, state performance, delivery status, gender distribution, and monthly sales trends, providing insights to improve inventory, operations, and marketing
# Retail Sales Performance Dashboard

**Author:** Maureen Emesiana  
**Tools:** Microsoft Excel (Power Query, PivotTables, PivotCharts, Slicers)  
**Preview:** `screenshots/RetailSalesDashboard.png`

## Overview
A dynamic Excel dashboard that visualizes retail sales performance across product lines, categories, states, delivery statuses, gender distribution and monthly sales trends. KPIs update with slicer selections.

## Business Problem
This dashboard helps retail operations and commercial teams answer:
- Which products/categories drive profit?
- Where should we focus marketing and stock?
- Are delivery and fulfillment healthy?
- What are seasonal sales patterns?

## Files
- `RetailSalesDashboard.xlsx` — Excel workbook (cleaned, interactive)
- `data/sample_dataset.csv` — anonymized sample dataset used to build the dashboard
- `screenshots/RetailSalesDashboard.png` — dashboard preview image
- `docs/DataDictionary.md` — data column descriptions

## How it was built (high level)
1. Cleaned and transformed raw sales data (Power Query).
2. Calculated Revenue & Profit columns.
3. Built PivotTables and associated PivotCharts for each visual.
4. Created KPI cards using cell-linked values / `GETPIVOTDATA`.
5. Added slicers (Order Date, State, Delivery Status, Category) for interactivity.
6. Styled charts and formatted for a dark theme dashboard.

## Key insights
- Laptops (and Gadget/Electronics categories) are the main profit drivers.
- Delivered orders are ~43% but cancellations + pending are high — operational improvement required.
- Monthly peak around July — plan inventory and promotions accordingly.

## Recommendations
- Increase laptop/gadget stock and promote accessories as add-ons.
- Investigate fulfillment partners and reduce cancellations.
- Target marketing and logistics improvements in top-performing states.

## Reproduce locally
1. Open `data/sample_dataset.csv` in Excel.
2. If using the workbook: open `RetailSalesDashboard.xlsx` and enable editing.
3. Use slicers on the Dashboard sheet to explore the data.

## License
MIT



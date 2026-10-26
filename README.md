# Sales Analysis & Interactive Dashboard (2025)

> **Note:** This project uses a **simulated dataset** (1,000 online-store orders for 2025). It is not real company data.

**Live dashboard:** https://jiyaverma142.github.io/sales-analysis-dashboard/

![Dashboard preview](images/dashboard.png)

## Business question

Which regions, product categories and months drive revenue for an online store, and how should sales be tracked on one dashboard?

## What I did

- **Cleaned the data** (1,025 raw rows to 1,000): removed 25 duplicates, standardised 40 inconsistent Region spellings, and filled 20 blank Payment_Method values with "Unknown".
- **Added calculated columns:** `Sales = Quantity * Unit_Price * (1 - Discount)` and `Month`.
- **Analysed** sales by region, category, payment method and month.
- **Built an interactive web dashboard** with filters and charts.

## Key insights

- **Overall:** INR 35.4 lakh across 1,000 orders (average order value about INR 3,540). Top region is West, top category is Electronics, and the peak month is November.
- **Categories:** Electronics (33.8%) and Home & Kitchen (31.7%) bring in about two-thirds of revenue. Fashion has the most orders (298) but only 23.1% of sales.
- **Top products:** Smart Watch and Air Fryer together make about 30% of revenue from only 13% of orders, because each order is high value.
- **Seasonality:** October and November are the peak months. Together they bring in about 26% of the year's sales, and November is the highest at INR 4.9 lakh.
- **Customers:** Returning customers generate 55.5% of sales, but new and returning customers spend almost the same per order (about INR 3,500).
- **Payments:** UPI is the most used method at 40.8% of sales. Cash on Delivery is 12.8%.

### Recommendations

- Run promotions on Electronics and Home & Kitchen in the weak months (April, August).
- Stock up and plan campaigns ahead of October and November.
- Look at why East lags behind and whether more marketing there would help.

## Files

| File | Purpose |
|---|---|
| `data/Sales_Analysis_Dashboard.xlsx` | Raw data and cleaned data |
| `index.html` | Interactive web dashboard (Chart.js) |
| `images/dashboard.png` | Screenshot of the dashboard |

## Tools

Excel (data cleaning, formulas), HTML, JavaScript, Chart.js

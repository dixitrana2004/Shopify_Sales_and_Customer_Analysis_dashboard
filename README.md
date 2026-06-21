# Shopify | Sales & Customer Analysis Dashboard

An interactive **Power BI** dashboard analyzing Shopify e-commerce transaction, customer, and retention data — built to surface actionable insights on sales trends, customer behavior, payment methods, and regional performance.

![Shopify Sales & Customer Report](Shopify_Sales_and_Customer_Analysis_dashboard.png)

## 📊 Overview

This project transforms raw Shopify sales data into a single-page, decision-ready dashboard covering:

- **Transaction Performance** — Net Sales, Total Quantity, Net Avg Order Value
- **Customer Behavior** — Total Customers, Repeated vs. Non-Repeated Customers
- **Retention & Value KPIs** — Lifetime Value, Repeat Rate, Purchase Frequency
- **Trends Over Time** — Sales by day and by hour
- **Regional Overview** — Sales distribution by city/state on a map
- **Mode of Payment** — Breakdown by payment gateway
- **Net Sales by Product Type** — Top and underperforming categories

## 🗂️ Repository Contents

| File | Description |
|---|---|
| `Shopify_dashboard.pbix` | Power BI dashboard file (open in Power BI Desktop) |
| `Shopify_Sales.xlsx` | Source/raw sales dataset used to build the dashboard |
| `Detailed_Insights_and_Analysis.docx` | Written analysis and strategic recommendations derived from the dashboard |
| `Shopify_Sales_and_Customer_Analysis_dashboard.png` | Static preview/screenshot of the dashboard |

## 🔑 Key Metrics at a Glance

| Metric | Value |
|---|---|
| Net Sales | $4M |
| Total Quantity | 8K |
| Net Avg Order Value | $562.59 |
| Total Customers | 4,425 |
| Non-Repeated Customers | 2,388 |
| Repeated Customers | 2,037 |
| Lifetime Value | $943.375 |
| Repeat Rate | 46.03% |
| Purchase Frequency | 1.7 |

## 💡 Key Insights

- **High-value, lower-volume transactions** point to a premium/bundled product mix rather than a high-volume discount model.
- **Repeat rate (46%)** is healthy but leaves room to grow through remarketing, email flows, and loyalty programs.
- **Sales peak between 12 PM–4 PM**, with lulls overnight (12 AM–7 AM) — useful for timing ad spend and flash sales.
- **Washington, Houston, New York City, El Paso, and Dallas** are the top 5 cities by sales, with strong concentration on the East Coast and Midwest.
- **Shopify Payments** dominates the payment mix (58%+), reducing third-party processing dependency; PayPal and Amazon Pay fees present a cost-reduction opportunity.
- **Sportswear and outdoor equipment** are the strongest product categories, while clogs, boots, and wallets underperform and may need repositioning.

Full analysis and strategic recommendations are available in [`Detailed_Insights_and_Analysis.docx`](./Detailed_Insights_and_Analysis.docx).

## 🛠️ Tools Used

- **Power BI** — dashboard design, DAX measures, visuals
- **Excel** — source data preparation
- **Word** — written insights and analysis report

## 🚀 How to Use

1. Clone or download this repository.
2. Open `Shopify_dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
3. Use the **Gateway** and **Province** slicers on the left to filter the report.
4. Click through the left navigation buttons (Net Sales, Total Quantity, Total Customers, etc.) to explore different views.

## 📌 Notes

- Data is illustrative/sample Shopify sales data for portfolio and analysis purposes.
- Currency values are in USD.

---

*Built as a data analysis portfolio project to demonstrate dashboarding, KPI design, and insight generation from e-commerce data.*

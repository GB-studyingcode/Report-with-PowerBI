# Power BI Project Insights — Supply Chain & Sales Dashboard

## Dataset Overview
- Records: **9,994 order-line transactions** from **2014-01-02 to 2017-12-30**.
- Coverage: **5,009 orders**, **793 customers**, **1,862 products**, **49 states**, and **4 regions**.
- Total sales: **$2.30M**, total profit: **$286.4K**, total cost: **$2.01M**, profit margin: **12.5%**.
- Average discount: **15.6%**; return rate by line item: **8.0%**; average shipping lead time: **34.6 days**.

## Dashboard Structure Parsed from PBIX
- **Sale** page: 18 visuals (slicer: 8, cardVisual: 5, donutChart: 1, lineChart: 1, clusteredBarChart: 1, actionButton: 1, clusteredColumnChart: 1).
- **Supply Chain** page: 17 visuals (slicer: 7, cardVisual: 4, clusteredColumnChart: 2, pivotTable: 1, actionButton: 1, clusteredBarChart: 2).
- **Customer** page: 14 visuals (slicer: 6, cardVisual: 3, donutChart: 2, hundredPercentStackedColumnChart: 2, clusteredBarChart: 1).

## Key Business Insights
1. **Technology is the strongest category by sales and profit**: Technology generated **$0.84M** sales and **$145.5K** profit, making it the most attractive category for growth and inventory prioritization.
2. **Regional performance is uneven**: the **West** region contributed the highest profit at **$108.4K**, while **Central** delivered the weakest profit at **$39.7K**. This suggests region-level pricing, fulfillment, and sales strategies should be managed separately.
3. **Discounting has a clear margin risk**: the **>30%** discount bucket has the lowest margin at **-48.2%**, showing that aggressive discounts may increase sales but destroy profitability.
4. **Some sub-categories are loss makers**: Tables ($-17.7K), Bookcases ($-3.5K), Supplies ($-1.2K). These should be reviewed for pricing, supplier cost, discount policy, or delivery cost issues.
5. **Consumer segment is the largest demand base**: Consumer accounts for **$1.16M** in sales and **$134.1K** in profit, making it the main segment for retention and promotion campaigns.
6. **Shipping mode impacts service experience**: **Same Day** has the shortest average lead time at **0.9 days**, while **Standard Class** is slowest at **41.9 days**. This can be used to define SLA-based logistics recommendations.
7. **Product concentration is visible but not extreme**: the top 5 products generated **$153.4K**, equal to **6.7%** of total sales. This supports SKU-level inventory monitoring without over-relying on only a few products.
8. **Salesforce performance can be benchmarked**: **Anna Andreadi** generated the highest profit at **$108.4K**, which can be used as a benchmark for sales coaching and regional account allocation.
9. **Growth momentum improved in 2016**: sales grew by **29.5% YoY**, highlighting a period that deserves deeper analysis of product mix, customer acquisition, and promotion effectiveness.
10. **Geographic demand is concentrated**: **California** is the top state with **$0.46M** in sales, useful for warehouse placement, last-mile planning, and regional marketing decisions.

## Suggested GitHub Positioning
Use this as a **Business Intelligence / Power BI Analytics** portfolio project focused on sales performance, profitability, supply chain service levels, customer segmentation, and operational decision support.

## Screenshot
![Dashboard Overview](sale_dashboard_overview.png)

## Bullet Points
- Built an interactive Power BI dashboard analyzing sales, profit, product mix, customer segments, regional performance, returns, discounts, and shipping lead time from 9,994+ order-line transactions.
- Identified profitability drivers and risks, including **$2.30M** total sales, **$286.4K** profit, **12.5%** margin, **8.0%** return rate, and **34.6-day** average delivery lead time.
- Designed executive-level KPI pages for Sales, Supply Chain, and Customer analysis, enabling decision support for inventory planning, discount control, logistics SLA improvement, and regional sales strategy.
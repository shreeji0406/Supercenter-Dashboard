**Project Overview**: This Power BI project analyzes sales and profitability performance for a retail superstore using the Sample Superstore dataset. The goal was to identify key drivers behind revenue, profit, and margin variation across product categories, regions, and customer segments.

**Business Challenge** : Despite healthy sales, the company observed inconsistent profit margins across regions and categories. Leadership needed a clear, visual understanding of:
- Which categories and regions generate the highest profits.
- How discounts influence overall profitability.
- Which segments or margin bands are driving sustainable growth.

**Key Insights**
- Technology leads all categories, contributing around 55% of total profit.
- Furniture maintains strong sales but struggles with margins, especially in the Central region.
- The West region performs best, achieving a 14.9% margin and leading in both sales and profit.
- High-margin products (>30%) represent roughly 40% of total revenue.
- Higher discounts are directly linked to lower profitability.

**Recommendations**
- Review discount policies in low-margin regions, particularly Central.
- Focus marketing on Technology to sustain its performance.
- Reassess Furniture pricing and sourcing to improve profitability.
- Prioritize high-margin products to strengthen long-term growth.

**Tools & Techniques**
- Power BI: Data modeling, DAX calculations, and visual design
- Power Query: Data transformation and cleaning

•	DAX Formulas:
- Margin % = DIVIDE(Profit, Sales)
- Margin Band = SWITCH(TRUE(), ...)
- Visuals Used: KPI cards, line chart, bar chart, bubble chart, and dynamic slicers

**Dataset** : The dataset includes key retail metrics such as Category, Region, Segment, Sales, Profit, Discount, Quantity, and Order Date.

Dashboard Highlights
- screenshot : https://github.com/shreeji0406/Supercenter-Dashboard/blob/main/Dashboard%20Screenshot.png

**Outcome** : This dashboard converts raw sales data into actionable insights that help decision-makers optimize discounts, improve product strategies, and boost overall profitability.

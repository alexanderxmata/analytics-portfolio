# Inventory Planning & Reorder Point Optimization

## Business Problem
Inventory planners lacked visibility into demand variability and reorder point effectiveness, leading to frequent stockouts for high-demand items and excess inventory for low-demand SKUs.

## Tools Used
- SQL
- Excel
- Power BI

## Data
Simulated inventory and demand data including SKU-level demand, lead time, safety stock, reorder points, and on-hand inventory.

## Analysis Summary
- Analyzed SKU-level demand patterns and lead time variability using SQL
- Calculated reorder points and safety stock requirements based on demand volatility
- Modeled inventory scenarios in Excel to evaluate stockout risk and carrying cost tradeoffs
- Built Power BI dashboards to monitor inventory health and reorder performance

## Key Insights
- High-demand SKUs with long lead times experienced the highest stockout risk
- Several low-velocity SKUs consistently carried excess inventory
- Small adjustments to reorder points significantly reduced stockout frequency

## Recommendations
- Increase reorder points for high-demand, high-variability SKUs
- Reduce safety stock for low-demand, stable SKUs
- Implement SKU segmentation to prioritize inventory planning efforts

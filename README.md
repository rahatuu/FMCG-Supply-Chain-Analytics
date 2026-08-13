# FMCG Supply Chain Analytics & Executive Dashboard

## Project Overview

This project analyzes FMCG supply-chain data to provide an executive-level view of sales, procurement, inventory, demand forecasting, and replenishment risk.

The project was developed to demonstrate how data analytics and visualization can support supply-chain decision-making by transforming operational data into actionable KPIs and interactive dashboards.

## Business Objectives

The dashboard was designed to help supply-chain stakeholders:

* Monitor overall sales revenue and procurement cost
* Track inventory value over time
* Compare actual demand with forecast demand
* Identify warehouses with higher reorder risk
* Compare inventory levels with reorder points
* Analyze sales performance across regions
* Support inventory and replenishment planning

## Tools & Technologies

* Tableau
* Supply Chain Analytics
* Data Visualization
* KPI Analysis
* Demand & Inventory Analysis

## Key KPIs

| KPI                              |  Result |
| -------------------------------- | ------: |
| Total Sales Revenue              |  33.43M |
| Total Procurement Cost           |  21.47M |
| Total/Cumulative Inventory Value | 525.24M |
| Reorder Risk                     |   5.52% |

## Dashboard Components

### 1. Actual vs Forecast Demand

Compares actual units sold with forecast demand across the months to evaluate how closely the demand forecast tracks actual demand.

### 2. Monthly Inventory Value Trend

Tracks changes in inventory value across the year and helps identify periods of significant inventory movement.

### 3. Monthly Procurement Cost Trend

Shows monthly procurement expenditure and supports analysis of procurement-cost patterns.

### 4. Reorder Risk by Warehouse

Compares reorder risk across warehouses. WH_5 showed the highest reorder risk among the warehouses analyzed.

### 5. Sales Revenue by Region

Provides a regional comparison of sales revenue to identify differences in regional contribution.

### 6. Inventory Level vs Reorder Point

Compares inventory levels with reorder points for the selected Top 10 SKUs to support inventory-monitoring and replenishment analysis.

## Key Findings

* Total sales revenue was **33.43M**.
* Total procurement cost was **21.47M**.
* The calculated total/cumulative inventory value was **525.24M**.
* Overall reorder risk was **5.52%** based on the project's defined reorder-risk measure.
* Actual demand and forecast demand were relatively closely aligned.
* WH_5 showed the highest reorder risk among the warehouses analyzed.
* The dashboard provides SKU-level inventory monitoring through comparison of inventory levels and reorder points.

## Business Recommendations

1. **Prioritize WH_5 for monitoring**
   Investigate the factors contributing to its higher reorder risk and review replenishment timing and inventory thresholds.

2. **Use forecast information in inventory planning**
   Since actual and forecast demand are closely aligned, the forecast can continue to support procurement and inventory planning while being periodically validated.

3. **Investigate high inventory values**
   Review high inventory positions to distinguish between required safety/strategic stock and potentially slow-moving or excess inventory.

4. **Align procurement with demand**
   Use demand and inventory trends together when planning procurement to balance product availability with inventory investment.

5. **Monitor high-inventory SKUs against reorder points**
   Prioritize SKU-level review where inventory positions indicate potential replenishment or inventory-management concerns.

## Dashboard

The final Tableau dashboard provides a consolidated executive view of the supply-chain metrics and analyses described above.

## Project Structure

```text
FMCG-Supply-Chain-Analytics/
│
├── README.md
├── Tableau/
│   └── FMCG_Supply_Chain_Executive_Dashboard.twbx
├── Dashboard/
│   └── FMCG_Supply_Chain_Dashboard.png
├── Data/
│   └── processed_supply_chain_dataset.csv
└── Documentation/
    └── Project_Report.pdf
```

## Outcome

This project demonstrates the application of data analytics and visualization to FMCG supply-chain problems, including demand planning, inventory monitoring, procurement analysis, and warehouse-level replenishment risk.





# FMCG Supply Chain Analytics & Executive Dashboard

## Project Overview

This project analyzes FMCG supply-chain data to provide an executive-level view of sales, procurement, inventory, demand forecasting, and replenishment risk.

The project was developed to demonstrate how data analytics and visualization can support supply-chain decision-making by transforming operational data into actionable KPIs and interactive dashboards.

## Business Objectives

The dashboard was designed to help supply-chain stakeholders:

* Monitor overall sales revenue and procurement cost
* Track inventory value over time
* Compare actual demand with forecast demand
* Identify warehouses with higher reorder risk
* Compare inventory levels with reorder points
* Analyze sales performance across regions
* Support inventory and replenishment planning

## Tools & Technologies

* Tableau Public
* Data Visualization
* Supply Chain Analytics
* KPI Analysis
* Demand Analysis
* Inventory Analysis

## Key KPIs

| KPI | Result |
|---|---:|
| Total Sales Revenue | 33.43M |
| Total Procurement Cost | 21.47M |
| Cumulative Inventory Value | 525.24M |
| Reorder Risk | 5.52% |

## Dashboard Components

### 1. Actual vs Forecast Demand

Compares actual units sold with forecast demand across the months to evaluate how closely the demand forecast tracks actual demand.

### 2. Monthly Inventory Value Trend

Tracks changes in inventory value across the year and helps identify periods of significant inventory movement.

### 3. Monthly Procurement Cost Trend

Shows monthly procurement expenditure and supports analysis of procurement-cost patterns.

### 4. Reorder Risk by Warehouse

Compares reorder risk across warehouses. WH_5 showed the highest reorder risk among the warehouses analyzed.

### 5. Sales Revenue by Region

Provides a regional comparison of sales revenue to identify differences in regional contribution.

### 6. Inventory Level vs Reorder Point

Compares inventory levels with reorder points for the selected Top 10 SKUs to support inventory monitoring and replenishment analysis.

## Key Findings

* Total sales revenue was **33.43M**.
* Total procurement cost was **21.47M**.
* Cumulative inventory value was **525.24M**.
* Overall reorder risk was **5.52%** based on the project's defined reorder-risk measure.
* Actual demand and forecast demand were relatively closely aligned.
* WH_5 showed the highest reorder risk among the warehouses analyzed.
* The dashboard provides SKU-level inventory monitoring through comparison of inventory levels and reorder points.

## Business Recommendations

1. **Prioritize WH_5 for monitoring**

   Investigate the factors contributing to its higher reorder risk and review replenishment timing and inventory thresholds.

2. **Use forecast information in inventory planning**

   Since actual and forecast demand are closely aligned, the forecast can continue to support procurement and inventory planning while being periodically validated.

3. **Investigate high inventory values**

   Review high inventory positions to distinguish between required safety or strategic stock and potentially slow-moving or excess inventory.

4. **Align procurement with demand**

   Use demand and inventory trends together when planning procurement to balance product availability with inventory investment.

5. **Monitor high-inventory SKUs against reorder points**

   Prioritize SKU-level review where inventory positions indicate potential replenishment or inventory-management concerns.

## Dashboard Preview

![FMCG Supply Chain Executive Dashboard](Dashboard/FMCG_Supply_Chain_Dashboard.png)

## Project Structure

```text
FMCG-Supply-Chain-Analytics/
│
├── README.md
│
├── Tableau/
│   └── FMCG_Supply_Chain_Executive_Dashboard.twbx
│
├── Dashboard/
│   └── FMCG_Supply_Chain_Dashboard.png
│
└── Data/
    └── processed_supply_chain_dataset.csv

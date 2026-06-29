# Supply Chain Analytics Project Progress

## Completed

### Environment Setup
- Created Microsoft Fabric Workspace
- Created Lakehouse: supply_chain_lakehouse
- Uploaded DataCo Supply Chain dataset

### Bronze Layer
- Loaded raw CSV into Lakehouse
- Performed data profiling
- Checked row count
- Checked column count
- Checked null values
- Checked duplicate records
- Analyzed delivery status distribution

### Silver Layer
- Removed sensitive columns:
  - Customer Password
  - Customer Email
  - Product Description

- Standardized column names:
  - lowercase
  - underscores instead of spaces

- Created Silver table:
  - silver_supply_chain

### Gold Layer
Created aggregated business table:

- gold_delivery_performance

Metrics:
- Order Count
- Average Actual Shipping Days
- Average Scheduled Shipping Days
- Total Sales

### Task Flow
Created Medallion Architecture task flow:

Get Data
→ Bronze
→ Silver
→ Gold
→ Visualize

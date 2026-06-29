# Medallion Architecture

## Bronze Layer
Raw source data loaded from CSV.

## Silver Layer
Cleaned and standardized dataset.

Transformations:
- Removed sensitive fields
- Standardized column names

Output:
- silver_supply_chain

## Gold Layer
Business-ready aggregated tables.

Current Gold Tables:
- gold_delivery_performance

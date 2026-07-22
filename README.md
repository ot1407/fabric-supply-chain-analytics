# Supply Chain Analytics Platform using Microsoft Fabric

## 📌 Project Overview

This project demonstrates an end-to-end Supply Chain Analytics solution built using Microsoft Fabric and the DataCo Smart Supply Chain dataset.

The solution follows the Medallion Architecture (Bronze, Silver, Gold) to transform raw supply chain data into business-ready analytics for reporting and decision-making.

---

## 🛠 Technologies

- Microsoft Fabric
- OneLake
- Lakehouse
- PySpark
- SQL
- Power BI
- Medallion Architecture
- GitHub

---

## 📂 Project Structure

```
architecture/
docs/
notebooks/
powerbi/
screenshots/
sql/
```

---

## 🚧 Project Status

- ✅ Workspace & Lakehouse
- ✅ Bronze Layer (Raw Data)
- ✅ Silver Layer (Data Cleaning & Standardization)
- ✅ Gold Layer (Business Marts)
- ⏳ Semantic Model
- ⏳ Power BI Dashboard

---

## 🏗️ Medallion Architecture

### Bronze
- Raw CSV ingestion into Lakehouse

### Silver
- Data cleansing
- Column standardization
- Business-ready detailed dataset

### Gold
Business-oriented aggregated tables:

- gold_delivery_performance
- gold_sales_by_category
- gold_sales_by_country
- gold_sales_by_state
- gold_shipping_mode
- gold_market_performance

---

## 📸 Architecture

![Task Flow](screenshots/task_flow.png)

---

## 📊 Gold Layer Example
![Gold Output](screenshots/gold_layer.png)


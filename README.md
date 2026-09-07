E-Commerce Data Engineering Project

Tech Stack
- Databricks
- PySpark
- Delta Lake
- Medallion Architecture

Architecture
Raw CSV
   ↓
Bronze
   ↓
Silver
   ↓
Gold

Bronze
- customers_raw
- products_raw
- orders_raw

Silver
- customers_clean	
- products_clean
- orders_clean

Gold
- sales_detail
- daily_sales_summary
- state_sales_summary
- category_sales_summary
- product_sales_summary

Key Transformations
- Deduplication
- Null handling
- Data cleansing
- Data standardization
- Joins
- Aggregations
- Data quality validation

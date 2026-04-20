# Olist Azure Data Pipeline

End-to-end data analytics pipeline built on the 
[Olist Brazilian E-Commerce dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

## Stack
- **Ingestion**: Azure Data Factory
- **Storage**: Azure Data Lake Storage Gen2 (Medallion architecture)
- **Transformation**: Azure Databricks (PySpark)
- **Warehouse**: Azure Synapse Analytics
- **Visualisation**: Power BI

## Architecture
Bronze (raw CSVs) → Silver (cleaned Parquet) → Gold (aggregated analytics)

## Status
- [x] ADLS Gen2 storage account created
- [x] Medallion folder structure created (bronze/silver/gold)
- [x] Raw CSVs uploaded to bronze/olist/
- [ ] ADF pipeline configured
- [ ] Databricks transformation notebooks
- [ ] Synapse SQL views
- [ ] Power BI dashboard

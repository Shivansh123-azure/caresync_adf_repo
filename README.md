**CareSync Health Network – End-to-End Healthcare Data Engineering Platform**

- Designed a metadata-driven Azure Data Factory framework to ingest healthcare data from multiple sources, including PostgreSQL and CSV files stored in Azure Blob Storage, using a centralized configuration table.
- Developed reusable ADF pipelines with parameterized Copy Data activities to support dynamic ingestion of multiple tables and source systems, enabling both full and incremental data loading.
- Implemented a centralized metadata and auditing framework using Azure SQL Database, maintaining configuration, audit logs, and watermark tables to track pipeline execution and manage incremental data loads.
- Developed reusable PySpark notebooks in Azure Databricks to process ingested data and implement Medallion Architecture (Bronze, Silver, and Gold) using Delta Lake tables.
- Implemented secure credential management by integrating Azure Data Factory and Databricks with Azure Key Vault to manage sensitive connection details.
- Designed an end-to-end orchestration workflow using a master ADF pipeline to execute PostgreSQL and CSV ingestion in parallel, followed by Silver-to-Gold transformations.
- Integrated Azure Logic Apps with ADF Web Activities to send customized email notifications containing pipeline execution status and load summaries.
- Integrated Azure Data Factory and Databricks with GitHub to implement source control and CI/CD practices using version-controlled development workflows.
- Leveraged Unity Catalog for data governance and planned Databricks dashboards and AI/BI Genie to enable business reporting and natural-language querying of healthcare datasets.

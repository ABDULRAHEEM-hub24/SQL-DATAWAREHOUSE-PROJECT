# SQL-DATAWAREHOUSE-PROJECT
 I am building a modern data warehouse project with SQL Server which includes ETL processes, data modeling and data analytics.
 
 This project implements the "Medallion Architecture", a layered data design approach that improves data quality, scalability, and analytics readiness. The architecture is divided into three structured layers: Bronze, Silver, and Gold, each serving a specific purpose in the data lifecycle.

Bronze Layer stores raw data ingested from multiple source systems with minimal transformation, ensuring data traceability and auditability.

Silver Layer processes and cleanses the raw data by removing duplicates, handling missing values, and applying business rules to create structured, reliable datasets.

Gold Layer contains highly refined, aggregated, and business-ready data optimized for reporting, dashboards, and advanced analytics.

The project focuses on efficient data ingestion, transformation, and optimization, enabling faster insights and better decision-making. This layered approach ensures data consistency, reusability, and performance while supporting scalable analytics solutions.

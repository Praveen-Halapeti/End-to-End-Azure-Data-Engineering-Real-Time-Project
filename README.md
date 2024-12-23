# End-to-End-Azure-Data-Engineering-Real-Time-Project

Lets build a complete End to End Azure Data Engineering Project. In this project we are going to create an end to end data platform right from Data Ingestion, 
Data Transformation, Data Loading and Reporting. 

The tools that are covered in this project are,

1. Azure Data Factory - Used for Data Ingestion. Its a ETL tool.
2. Azure Data Lake Storage Gen2 - Storage solution in Azure
3. Azure Databricks - Big Data analytics tool used for high end data analytics. Used for data transformation.
4. Azure Synapse Analytics
5. Azure Key vault
6. Azure Active Directory (AAD) and
7. Microsoft Power BI

The use case for this project is building an end to end solution by ingesting the tables from on-premise SQL Server database using 
Azure Data Factory and then store the data in Azure Data Lake. Then Azure databricks is used to transform the RAW data to the most cleanest form of data and then we are using Azure Synapse Analytics to load the clean data and finally using Microsoft Power BI to integrate with Azure synapse analytics to build an interactive dashboard. Also, we are using Azure Active Directory (AAD) and Azure Key Vault for the monitoring and governance purpose.

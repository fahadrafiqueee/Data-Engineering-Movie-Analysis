# End-to-End Data Engineering Pipeline Intergrating Microsoft Azure (Azure Data Factory-Azure Databricks) For Analyzing IMDb Movie Rating Dataset

## Data flow:
- **Extract Data:** Retrieve CSV data from Azure Blob Storage for processing
- **Transform Data:** Utilize Python and PySpark on Azure Databricks to analyze and process the data, storing the results in Azure Data Lake Storage Gen2
- **Load Data:** Transfer the processed data into an Azure SQL database to establish a reporting layer for dashboard creation
- **Automation:** Construct end-to-end pipelines in Azure Data Factory to automate the data flow from extraction to reporting layers

##  Prerequisites
- **Microsoft Azure subscription**
- **Azure Blob Storage:** Object storage service for storing large amounts of unstructured data
- **Azure Data Lake Gen2 Storage:** Scalable storage for big data analytics
- **Azure Databricks:** Analytics platform based on Apache Spark for big data processing and machine learning
- **Azure SQL Database:** Managed relational database with SQL Server compatibility
- **Azure Data Factory:** Data integration service that enables you to create, schedule, and orchestrate ETL and ELT workflows. ADF provides a visually intuitive interface to build data-driven workflows for orchestrating data movement and transforming data at scale



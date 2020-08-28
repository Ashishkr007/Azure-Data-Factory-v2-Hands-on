# Azure-Data-Factory-v2-Hands-on
* Basic-ADF-Objects
    - Linked Service
        - [Azure Data Lake Storage Gen2 Linked Service](linkedService/ADLSConnection.json) 
        - [Azure Key Vault linked service](linkedService/DevKeyVault.json)
        - [Databricks Interactive Cluster Linked Service](linkedService/Dev_Interactive_cluster.json)
        - Databricks Job Cluster Linked Service 

    - Dataset
        - [Azure Data Lake Storage Gen2 CSV Dataset](dataset/ADLS_CSV_File.json) 

    - Pipeline
        - [Copy Pipeline (ADLS to ADLS)](pipeline/Copy-Data.json) 

    - Trigger
        - [Copy Pipeline Trigger](trigger/Test-Copy-Trigger.json)

    - Pipeline 
        - [Execute Databricks Notebook (Job/Interactive cluster)](tutorial/execute-databricks-notebook/README.md)

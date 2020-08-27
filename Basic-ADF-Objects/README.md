# Basic ADF Objects
## Table of Contents
* [Linked Service](#Linked-Service)
	* [Azure Data Lake Storage Gen2 Linked Service](#Azure-Data-Lake-Storage-Gen2-Linked-Service)
	* [Azure Key Vault linked service](#Azure-Key-Vault-linked-service)
	* [Databricks Interactive Cluster Linked Service](#Databricks-Interactive-Cluster-Linked-Service)
	* [Databricks Job Cluster Linked Service](#Databricks-Job-Cluster-Linked-Service)
* [Dataset](#Dataset)
	* [Azure Data Lake Storage Gen2 CSV Dataset](#Azure-Data-Lake-Storage-Gen2-CSV-Dataset)
* [Pipeline](#Pipeline)
	* [Copy Pipeline (ADLS to ADLS)](#Copy-Pipeline-(ADLS-to-ADLS))
* [Trigger](#Trigger)
	* [Copy Pipeline Trigger](#Copy-Pipeline-Trigger)

## Linked Service
### [Azure Data Lake Storage Gen2 Linked Service](linkedService/ADLSConnection.json) 
![ADLS2-Linked-Service](images/ADLS2-Linked-Service2.png "ADLS2-Linked-Service")
### [Azure Key Vault linked service](linkedService/DevKeyVault.json)
![Key-Vault-Linked-Service](images/Key-Vault-Linked-Service2.png "Key-Vault-Linked-Service")
### [Databricks Interactive Cluster Linked Service](linkedService/Dev_Interactive_cluster.json)
![Databricks-Interactive-Cluster-Linked-Service](images/Databricks-Interactive-Cluster-Linked-Service.png "Databricks-Interactive-Cluster-Linked-Service")
### Databricks Job Cluster Linked Service
![Databricks-Job-Cluster-Linked-Service](images/Databricks-Job-Cluster-Linked-Service.png "Databricks-Job-Cluster-Linked-Service")

## Dataset
### [Azure Data Lake Storage Gen2 CSV Dataset](dataset/ADLS_CSV_File.json) 
![ADLS2-CSV-Dataset](images/ADLS2-CSV-Dataset.png "ADLS2-CSV-Dataset")

## Pipeline
### [Copy Pipeline (ADLS to ADLS)](pipeline/Copy-Data.json) 
![ADLS-CSV-Copy-Pipeline-1](images/ADLS-CSV-Copy-Pipeline-1.png "ADLS-CSV-Copy-Pipeline-1")

![ADLS-CSV-Copy-Pipeline-2](images/ADLS-CSV-Copy-Pipeline-2.png "ADLS-CSV-Copy-Pipeline-2")

## Trigger
### [Copy Pipeline Trigger](trigger/Test-Copy-Trigger.json)
![Pipeline-Trigger](images/Pipeline-Trigger.png "Pipeline-Trigger")

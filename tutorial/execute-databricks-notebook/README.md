# Execute Databricks Notebook (Job/Interactive cluster)
In this tutorial, we are executing a databricks notebook from Azure data factory pipeline. We have given example for both type of cluster(Interactive / Job). We have added some parameter that will be passed to notebook for execution. In case of job cluster, linked service has some parameter for "clusterVersion","nodeType","workerCount","SparkLogPath","initScript".

### [Pipeline](pipeline/databricks-notebook-exec-example.json) 
![databricks-notebook-exec-pipeline](images/databricks-notebook-exec-pipeline.png "databricks-notebook-exec-pipeline")
### Pipeline Execution Result
![databricks-notebook-exec-pipeline](images/databricks-pipeline-exec-result.png "databricks-notebook-exec-pipeline")

### [Interactive cluster Linked Service](linkedService/Dev_Interactive_cluster.json)
![Databricks-Interactive-Cluster-Linked-Service](images/Databricks-Interactive-Cluster-Linked-Service.png "Databricks-Interactive-Cluster-Linked-Service")
### [Job cluster Linked Service](linkedService/Dev_Job_Cluster.json)
![Databricks-Job-Cluster-Linked-Service](images/Databricks-Job-Cluster-Linked-Service.png "Databricks-Job-Cluster-Linked-Service")
### [Key Vault Linked Service](linkedService/DevKeyVault.json)


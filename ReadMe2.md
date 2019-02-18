# Databricks workshop

This is a multi-part (free) workshop featuring Azure Databricks. It covers basics of working with Azure Data Services from Spark on Databricks with Chicago crimes public dataset, followed by an end-to-end data engineering workshop with the NYC Taxi public dataset, and finally an end-to-end machine learning workshop.  The workshop is offered in Scala and Python.<br>

The goal of this workshop is deliver a clear understanding of how to provision Azure data services, how the data services services integrate with Spark on Azure Databricks, to give you end to end experience with basic data engineering and basic data science on Azure Databricks, and to share some boilerplate code to use in your projects.<br>  

This is a community contribution, so we appreciate feedback and contribution.<br>

## Target audience:
Architects and Data engineers<br>

##  Pre-requisite knowledge:
Prior knowledge of Spark, is beneficial, as is familiarity/experience with Scala/Python wuthout or without Spark in context.

## Azure pre-requisites:
A subscription with at least $200 credit for a continuous 10-14 hours of usage.<br>

## 1.  Module 01-Primer:
This module covers basics of integrating with Azure Data Services from Spark on Azure Databricks in batch mode and with structured streaming.<br>

![primer](images/1.png)

At the end of this module, you will know how to provision, configure, and integrate from Spark with-<br>
1.  Azure storage - blob storage, ADLS gen1 and ADLS gen2; Includes Databricks Delta as well<br>
2.  Azure Event Hub - publish and subscribe in batch and with structured streaming; Includes Databricks Delta<br>
3.  HDInsight Kafka - publish and subscribe in batch and with structured streaming; Includes Databricks Delta<br>
4.  Azure SQL database - read/write primer in batch and structured streaming<br>
5.  Azure SQL datawarehouse - read/write primer in batch and structured streaming<br>
6.  Azure Cosmos DB (core API - SQL API/document oriented) - read/write primer in batch and structured streaming; Includes structured streaming aggregation computation<br>
7.  Azure Data Factory - automating Spark notebooks in Azure Databricks with Azure Data Factory version 2<br>
8.  Databricks secrets management<br>

The Chicago crimes dataset is leveraged in the lab.<br>

## 2.  Data Science Workshops:
This module focuses on ML pipeline and also a deep learning pipeline using tensorFlow.

In the ML workshop the following are covered:
1.  Ingest data and cleanse data using a DE pipeline<br>
2.  Feature Engineering<br>
3.  Model training and hyperparameter tuning using CrossValidator<br>
4.  Persist the trained model<br>
5.  Create batch predictions out of the best model<br>
6.  Finally persist the predictions on a SQL Server database for downstream consumption<br>

the DL workshop consists of
1. Working with image data:
2. Loading images natively in Spark DataFrames
3. Transfer learning, a super quick way to leverage deep learning
4. Distributed hyperparameter tuning via Spark MLlib Pipelines
5. Applying deep learning models at scale to images, using your own or known popular models, to make predictions or transform them into features
6. Working with general tensors:
7. Applying deep learning models at scale to tensors of up to 2 dimensions
8. Deploying Models in SQL:

Distributed Deep Learning is not in scope and will be offered as a separate workshop.

## Next
[Provisioning guide](docs/1-provisioning-guide/ProvisioningGuide.md)<br>
[Lab guide](docs/2-lab-guide/README.md)



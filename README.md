# Azure Synapse Analytics training

Presentations and labs for Synapse Analytics custom two-day training.

- [Azure Synapse Analytics training](#azure-synapse-analytics-training)
  - [Day 1](#day-1)
    - [Day 1 labs](#day-1-labs)
  - [Day 2](#day-2)
    - [Day 2 labs](#day-2-labs)

## Day 1

Building a modern data warehouse with **Azure Synapse Analytics**. We introduce Synapse Analytics and its components and features. Then we focus on data engineering tasks, working with files of different types stored in the data lake. The tasks include data ingestion, exploration, transformation, and loading, using a mix of serverless Spark pools and serverless SQL pools. Next, we explore ways to load data into dedicated SQL pools and how to build data pipelines to load and transform data in an automated and repeatable way.

### Day 1 labs

- [**Lab 1: Perform Data Engineering and exploration**](labs/day1/lab1/README.md) (60 minutes)
  - Perform Data Exploration in Synapse Studio
  - Ingesting data with Spark notebooks in Azure Synapse Analytics
  - Transforming data with DataFrames in Spark pools in Azure Synapse Analytics
  - Integrating SQL and Spark pools in Azure Synapse Analytics
  - Import sales data with PolyBase and COPY using T-SQL
- [**Lab2: Build automated data integration pipelines with Azure Synapse Pipelines**](labs/day1/lab2/README.md) (60 minutes)
  - Petabyte-scale ingestion with Azure Synapse Pipelines
  - Code-free transformation at scale with Azure Synapse Pipelines
    - Create data pipeline to import poorly formatted CSV
    - Create Mapping Data Flow for top product purchases
  - Orchestrate data movement and transformation in Azure Synapse Pipelines
- [**Lab 3: Run interactive queries using serverless SQL pool with Azure Synapse Analytics**](labs/day1/lab3/README.md) (60 minutes)
  - Querying a Data Lake Store using serverless SQL pools in Azure Synapse Analytics
  - Securing access to data through using a serverless SQL pool in Azure Synapse Analytics
- [**Lab 4: Optimize a Data Warehouse with dedicated SQL Pools in Azure Synapse**](labs/day1/lab4/README.md) (60 minutes)
  - Understanding developer features of Azure Synapse Analytics
  - Using data loading best practices in Azure Synapse Analytics
  - Optimizing data warehouse query performance in Azure Synapse Analytics
  - Improve query performance

## Day 2

Building on the foundations covered in Day 1, we continue with performance and monitoring. Next, we cover data science in Synapse Analytics, using Azure Machine Learning and Spark pools. Then, we move on to security within the Synapse Workspace and its related components. Finally, we create Power BI reports within Synapse Analytics against files stored in the data lake.

### Day 2 labs

- [**Lab 1: Optimize a Data Warehouse Part 2**](labs/day2/lab1/README.md) (60 minutes)
  - Check for skewed data and space usage
  - Understand column store storage details
  - Study the impact of wrong choices for column data types
  - Study the impact of materialized views
  - Avoid extensive logging
- [**Lab2: End-to-end security with Azure Synapse Analytics**](labs/day2/lab2/README.md) (30 minutes)
  - Securing Azure Synapse Analytics supporting infrastructure
  - Securing the Azure Synapse Analytics workspace and managed services
  - Securing Azure Synapse Analytics workspace data
- [**Lab 3: Machine Learning**](labs/day2/lab3/README.md) (60 minutes)
  - Training models
  - Registering and using models in Synapse Analytics
  - Training and batch scoring with a recommender, using Spark ML
- [**Lab 4: Build reports using Power BI**](labs/day2/lab4/README.md) (30 minutes)
  - Power BI and Synapse workspace integration
  - Optimizing integration with Power BI
  - Visualize data with SQL serverless and create a Power BI report
- [**(Optional) Lab 5: Support Hybrid Transactional Analytical Processing with Azure Synapse Link**](labs/day2/lab5/README.md) (45 minutes)
  - Configuring Azure Synapse Link with Cosmos DB
  - Querying Cosmos DB with Apache Spark for Synapse Analytics
  - Querying Cosmos DB with SQL Serverless for Synapse Analytics

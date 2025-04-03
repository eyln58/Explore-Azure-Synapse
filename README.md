# Azure Synapse Analytics Exploration Project

## Project Overview
This project highlights my hands-on experience with **Azure Synapse Analytics**, a unified platform for end-to-end data analytics in the cloud. The objective was to explore its core features, such as data ingestion, processing, and analysis, using its integrated tools and components like SQL pools, Apache Spark pools, and Azure Data Lake Storage. This exercise served as an introductory overview of Synapse’s capabilities, completed as part of the **DP-203 Azure Data Engineer** certification preparation.

The project took approximately **60 minutes** to complete and involved setting up a Synapse workspace, ingesting data, analyzing it, and managing resources effectively.

## Project Steps

### Provisioning the Azure Synapse Analytics Workspace
- **Objective:** Establish a Synapse workspace to manage data and processing runtimes.
- **Process:**  
  - Used the Azure Portal and PowerShell Cloud Shell to clone a GitHub repository with exercises.
  - Ran a setup script to deploy a Synapse workspace, Data Lake Storage, a dedicated SQL pool, and an Apache Spark pool within a resource group.
- **Outcome:** Successfully created a fully functional Synapse environment.

### Exploring Synapse Studio
- **Objective:** Get familiar with Synapse Studio’s interface and features.
- **Process:**  
  - Accessed Synapse Studio to explore sections like Data, Develop, Integrate, Monitor, and Manage.
  - Reviewed the workspace’s built-in serverless SQL pool, dedicated SQL pool, and Spark pool.
- **Outcome:** Understood Synapse Studio’s layout and the purpose of its key components.

### Ingesting Data with a Pipeline
- **Objective:** Import data into Azure Data Lake Storage for analysis.
- **Process:**  
  - Used the Copy Data tool in Synapse Studio to create a pipeline.
  - Configured the pipeline to pull a CSV file from an HTTP source and store it in the Data Lake.
  - Monitored the pipeline until it completed successfully.
- **Outcome:** Successfully transferred the data file into the Data Lake and verified its presence.

### Analyzing Data with a Serverless SQL Pool
- **Objective:** Query and analyze Data Lake data using SQL.
- **Process:**  
  - Created a SQL script to retrieve and summarize data from the ingested CSV file.
  - Generated a chart to visualize product counts by category.
- **Outcome:** Analyzed the data effectively and saved the script for future use.

### Analyzing Data with a Spark Pool
- **Objective:** Process data using PySpark in an Apache Spark pool.
- **Process:**  
  - Created a notebook to load the CSV data into a DataFrame.
  - Performed grouping and counting operations, then visualized the results with a chart.
- **Outcome:** Processed and visualized data using PySpark, saving the notebook for reference.

### Querying a Dedicated SQL Pool
- **Objective:** Analyze structured data in a relational data warehouse.
- **Process:**  
  - Resumed the dedicated SQL pool and queried a preloaded sales table.
  - Aggregated sales data by year, month, and product, then saved the query.
- **Outcome:** Successfully analyzed structured data and paused the pool to manage resources.

### Resource Cleanup
- **Objective:** Prevent unnecessary Azure costs.
- **Process:** Ensured all resources were paused or shut down after use.
- **Outcome:** Demonstrated effective resource management practices.

## Key Outcomes
- Provisioned and configured an Azure Synapse Analytics workspace.
- Ingested data from an external source into Azure Data Lake Storage using a pipeline.
- Analyzed data using serverless SQL and Spark pools, generating actionable insights and visualizations.
- Queried a dedicated SQL pool for structured data warehouse scenarios.

## What I Learned
- **Azure Synapse Analytics:** Gained practical experience with its unified platform, including Synapse Studio and its integration with SQL pools, Spark pools, and Data Lake Storage.
- **Data Ingestion:** Learned to design pipelines to move and manage data from external sources into a cloud environment.
- **SQL and PySpark:** Developed skills in querying data with SQL and processing large datasets with PySpark for flexible analysis.
- **Resource Management:** Understood the importance of provisioning, monitoring, and shutting down cloud resources to optimize costs and performance.
- **DevOps Basics:** Explored automated provisioning with scripts, a key practice for production workflows.

This project provided a strong foundation in Azure Synapse Analytics and its role in modern data engineering.

## Connect with Me
Feel free to reach out or follow my journey on [LinkedIn](https://www.linkedin.com/in/eyilan/).

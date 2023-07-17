# [Microsoft Azure Data Engineering and Analytics Masterclass Course](https://learn.microsoft.com/en-us/certifications/exams/dp-203/)

In this course, we will get the expertise in integrating, transforming, and consolidating data from various structured, unstructured, and streaming data systems into a suitable schema for building analytics solutions.

This repository contains instructions and assets for hands-on exercises to support the Microsoft Certified: Azure Data Engineer Associate certification (DP-203). The exercises are designed to complement the associated training modules on Microsoft Learn, and a subset of these exercises comprises the hands-on labs.

[Certification Exam Reference](https://learn.microsoft.com/en-us/certifications/exams/dp-203/)

## Course Syllabus

<details>
 <summary> <b> Module-01: Introduction to Cloud Computing, Microsoft Azure and Data Engineering :computer: </b>  </summary>
  
 *  Introduction to Cloud Computing
 
 *  Microsoft Azure Overview | Organization Hierarchy | Web-services | Billing 
  
 *  Introduction to Data Engineering | Different Roles and Responsibilities | IaaS vs PaaS
  
 *  Introduction to Data Pipelines | Data Ingestion, Storage, Processing & Analysis | Explore & Visualize
 
 *  Understand *Relational* & *Non-relational* data storage with real world scenario
 
 *  Understand *High availability* and *Disaster Recovery* concepts
  
 *  Real-world use cases
  
 *  Case study
     
</details>

<details>
 <summary> <b> Module-02: Design & Implement Data Storage (Relational DB) - Azure SQL| Azure Synapse Analytics :book: </b>  </summary>
  
  *  What is Data? | Relational Database Primer | Case studies
  
  *  Explore various file formats
  
 *  Explore <b>*Azure SQL*</b> service
    - Azure SQL Overview
    - Internals of Database engine
    - Lab: Setting-up Azure SQL Instance
    - Lab: Setting-up SQL Server Management Studio
    - Database keys Primer: Primary Keys, Foreign Keys    
    - Lab: Performing various DDL, DML actions on Azure SQL Database
    - Azure SQL: Manage multiple Databases (HA) with Node pools 
    - Azure SQL: Security | In-transit and at rest
 *  Explore <b>*Azure Synapse Analytics*</b> service
    - What is Data Warehouse?
    - Azure Synapse analytics service overview | Architecture
    - Lab: Create Azure Synapse Analytics workspace
    - Azure Synapse Analytics: Compute options
    - Lab: Prepare data-sets and other pre-requisites
    - Lab: Working to external tables | SQL Pools | Loading data into the Pool
    - Designing a Data Warehouse
    - Lab: Building a Fact table | Dimention Table | Transfer data to SQL pool
    - Azure Synapse Analytics: Pricing
</details>
<details>
 <summary> <b> Module-03: Design & Implement Data Storage (Non-Relational DB) - Azure Data Lake| Cosmos DB 💽: </b>  </summary>
  
 *  Introduction to Non-relational Database | Case studies
 
 *  Explore <b>*Azure storage services*</b> 
    - Azure Blob
    - Azure Queue
    - Azure File Share
    - Azure Table
 
 *  Introduction to Data Lake | Azure Data Lake Storage Gen2 | Azure Blob Storage
 
 *  Explore <b>*Azure Cosmos DB*</b> | Features | Performance | Scaling | HA | Security
    - Understand Cosmos DB resource model
    - Lab: Create an Azure Cosmos DB account, database, container, and items from the Azure Portal/PowerShell/ARM Template
    - Understand Cosmos DB Modelling & Paritioning | Partition Keys
    - Lab: Demonstrate the use of Partition keys in Cosmos DB
    - Azure Synapse Link for Azure Cosmos DB
    - Azure Cosmos DB Analytical Store
 </details>
 <details>
    <summary> <b> Module-04: Design & Develop Data Processing Solutions - ADF| Event Hubs| Stream Analytics :gear: </b> </summary>
 
  *  Understand Extract, Transform and Load (ETL) | Data Pipeline
 
  *  Explore <b>*Azure Data Factory*</b> service
     - Introduction to Azure Data Factory
     - Lab: Create a Data Pipeline to move data from source to destination service
     - Lab: Create a Data Pipeline to covnvert .csv data to .parquet data
     - Lab: Use Azure Data Factory Ingest Copy action for data transfer
     - Working with Cache sink and Lookup concepts in ADF
     - Lab: Demonstrate how cache sink works | Data prep | Cache sink implementation
     - Self-hosted integration runtimes (Ex Pysical Machine/VM to Azure Synapse)
     - Lab: Demonstrate self-hosted integration runtimes for data transfer
     - Azure Data Factory: Schema Drift and Validation
  *  Explore <b>*Azure Event Hubs*</b> service
     - Batch Processing vs Real-time Processing vs Stream Processing
     - Introduction to Azure Event Hubs
     - Lab: Create a Namespace and an Azure Event Hub Instance into it
     - Lab: Sending and Receiving event from Azure Event Hub using custom application
  *  Explore <b>*Azure Stream Analytics*</b> service 
     - Introduction to Azure Stream Analytics
     - Lab: Working with Azure stream analytics job | Define | Execute
     - Lab: Enable diagnostics logs for Azure Data Lake
     - Lab: Reading the Azure Blob diagnostics
     - Running Azure Stream Analytics jobs
     - Debugging Azure Stream Analytics jobs
     - Integrate *Microsoft Power BI* with *Azure Stream Analytics jobs* for displaying as an output
     - Lab - Demonstrating some more Data Factory features | Mapping Data Flow | Copyin to sink | Storage event trigger
 </details> 
 <details>
    <summary> <b> Module-05: Design & Develop Data Processing Solutions - Scala| Python| Apache Spark| Azure DataBricks :gear: </b></summary>
 
  *  <b>*Scala Programming Primer*</b>
     -  Introduction to *Scala* programming language
     -  Scala programming constructs | Variables | Looping statements | Conditional statements | Functions
     -  Lab - Demonstrate various Scala programming constructs 

  *  <b>*Python Programming Primer*</b>
     - Introduction to Python Programming
     - Python programming constructs | Variables | Looping statements | Conditional statements | Functions
     - Demonstrate various Scala programming constructs 

  *   Working with [<b>*Jupyter Notebook*</b>](https://jupyter.org/)

  *   Working with Spark pools in Azure Synapse Analytics

  *   Lab: Working with Spark pools | Load Data | Grouping the results | Write data to Azure Synapse

  *   Explore <b>*Azure Databricks*</b>
      - Introduction to Databricks & Azure Databricks
      - Understand Azure Databricks concepts - Workspace | Runtime | Pricing (DBUs)|  Security | Scaling | Interfaces
      - Lab: Create Azure Databricks Workspace and Cluster
      - Lab: Create a new Notebook to read data from a .parquet file using spark
      - Lab: Create a new Notebook to read data from a .json file using spark
      - Lab: Demonstrate streaming data using Azure Databricks
      - Lab: Run Databricks jobs on a schedule or continuously - Scheduled trigger | Continuous trigger
      
 </details> 
 <details>
 <summary> <b> Module-06: Design & Implement Data Security 🛡️ </b>  </summary>
  
 *  Azure Data Lake Gen2 security
    - Access Keys
    - Shared Access Token (SAS)
    - Azure AD
    - Access Control Lists
 
 *  Lab: Granting access to Azure Data Lake using Azure AD as Identity provider
 
 *  Explore <b>*Azure Key Vault*</b>
 
 *  Understand concept of Azure Managed Identities and Application Objects
 
 *  Azure Data Factory: Data Encryption
 
 *  Azure Synapse: Data Encryption | Data Masking | Column & Row level security
 
 </details>
 <details>
 <summary> <b> Module-07: Monitor and Optimize Data storage and Data processing - Microsoft Purview| Azure Monitor 🥽 </b></summary>
  
 *  Explore [<b>*Microsoft Purview*</b>](https://www.microsoft.com/en-in/security/business/microsoft-purview)
    - Monitoring data pipelines and Azure Services - Azure Data Lake | Azure Data Factory
 
 *  Explore [<b>*Azure Monitor*</b>](https://learn.microsoft.com/en-us/azure/azure-monitor/) service
    - Alert rules
    - Activity Logs
    - Insights
 
 *  Monitoring & Logging: Azure Synapse workloads | Azure Stream Analytics | Azure Databricks
 
 *  Optimizing Azure Data Lake Gen2 storage cost: Access tiers & Lifecycle Policies
 
 *  Best practices for storing files in Data Lake 
   
 </details>
 <details>
    <summary> <b> Module-08: Continuous Integration and Continuous Delivery (CI CD) for Azure Data Factory ⏩:</b></summary>
  
 *  What is CI CD?
 
 *  Overview of Azure DevOps | Azure Repos | Azure Pipeline
 
 *  Lab: Azure Data Factory Environment Setup - Git Repos | Manual Build | Release Pipeline | Pre-post deployment tasks
 </details>
 <details>
    <summary> <b> Module-09: Google Cloud Platform Data Engineering Services ☁️:</b></summary>
  
 *  Google Cloud Platform Primer
 
 *  GCP Data Storage services
    - Binary Storage services - Cloud Storage
    - Database services - Cloud SQL, Cloud Spanner
    - Data Processing services - BigQuery, Dataflow and DataProc
    - Visualization - Looker, Data Studio
 </details>
  
## Project Ideas

[Project-01: Automate Create 3-tier application infrastructure provisioning using ARM Templates and deploy it using PowerShell & Portal]()
  
[Project-02: Create an end-to-end CI CD pipeline for Application deployment using Azure DevOps services]()
  
[Project-03: Establish connectivity between two networks using Azure network connectivity services]()

## Contact
Website: [Novatec IT Services](https://novatec.co.in/)

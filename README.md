# Azure Data Factory Data Pipeline

The foundation of this project relies on ECDC Covid-19 Data, which is acquired through the HTTP connector in Azure Data Factory. Subsequently, the data is transferred to Azure Data Lake Gen 2 and undergoes transformation through Azure Data Flow, Databricks, and HDInsight. Following this transformation, the processed data is loaded into Azure SQL Database, enabling the generation of insights using Microsoft Power BI. 

## Installation of Azure Storage Account
This guide provides step-by-step instructions for setting up an Azure Storage Account, which is essential for storing and managing your project's data in the cloud.

### Prerequisites
- [Azure Account](https://portal.azure.com/)
- [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
  
### Steps

### 1. Create a Storage Account

Visit the [Azure Portal](https://portal.azure.com/) and log in with your Azure account. Follow these steps to create a new Storage Account:

1. Click on "Create a resource."
2. Search for "Storage Account" and select it from the list.
3. Click "Create" and fill in the required information, including:
   - **Subscription:** Choose your subscription.
   - **Resource Group:** Create a new one or select an existing one.
   - **Storage Account Name:** Choose a unique name.
   - **Location:** Choose the region for your storage account.
   - Leave other settings as default or adjust as needed.
4. Click "Review + create" and then "Create" to initiate the creation process.

## Installation of Azure Data Factory 

This guide provides step-by-step instructions for setting up Azure Data Factory to facilitate seamless data workflows. The Azure Data Factory instance will be linked to a GitHub repository for version control and collaborative development.

### Prerequisites
Before proceeding with the installation, make sure you have the following prerequisites:

#### Azure Subscription: Ensure you have an active Azure subscription.
#### GitHub Account: Create a GitHub account if you don't have one.
#### Azure Data Factory Account: Set up an Azure Data Factory instance in your Azure portal.

# Data Flow for COVID-19 Data Analysis

## Data Acquisition
The ECDC COVID-19 data is fetched using the HTTP connector in Azure Data Factory, ensuring the retrieval of the most up-to-date information for analysis.

## Data Storage
The acquired data is stored in Azure Data Lake Gen 2, a scalable and secure storage solution that facilitates efficient data handling and management.

## Data Transformation
### Azure Data Flow
Raw data transformation is performed using Azure Data Flow, allowing for the cleaning, filtering, and enrichment of the dataset.

### Databricks
Additional data transformations and advanced analytics take place in Databricks, leveraging its powerful data processing capabilities.

### HDInsight
Big data processing tasks are efficiently handled through HDInsight, ensuring optimal performance for large-scale data processing.

## Data Loading
The processed and transformed data is loaded into an Azure SQL Database. This structured database provides a solid foundation for generating insights and running complex queries.















## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rishi-pandey-017546170)

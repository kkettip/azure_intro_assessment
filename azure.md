# azure_intro_assessment

**Storage**

1. **Azure Blob Storage** is cloud storage. It is used for the storage of large amounts of a variety of data types that includes unstructured data. Examples of data stored in Blob storage include images and videos. It is ideal for storing data for distributed access, backup, archiving, disaster recovery and analysis. Blob Storage could be accessed using the Azure Storage client library for python, which requires python 3.7 or later. Blob Storage also supports Azure Data Lake Storage Gen2.

2. **Azure Data Lake Storage Gen2** is cloud storage of data lakes that is built on Blob storage. The data stored is encrypted at rest by Microsoft-managed or customer-managed encryption keys. It is ideal for use with big data analytics. The type of data stored in Azure Data Lake Storage Gen2 is not restricted to type or size. It works with Hadoop and allows for the storage of data as a hierarchy of directories and nested subdirectories. Azure Data Lake Storage Gen2 could be accessed by installing the Azure DataLake Storage client library for Python, which requires python 3.7 or later.


**Compute**

1. **Azure App Service** is for hosting web applications, REST APIs, and mobile back ends. Azure App Service supports a variety of languages and frameworks such as Java, Ruby and python. It also provides autoscaling, load balancing and is ISO, SOC, and PCI compliant. Some additional features include DevOps optimization and the ability to integrate with Visual Studio Code. It also supports Python apps hosted in a Linux server environment. To develop a Python web app, Flask or Django frameworks have to be used. The Python web app can be created and deployed in Azure App Service using Visual Studio Code, Azure CLI or Azure Portal.

2. **Azure Container Instances** allows containers to be run in Azure without managing virtual machines. Azure Container Instances is used to run and isolate one application, but multiple supporting containers can be combined with the main container. It provides fast startup times, allows for the setting of custom CPU cores and memory sizes and allows for the exposure of the container to the internet with its own IP address and domain name. The containers can be managed using Azure Python SDK.


**Database**

1. **Azure Database for PostgreSQL** is a relational database service based on the open source relational database called PostgreSQL. It provides data protections by using automatic backups and point-in-time restore, automatic maintenance and security to protect sensitive data. It is available as Single Server or Flexible Server. The single Server platform handles patching, backups and security with minimal user involvement.  While the Flexible Server allows users to configure and customize settings of the database based on their requirements. Once the Azure Database for PostgreSQL is created, python can be used to connect and query the database by installing psycopg2. 

2. **Azure SQL Database** is based on Microsoft SQL Server database engine. It is a managed platform as a service (PaaS) database engine. It is involved in upgrading, patching, backups and database monitoring without the user's involvement. It allows for the processing of relational and non relational data. To connect and query Azure SQL Database using Python, the pyodbc driver should be installed.

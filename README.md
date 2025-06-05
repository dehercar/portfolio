# [Certified Azure Data Engineer 🎓](https://learn.microsoft.com/en-us/users/davidhernandez-6060/credentials/5564a068924c3840?ref=https%3A%2F%2Fwww.linkedin.com%2F)

Contact me in:
[LinkedIn](https://www.linkedin.com/in/davhercar/)

Location: Monterrey, Mexico.

#### Technical Skills: Azure, Synapse, Data Factory, Databricks, Python, SQL Server, SSIS, Power BI, AWS Sagemaker, Tableau, GIT

## Azure Projects

### **Productivity Predictor**
- Created a medallion schema with Dimension and Fact tables.
- Ingested SAP price update requests and raw material prices (REST API) via Azure Data Factory pipelines to calculate productivity impacts using Databricks.
- Used KERAS to develop Neural Networks for predicting parts cost and estimate impact productivity.
- Used and Optimize Synapse SQL Pools allowing direct connections from Power BI and Tableau.

### Appbot Datawarehouse
- Implemented an ELT solution using medallion architecture to track Mobile App data from Appbot REST API.
- Performed data profiling analysis and adhoc transformations in silver layer.
- Created gold layer in Synapse SQL Pool.
- Developed deployment plan using Jenkins.

### Azure Migration Project
- Migrated project in Azure to align with new business requirements
- Explored old setup and implemented new setup with Synapse SQL Pool replacing Databricks Delta table.
- Partition of tables by daily partitions with millions of rows.

### Part Number Matcher
- Data Orchestration with Data Factory and Databricks to build an NLP powered Part number matcher at scale used downstream by business to improve grouping of similar part numbers.


## Other Data Projects

### **UNSPSC Categorizer** 
NLP tool developed in Python using RegEx, NLTK and scikit-learn (Tfidf, SVM) and Descriptions-UNSPSC labels as datasource (csv) to retrieve UNSPSC for a given part description.

[See repository.](https://github.com/dehercar/UNSPSC_Categorizer)

### **Sea Level Predictor** 
The objective of this project is to predict sea levels for 2050 based on a dataset of global sea levels since 1880.

This project in Jupyter Notebook uses Pandas, Numpy, Scipy and Matplotlib.

[See repository.](https://github.com/dehercar/sea_level_predictor) 


### **Cardiac Diseases**
These modules were developed to perform data analysis over a dataset of 70k patients. Variables like blood preasure, height, weigth, patologies, etc were examinated on them.

By analyzing demographic, medical and habits data we want to determine if they can lead into a cardiac disease.

[See repository.](https://github.com/dehercar/medical_data)


### Blacklist System
This project was made for a Debt Collection team. 

The objective of this project is to have a control of blocked phone numbers and emails for clients with problems in their credits.

It was implemented using Windows Forms automated with Excel Macros as GUI and connected to SQL Server database secured by Windows Authentication.

**Git and Github for version control in all projects.**

**General automations with Power Automate, dataloader.io, DemandTools and Web Scraper Platform.**

# Data science - Data engineering

Contact me in:
[LinkedIn](https://www.linkedin.com/in/davhercar/)

Location: Monterrey, Mexico.

#### Technical Skills: Python, SQL Server, SSIS, Power BI, AWS Sagemaker, Tableau, GIT

## Relevant Projects

### [UNSPSC Categorizer](https://github.com/dehercar/UNSPSC_Categorizer)
NLP tool developed in Python using RegEx, NLTK and scikit-learn (Tfidf, SVM) and Descriptions-UNSPSC labels as datasource (csv) to retrieve UNSPSC for a given part description.

### **Part Number Matcher**
This Power BI dashboard uses as datasource conclusions about similarities on Part Numbers to identify duplicated developed with Python and using RegEx, fuzzywuzzy and PyODBC library to connect to SQL Server, as well as gathering data from other Power BI datasources using DAX Studio. Datasource length about 1 million rows.

### **Productivity Predictor**
This is a Tableau dashboard developed for a Procurement Community whose datasource (3 million rows) has future productivity predictions at part number level with two main purposes:
1. Give visibility of future impacts on productivity based on cost trends.
2. Find money leakage opportunities that impacts productivity by getting the gap of cost based on issued invoices and past submitted price udpate requests (e.g. PIR in SAP).

#### 1. Future Productivity
- **unit cost predictions** based on cost predictions (a) and submitted price update requests (b),
- forecasting procured **volumes** and
- market **raw material** indices.

##### Unit Costs

##### a. Unit Costs predictions
Tasks to predict cost were:
- Gather relevant ERP invoices data (mainly SAP) from the Datawarehouse on Tableau Server.
- Create Schema, Dimension and Fact tables in SQL Server.
- ETL with SSIS dataflows. 
- Create Views using relevant hierarchies following business rules.
- Query SQL View in Python using PyODBC and Pandas
- Do data analysis with matplotlib and find correlations in cost changes.
- Digest data with numpy to be read by KERAS API.
- Use KERAS to develop Neural Networks that predicts future costs deployed in AWS Sagemaker.


##### **b. Price Update Requests**
- Gather data from Price Update Requests in SQL Server database using conditional Joins
- Create trigger database objects to insert rows. 


##### Volumes
- Gather data from Tableau Server with forecast volumes at part number level made by different areas.
- Creation of SQL Server Tables to store. 
- ETL with SSIS dataflows.
- Load data with PyODBC as described in Unit Costs predictions section.


##### Market Raw Material Indices
- Gather Market Raw Material Indices data from SQL Server to Python.
- Get cost breakdowns implementing financial calculations to Market Indices in Total Parts Cost manipulating and merging data with Pandas.


#### 2. Money Leakage
- Join Price Update Requests and issued Invoices data to find Productivity GAP comparing prices using efficient conditional Joins with relevant date fields among others.

The Tableau dashboard was made with features such as merge datasources, blend relationships, use of parameters, LOD expressions, etc.

### [Sea Level Predictor](https://github.com/dehercar/sea_level_predictor) 
The objective of this project is to predict sea levels for 2050 based on a dataset of global sea levels since 1880.

This project in Jupyter Notebook uses Pandas, Numpy, Scipy and Matplotlib.


### Blacklist System
This project was made for a Debt Collection team. 

The objective of this project is to have a control of blocked phone numbers and emails for clients with problems in their credits.

It was implemented using Windows Forms automated with Excel Macros as GUI and connected to SQL Server database secured by Windows Authentication.

**Git and Github for version control in all projects.**

**General automations with Power Automate, dataloader.io, DemandTools and Web Scraper Platform.**

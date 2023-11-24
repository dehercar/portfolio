# Machine Learning Engineer

#### Technical Skills: Python, SQL Server, SSIS, Power BI, AWS Sagemaker, Tableau, GIT

## Projects

### **UNSPSC Categorizer**
This is a NLP tool I developed in Python using RegEx, NLTK and scikit-learn (Tfidf, SVM) and Descriptions-UNSPSC labels as datasource (csv).

### **Part Number Matcher**
This tool matches Part Numbers among them by looking at the characters content developed in Python and using RegEx, and for connecting to SQL Server Data base use of pyodbc module. 

### **Productivity Predictor**
This project was developed for a Procurement Community and predicts productivity at part number level with two main purposes:
1. Give visibility of future impacts on productivity based on cost trends.
2. Find money leakage opportunities that impacts productivity by getting the gap of cost based on issued invoices and past submitted price udpate requests (e.g. PIR in SAP).

#### 1. Future Productivity
- **unit cost predictions** based on cost predictions (a) and submitted price update requests (b),
- forecasting procured **volumes** and
- market **raw material** indices.


##### a. Unit Costs predictions
Tasks to predict cost were:
- Gather relevant ERP invoices data (mainly SAP) from the Datawarehouse on Tableau Server.
- Create Schema, Dimension and Fact tables in SQL Server.
- ETL with SSIS dataflows. 
- Create Views using relevant hierarchies following business rules.
- Query SQL View in Python using PyODBC and Pandas
- Do data analysis with matplotlib and find correlations in cost changes.
- Digest data with numpy to be read by KERAS API.
- Use KERAS to develop Neural Networks that predicts future costs.


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


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

1. Future Productivity
- **cost predictions** based on correlations (1) and submitted price update requests (2),
- forecasting procured **volumes** and
- market **raw material** indices.

As well this project gives  The technologies used for this were:
- SLQ

#### **Cost predictions**
Tasks to predict cost were:
- Gather relevant ERP invoices data (mainly SAP) from the Datawarehouse on Tableau Server.
- Create Schema, Dim and Fact tables in SQL Server.
- ETL with SSIS dataflows. 
- Create Views using relevant hierarchies following business rules.
- Query SQL View in Python using PyODBC and Pandas to make data analysis and find correlations in cost changes.
- Use KERAS to develop the Neural Network that predicts future costs.

#### Volumes


#### Market Raw Material Indices










33

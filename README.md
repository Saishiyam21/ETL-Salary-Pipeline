# ETL-Salary-Pipeline
Personal ETL project
In this project, we will be building an ETL pipeline for the dataset which contains salary information of the people living in San Francisco. The dataset has been downloaded from Kaggle. We extract the data from local DBFS. The dataset is in the form of csv, which consists of personal information like name, salary etc. 
We ingest the raw data into staging area using batch load and add two new columns - ingest date and ingest time.
Then we perform some cleaning and analysis using various python libraries.
Finally, we load the cleaned data into an SQL server and perform query operations. 
This is a POC for ETL pipeline. 

# QMSS 5052 Lovelytics Project

## About the Project
This project is conducted under the mentorship of Lovelytics as part of the QMSS 5052 Practicum in Data Analysis course. For this project, the main task is to conduct market segmentation clustering analysis on consumer demographic, spending and transaction data. The task has been left open for interpretation, so groups are free to adopt any strategy for clustering.    

More information can be found in *project_description.docx*.


## Code
The following scripts were first created on Databricks, and therefore are mostly written in PySpark language (and possibly some SQL). There is also code used to stream data from the Databricks data warehouse. As such, the code will have to be tweaked before these scripts can run in local Jupyter notebooks.

Code description:
- *code/ingest.ipynb* - Script that ingests (i.e. imports) datasets into the Databricks workspace from the Databricks data warehouse and outputs 'Bronze' tables.
- *code/clean.ipynb* – Script that pre-processes and cleans 'Bronze' tables to output 'Silver' tables. Imputation for missing values is also performed in this code.


## Data
2 datasets are used in this project:
- Dataset 1 contains demographic/attribute data
- Dataset 2 contains transaction frequency and spending data over Q4 2019 to Q3 2021

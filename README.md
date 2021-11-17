# QMSS 5052 Lovelytics Project

## About the project


## Code
The following scripts were first created on Databricks and therefore contain a mix of PySpark and possibly SQL language.
Code description:
- *code/ingest.ipynb* - Script that ingests (i.e. imports) datasets into the Databricks workspace and outputs 'Bronze' tables.
- *code/clean.ipynb* – Script that pre-processes and cleans 'Bronze' tables to output 'Silver' tables. Imputation for missing values is also performed in this code.


## Data
2 datasets are used in this project:
- Dataset 1 contains demographic/attribute data
- Dataset 2 contains transaction frequency and spending data over Q4 2019 to Q3 2021

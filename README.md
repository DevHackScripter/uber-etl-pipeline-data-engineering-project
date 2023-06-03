# Uber Data Anaytics | End-To-End Data Engineering Project

## Prequisite :
- Basic Python, SQL and upyter Notebook install
- GCP Service : 
    - Cloud Storage
    - Compute Engine
    - BigQuery
    - Looker
- Mage (Data pipeline tool for transforming and integrating data)

## Fact & Dimension Table
### Fact Table
- Contains quantitative measures or metrics that are used for analysis
- Typically contains foreign keys that link to dimension tables
- Contains columns that have high cardinality and change frequently
- Contains columns that are not useful for analysis by themselves, but are necessary for calculating metrics

### Dimension Table
- Contains columns that describe attributes of the data being analyzed
- Typically contains primary keys that link to fact tables
- Contains columns that have low cardinality and don't change frequently
- Contains columns that can be used for grouping or filtering data for analysis


Link For update Documentation : 
- Dashboard : https://lookerstudio.google.com/reporting/b9e7f974-55c1-4d9c-8cfe-01786b17e04b
- Source : https://github.com/darshilparmar/uber-etl-pipeline-data-engineering-project
- Draw IO : https://drive.google.com/file/d/1oRzrKgXkFVL5mU2NjdRpZ-tXKly2FR2F/view?usp=sharing
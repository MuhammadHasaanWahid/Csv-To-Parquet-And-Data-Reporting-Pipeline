# Csv-to-Parquet-and-data-reporting-pipeline
[Click here to see the dataset](https://www.kaggle.com/datasets/brittonbutler2/usa-business-entity-salescredit-data)
## Problem Statement
This Problem was to extract 800k records from csv file, convert it to parquet and store in datalake and then create report in Power BI. The major problem that I was facing that in csv data there were spaces in column names. So my pipeline was crashing again and again because I was converting data to parquet format and parquet does not support spaces in column names then I removed spaces and pipeline ran successfuly after that I fetch that parquet data
 in power bi and created a report.
  ## The Json files
 The Third Portfolio Project.json file contains information about the ADF pipeline, including the pipeline name, description, and the resources that make up the pipeline. The manifest.json file contains information about the dependencies and structure of the ARM template of the pipeline in Azure DataFactory.
 ## PowerBI Report
 ![Capture](https://user-images.githubusercontent.com/123824748/236014955-97eca896-489a-488a-881b-1506bd218697.PNG)

 




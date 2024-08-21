# Power BI Dashboard

## Background and Context
An Insurance Company based out of flodria has implemented an aggressive growth plan in 2021 across the counties. The anonymous company want to know how did their performace and growth over this period. 

## Objective
With help of power bi and python i have created a interactive dashboard to tell a story on how they performed. I used python to do ETL followed by EDA and then loaded transformed data into power bi to create a dashbord that would sumamrie their growth plan action.


## Tech Stack
- **Programming Language:** Python, DAX
- **Libraries:** pandas, numpy
- **Tools:** Google Collab, PowerBI, Github

The repository directory structure is as follows:

Insurance-Portfolio-Analysis<br>
├─ 01_SOURCE<br>
├─ 02_ETL<br>
├─ 03_DATA<br>
├─ 04_ANALYSIS<br>
├─ 05_DASHBOARD<br>
├─ 06_RESOURCES<br>

The types of content present in the directories is as follows:

**01_SOURCE**

This directory contains the the received/downloaded raw data that needs to be cleaned and organized to ease out the data analysis and visualization process.

**02_ETL**

This directory contains the ETL script that takes the raw dataset as an input, transforms it and exports an analysis-ready dataset into the _03_DATA_ directory.

**03_DATA**

This directory contains the data that can be directly used for exploratory data analysis and data visualization purposes.

**04_ANALYSIS**

This directory contains the python notebooks that analyzes the clean dataset to generate insights.

For analyzing the data with Jupyter Notebook; we have used the clean dataset present in the SQLite database.

**05_DASHBOARD**

This directory contains the markdown file with an embedded Power BI report link that visualizes the data.

The Power BI dashboard contains slicers, cross-filtering and other advance capabilities that end user can play with to visualize a specific facet of the data or, to get additional insights.

**06_RESOURCES**

This directory contains images, icons, layouts, etc. that are used in this project.

## Architecture

The project architecture is quite straight forward and can be explained through the below image:

![Process Architecture][process_workflow]

As shown in the above workflow; we are first performing necessary cleaning and transformation in the received raw dataset using Python and exporting the clean dataset as a comma-separated flat file

Finally; we leverage the clean & analysis-ready dataset for exploratory data analysis (EDA) using Jupyter Notebook and creating an insightful report using Power BI.


##Demo Dashboard 
For interactive Power BI dashboard click below Sample snippet:

[![Power BI Dashboard][dashboard_image]][dashboard_link]




<!--links of images-->
[process_workflow]: https://github.com/SumanthChilupuri/Power-BI-Dashboard/blob/main/Resource/process_architecture.png
[dashboard_image]: https://github.com/SumanthChilupuri/Power-BI-Dashboard/blob/main/Resource/Dashboard%20Demo.png
[dashboard_link]: 
  

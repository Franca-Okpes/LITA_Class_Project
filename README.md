# LITA_Class_Project

[Project Overview](#project-overview)


[Data Sources](#data-sources)


[Tools Used](#tools-used)


[Data Cleaning and Preparations](#data-cleaning-and-preparations)


[Exploratory Data Analysis (EDA)](exploratory-data-analysis-eda)


[Data Analysis](#data-analysis)


[Data Visualization](#data-visualization)

### Project Title: Attrition Analysis
- Project Overview
---
This repository contains an analysis of attrition. This project explores employee attrition within an organization to identify key factors contributing to turnover and retention. By analyzing patterns in employee data, such as demographics, performance, tenure, and job roles, we aim to uncover insights into factors influencing attrition rates. The project employs statistical analysis, data visualization, and machine learning techniques to predict potential attrition and provide actionable insights for improving employee retention.

- Data Sources
The primary source of Data used here is a DataSale.xlsx which is an open source Data that can be freely downleaded from an open source online such as Kaggleor FRED or any other Data repository site.

- Tools Used
The tools used in analysing the Dataset from the retail shop are

Power Bi for visualization of the analysis

- Github for Portfolio Building

- Data Cleaning and Preparations
In the initial phase of Data cleaning and preparation, I performed the following action;

1. Data Importation and Inspection
2. Handling missing variables
3. Data Cleaning and Formatting

- Exploratory Data Analysis (EDA)
Exploratory Data Analysis (EDA) helps uncover insights by addressing key questions such as:
Are certain job roles or departments experiencing higher attrition rates?
How do performance ratings correlate with attrition rates?
Are compensation levels a factor in attrition rates?
What are the top predictors of attrition based on employee data?
Are certain tenure milestones (e.g., 1 year, 3 years) associated with higher attrition?
Can a predictive model identify employees most at risk of leaving in the near future?
Are employees with higher engagement in professional development programs more likely to stay?

Data Analysis
This is the section I included my basic lines of code or queries or even some of the DAX (Data Analysis Expression) ecpressions used during the analysis;

Eg
```POWER BI
Attrition rate = Attrition Rate = SUM('HR data (2)'[Attrition Count])/SUM('HR data (2)'[Employee Number])
```

```POWER BI
Average Age = AVERAGE('HR data (2)'[Age])
```

Data Visualization

![HR ](https://github.com/user-attachments/assets/24625022-116a-4769-a806-5f76b760d7cf)


![employee count](https://github.com/user-attachments/assets/7b9bf54c-1da5-4f00-a9ce-ac3784ce672f)


![Attritn by age band](https://github.com/user-attachments/assets/91ccd31f-456a-4cc8-8ff6-a981dcc066cd)


![job satisfaction](https://github.com/user-attachments/assets/372f76f0-87d3-46f9-a570-9a6f85eeaf4c)


![training   dev](https://github.com/user-attachments/assets/aae0b46b-f8cd-4e21-a4bb-41acb51ce43b)


![performance and appraisal](https://github.com/user-attachments/assets/a3a5eed1-c0bc-497d-bd72-bff7ff29e338)


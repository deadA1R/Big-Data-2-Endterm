
# Report

### Names: Dias Amangeldy, Ilya Rogov, Beybarys Rysbek

### Group: CS-2117

### Discipline: Big Data in Law Enforcement 2

### Project: Examination project.

Link to the dataset: https://data.world/city-of-ny/uip8-fykc/workspace/file ?filename=nypd-arrest-data-year-to-date-1.csv


#### Analysis plan:
* Introduction: Presentation of the dataset, its meaning and application in the context of law enforcement agencies.

* Data preparation: Using tools to clean, transform and load data, ensuring that it is ready for analysis.

* Data Analysis: In-depth analysis using statistical methods and visualization to identify trends and patterns.

* Conclusion: Summarizing, discussing the key results of the analysis and suggestions for further research.

#### The purpose of the analysis:
The purpose of this project is a comprehensive analysis of law enforcement data to identify the main trends, patterns and anomalies in crimes committed. This includes an analysis of the types of crimes, the time and place of their commission, as well as the demographic characteristics of criminals. The main task is to identify potential patterns that can help law enforcement agencies in planning measures to prevent crime and improve public safety.

##### Introduction

This report focuses on an extensive dataset describing arrests made by the New York Police Department (NYPD). This is critical to understanding patterns in law enforcement activities, including the types of crimes that lead to arrests, demographic information about suspects, and the locations and times of these incidents.

##### Data preparation
The dataset has gone through an extensive ETL process using Pandas for purification and transformation. This included removing duplicates, processing missing values, and ensuring the correct data types for analysis. SQL has been used for structured queries to further refine the data to produce meaningful conclusions.

##### Analysis
The analysis was carried out through several prisms:

- Pandas and NumPy were used for primary research identifying trends in crime types and demographic distribution.

- An analysis of the arrests provided by the New York Police Department has been conducted. The original dataset was downloaded from the 'nypd-arrest-data-year-to-date-1.csv' file using the pandas library. After downloading, we reviewed the data types of each column and replaced the values in the 'ARREST_BORO' column, using a dictionary to match the abbreviations of the full names of the districts.

- To process the data, we deleted duplicate rows and rows with missing values. Then we converted the 'ARREST_DATE' column to datetime format and the 'LAW_CAT_CD' and 'ARREST_BORO' columns to categorical data types.

- Then we conducted various data analyses, including counting unique types of crimes, the distribution of age groups among those arrested, the number of arrests over different time periods (by month) and the number of arrests in each area of the city.

- These analyses provided valuable data on the distribution of crimes, the age demographics of those arrested, the time patterns of arrests, and the geographical distribution of arrests across different areas of the city.

##### Conclusion
The analysis found significant patterns in the nature and distribution of arrests in New York City, highlighting the prevalence of assault-related crimes as a significant cause of arrests, and the lack of arrests of youth in the Manhattan area.

All the results of the analysis were saved in CSV files

## 🔗 Links
[[telegram]](https://t.me/ddd3eddd)


## 🚀 About our Team
Dias Amangeldy - 2 part (SQL + Report)
Ilya Rogov - (1 part + Report)
Beybarys Rysbek - (3 part + Report)


## Cyclistic Bike Sharing Company Case Study

**Project Overview: -**

Cyclistic, a Chicago-based bike-share company, aims to maximize annual memberships by understanding the differences in bike usage between annual members and casual riders. This case study is part of a broader initiative to design effective marketing strategies and convert casual riders into annual members. The focus is on answering the question: How do annual members and casual riders use Cyclistic bikes differently?

**Project Objectives: -**

Business Task:- Design marketing strategies to convert casual riders into annual members by analyzing riding patterns.

Key Stakeholders:-
Lily Moreno: Director of Marketing
Cyclistic Marketing Analytics Team

**Data Preparation: -**

Data Source:
The historical trip data was obtained from Motivate International Inc..

Data Organization:
The data, covering January to December 2021, was organized into 12 CSV files, each representing a month.

Data Quality Check:
Ensured data reliability, completeness, accuracy, timeline and relevance for the desired analysis. Addressed data privacy concerns, excluding personally identifiable information.

**Data Processing: -**

Tools Used:-
* Excel: Initial data exploration.
* SQL & Python: Data analysis and computations.
* Tableau: Data visualization.

**Cleaning Process: -**

Checked for data types, ranges, and formats. Removed duplicates and cleaned and formatted text columns. Addressed missing or inconsistent data. Created additional columns for trip duration, day of the week, and season.

**Analysis: -**

1.	Loaded all the 12 files in python and checked for formatting and names of columns & their sizes to combine them in one data frame
2.	Combined the data in one data frame in python 
3.	Sorted the data according to start date
4.	Used info() & head() methods to get an idea about the data
5.	Calculated the Distance between each trip in km & Trip Duration in time format
6.	Sorted the value according to Distance 
7.	There was one outlier which was skewing the result so eliminated the row from analysis data for accurate analysis
8.	Checked for the rows which contains zero values in coordinate columns and cleaned it as they were giving wrong information about the Distance values
9.	Imported the cleaned data to perform analysis in Tableau
10.	Saved the required columns from cleaned data set in a separate data frame to perform analysis and save time in process
11.	 Used “describe () “method to understand the initial statistics of data
12.	After that created initial plots and graphs to better understand the distribution
13.	Aggregated the data as required and did some analysis on that to find out trends and relationships of different parameters with respect to casual and member riders.


**Deliverables:-**

* Data Files: Stored 12 CSV files for each month in a separate folder for further follow up.
* Documentation: Detailed process of data cleaning and manipulation documented step by step in the report.
* Analysis Output: Presented initial insights and trends using a presentation and build a dashboard using Tableau visualizations. Also suggested actionable insights to prepare a marketing strategy to target casual riders to convert then into member riders.

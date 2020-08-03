# Glassdoor Exploratory Data Analysis
Comaprison of Data Science Positions Before and During Covid-19
Project Overview:
 This project puts an insight in to the available data science positions, compares job counts and salary across states, finally compares data science positions to the year 2019.The data for the data science positions was scrapped from glassdoor website after that the data was cleaned and organized to conduct exploratory data analysis.
 
 Contents:
1. Data Scrapping
2. Data 2020 Data
Exploratory Data Analysis:
3. Missing Values
4. Average salary
5. Company Rating
6. Average Salary by Job Type 2020
7. Counts by Job Type
8. Salary by Seniority Level
9. Job Count by State
Salary by Job Type by State:
10. Data Analyst
11. Data Scientist
12. Data Engineer
13. Data Modeler
14. Cleaning 2019 Data
15. Average Salary by Job Type 2019
16. Job Count Comparison 2019-2020
17. Percentage of Job Types
18. Comparison of the Top Highest Paying States in 2020 to 2019


Code and Resources Used
R version: 3.6.2
Packages: (httr, xml2, rvest, tidyverse, purrr, ggpubr, janitor, kableExtra, readr)
Scrapper github: https://github.com/chrisjkeeney/Glassdoor
Scrapper Web:https://www.rpubs.com/chrisjkeeney/Glassdoor

Data Science position web Scrapping:
This section portrays a step by step data scrapping approach. A total of 15,908 data science and related field s was scrapped and the variables include:
  Job Title
  Company Name
  City and State
  Company Rating 
  Salary
  Posted Date
  
Data cleaning
Values that contain non relevant characters or other information were removed. Inaddition, abbreviated words were converted in to a same format to keep consistency. For some observations the value of state was manually inserted by reffering to the stated city.On the other hand, 212 observation did not include state and salary values hence were removed from the data.

# Glassdoor Exploratory Data Analysis
**_Comaprison of Data Science Positions Before and During Covid-19_**

**Project Overview:**
 This project puts an insight in to the available data science positions, compares job counts and salary across states, finally compares data science positions to the year 2019.The data for the data science positions was scrapped from glassdoor website, after that the data was cleaned and organized to conduct exploratory data analysis.
 
# Contents:
1. Data Scrapping
2. Cleaning 2020 Data
#### Exploratory Data Analysis:
3. Missing Values
4. Average salary
5. Company Rating
6. Average Salary by Job Type 2020
7. Counts by Job Type
8. Salary by Seniority Level
9. Job Count by State
#### Salary by Job Type by State:
10. Data Analyst
11. Data Scientist
12. Data Engineer
13. Data Modeler
#### Data preparation for the year 2019 and analysis in comparison to 2020
14. Cleaning 2019 Data
15. Average Salary by Job Type 2019
16. Job Count Comparison 2019-2020
17. Percentage of Job Types
18. Comparison of the Top Highest Paying States in 2020 to 2019


# Code and Resources Used
* **R version:** 3.6.2
* **Packages:** (httr, xml2, rvest, tidyverse, purrr, ggpubr, janitor, kableExtra, readr)
* **Scrapper github**: https://github.com/chrisjkeeney/Glassdoor
* **Scrapper Web:** https://www.rpubs.com/chrisjkeeney/Glassdoor

# Data Science positions web Scrapping:
This section portrays a step by step data scrapping approach. The scrapped data includes a total of 15,908 data science and related fields observationa and six variables:
* Job Title
* Company Name
* City and State
* Company Rating 
* Salary
* Posted Date
  
# Data cleaning
Values that contain non relevant characters or other information were removed. Inaddition, abbreviated words were converted in to a same format to keep consistency. For some observations the value of state was manually inserted by reffering to the stated city.On the other hand, 212 observation did not include state and salary values hence were removed from the data.

# Exploratory Data Analysis
### Missing Values Table
<img width="262" alt="Missing" src="https://user-images.githubusercontent.com/47319011/89211012-f9f9a980-d575-11ea-952a-ac7913678651.png">

### Average Salary
<img width="832" alt="Screen Shot 2020-08-03 at 10 53 55 AM" src="https://user-images.githubusercontent.com/47319011/89212244-fcf59980-d577-11ea-9df4-9f434ec89f93.png">

### Company Rating
<img width="591" alt="Screen Shot 2020-08-03 at 10 57 27 AM" src="https://user-images.githubusercontent.com/47319011/89212413-3c23ea80-d578-11ea-8539-86e8df936e59.png">

### Average Salary by Job Type
<img width="894" alt="Screen Shot 2020-08-03 at 11 00 00 AM" src="https://user-images.githubusercontent.com/47319011/89212635-a3da3580-d578-11ea-914b-baa8a10e6505.png">

### Salary by Seniority Level
<img width="440" alt="Screen Shot 2020-08-03 at 11 02 50 AM" src="https://user-images.githubusercontent.com/47319011/89212790-f582c000-d578-11ea-8a7b-30642ee02422.png">

### Job Count by State
<img width="923" alt="Screen Shot 2020-08-03 at 11 09 18 AM" src="https://user-images.githubusercontent.com/47319011/89213829-90c86500-d57a-11ea-92c9-8b4ac199cc1a.png">

### Data Analyst Salary by State
<img width="911" alt="Screen Shot 2020-08-03 at 11 09 38 AM" src="https://user-images.githubusercontent.com/47319011/89213902-b190ba80-d57a-11ea-8bf5-7f0bef64f87e.png">

###  Data Scientist Salary by State
<img width="921" alt="Screen Shot 2020-08-03 at 11 09 58 AM" src="https://user-images.githubusercontent.com/47319011/89213949-c3725d80-d57a-11ea-8cbd-05dc204278b0.png">

### Data Engineer Salary by State
<img width="928" alt="Screen Shot 2020-08-03 at 11 10 11 AM" src="https://user-images.githubusercontent.com/47319011/89214037-eac92a80-d57a-11ea-9009-6f4a00323e36.png">

### Data Modeler Salary by State
<img width="917" alt="Screen Shot 2020-08-03 at 11 10 29 AM" src="https://user-images.githubusercontent.com/47319011/89214129-15b37e80-d57b-11ea-9ae4-6ab5c1e4a1d8.png">

### Average Salary by Job Type 2019
<img width="910" alt="Screen Shot 2020-08-03 at 11 11 31 AM" src="https://user-images.githubusercontent.com/47319011/89214158-2663f480-d57b-11ea-98f0-badb8fe5c6ec.png">

### Job Count Comparison 2019-2020
<img width="922" alt="Screen Shot 2020-08-03 at 11 11 58 AM" src="https://user-images.githubusercontent.com/47319011/89214220-47c4e080-d57b-11ea-8172-9f06dd409400.png">

### Percentage of Job Types
<img width="878" alt="Screen Shot 2020-08-03 at 11 12 16 AM" src="https://user-images.githubusercontent.com/47319011/89214319-6fb44400-d57b-11ea-98b1-995cf0e09639.png">

### Comparison of the Top Highest Paying States in 2020 to 2019
<img width="832" alt="Screen Shot 2020-08-03 at 11 45 04 AM" src="https://user-images.githubusercontent.com/47319011/89216409-2f56c500-d57f-11ea-8611-f4db7cc00204.png">

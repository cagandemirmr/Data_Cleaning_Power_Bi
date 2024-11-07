# Data_Cleaning_Power_BI

This project involves a comprehensive cleaning and analysis of a dataset, using Microsoft Power BI to identify trends, key performance indicators (KPIs), and demographic insights. The primary focus was to preprocess the data for analysis and create various visualizations to uncover insights about career switching, salary distribution, preferred programming languages, and other aspects of the dataset.

## Table of Contents

- [Overview](#overview)
- [Data Cleaning Process](#data-cleaning-process)
  - [Column Review](#column-review)
  - [Data Type Verification](#data-type-verification)
  - [Data Splitting by Delimiters](#data-splitting-by-delimiters)
  - [Blank Value Imputation](#blank-value-imputation)
- [Analysis and Visualization](#analysis-and-visualization)
  - [Career Switching Indicator](#career-switching-indicator)
  - [KPIs Using Cards](#kpis-using-cards)
  - [Job Title and Salary Distribution](#job-title-and-salary-distribution)
  - [Programming Language Preference](#programming-language-preference)
  - [Work-Life Balance and Salary Satisfaction](#work-life-balance-and-salary-satisfaction)
  - [Country Distribution with Tree Map](#country-distribution-with-tree-map)
  - [Difficulty Level Analysis](#difficulty-level-analysis)
  - [Final Dashboard Edits](#final-dashboard-edits)
- [Conclusions](#conclusions)

---

## Overview

The project starts with cleaning and preparing data in Power BI, followed by creating various visualizations to uncover meaningful patterns. The goal was to make data-driven insights accessible and understandable, focusing on user demographics, job satisfaction, and key career metrics.

## Data Cleaning Process

### Column Review
The initial step involved examining each column to decide whether any data needed removal or correction. This helped streamline the dataset and ensure only relevant information was retained.

![Column Review](https://github.com/user-attachments/assets/d4b683fb-fb16-40c5-a65d-f5a386c65192)

### Data Type Verification
Each column's data type was checked for consistency to prevent issues during visualization and analysis.

![Data Type Verification](https://github.com/user-attachments/assets/eb402d74-3487-4c3e-a38b-930697e57b85)

### Data Splitting by Delimiters
To simplify and make data more usable, certain fields were split using delimiters.

![Data Splitting](https://github.com/user-attachments/assets/10193dbc-56a0-44cd-8239-bc780befb0b2)

### Blank Value Imputation
Blank values were filled with approximate values to ensure completeness and continuity in analysis.

![Blank Value Imputation](https://github.com/user-attachments/assets/2af835e3-0305-43d9-abe7-89e65870c442)

## Analysis and Visualization

### Career Switching Indicator
A new column was created to indicate whether a respondent had switched careers. A value of `1` represents "Yes" for career switching, and `0` represents "No." The average value was measured to calculate the percentage of career switchers.

![Career Switch Indicator](https://github.com/user-attachments/assets/384d0099-0477-4ee5-957c-3b724ea30ca6)

### KPIs Using Cards
KPI cards were generated to display average values and other essential metrics, providing an at-a-glance view of important figures.

![KPI Cards](https://github.com/user-attachments/assets/96821bcc-6061-4a0c-b03f-1603c2ab48b9)

### Job Title and Salary Distribution
A stacked bar chart was used to illustrate salary ranges across various job titles, revealing insights into compensation across roles.

![Job Title and Salary](https://github.com/user-attachments/assets/bffb97e3-9f22-4387-9926-74d8f14e017b)

### Programming Language Preference
To understand the respondents' preferred programming languages, a stacked column chart was used to highlight popularity by language.

![Programming Language Preference](https://github.com/user-attachments/assets/68ab5efb-3009-450c-ab94-2432880117ea)

### Work-Life Balance and Salary Satisfaction
Gauge charts were implemented to show satisfaction levels related to work-life balance and salary, allowing for a quick view of overall job satisfaction.

![Work-Life Balance Satisfaction](https://github.com/user-attachments/assets/0b725ef1-b4ec-4010-abad-5a6f9ee5065c)

### Country Distribution with Tree Map
The distribution of survey respondents by country was visualized using a tree map, making it easier to see the regional representation in the dataset.

![Country Distribution](https://github.com/user-attachments/assets/6fb76b1e-9206-40e6-a493-3598f7c79227)

### Difficulty Level Analysis
A donut chart was created to analyze the perceived difficulty levels within the dataset, helping to understand user experiences in the field.

![Difficulty Level Analysis](https://github.com/user-attachments/assets/c24ce168-ed5f-433c-87e7-dec6e66fa7da)

### Final Dashboard Edits
The final step involved polishing the dashboard to ensure clarity and readability. Headers were added for structure, and chart designs were refined.

![Dashboard Finalization](https://github.com/user-attachments/assets/42353a47-5ca3-489f-aed0-b067e847f421)

## Conclusions

In this analysis:
- **Career Switching:** A significant portion of respondents are switching to data-related careers, often reporting moderate job satisfaction.
- **Programming Language Preferences:** Python stands out as the most popular language, possibly due to its ease of use.
- **Age Demographics:** The majority of respondents are in their late 20s.
- **Difficulty Perception:** Respondents generally found data-related jobs to be moderately challenging.
- **Popular Job Roles:** Data Analyst roles were the most common among survey participants.

This project highlights trends and preferences in the data field, providing valuable insights for anyone interested in understanding the current landscape of data-related careers.

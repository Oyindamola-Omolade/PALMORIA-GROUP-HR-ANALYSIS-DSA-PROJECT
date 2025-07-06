# PALMORIA-GROUP-HR-ANALYSIS-DSA-PROJECT
This is my second project after my Data Analysis classes at Digital Skillup Africa , Incubator Hub

### Project Overview 
Palmoria Group is a manufacturing company based in Nigeria. They have been tagged in a News headline as a company with gender  inequality . This is bad for the companies revenue. As an analyst I was brought on board  to analyse issues of gender inequality in its 3 regions.
By analysing the various parameters in the data received, I seek to gather enough insights to identify key areas that the company needs to address immediately, find out the reason for the gender inequality news headline and how to prevent further bad news reports on gender inequality in Palmoria Group.  

### Data Sources 
The primary source used for this analysis is a CSV file 

### Tools Used
- Ms. Excel for Data Collection and cleaning 
- Power BI for cleaning and creating visulaization reports
- Ms. Power point for presentation

### Data Cleaning and Preparation  
- Data Loading and inspection
- Handling missing variables
- Removing nulls and blanks
- Changing the blanK gender spaces to N/A
- Data cleaning and formatting

  ### Exploratory Data Analysis
  1. what is the gender distribution in the organization?
  2. Identify gender pay gaps
  3. Does Palmoria meet the $90,000 minimum wage?

  ### Data Analysis
  I used Unpivot columns , Custom Column , Merge Queries as New, Replace Values Functions to transform my data

  ### Findings
  - Some employees in the data refused to disclose their gender , Instead of the initial blank spaces i changed all blank gender spaces to N/A
  - Some employees had no salary because they have left the company , instead of having NULL in my dataset i removed all people that are no longer with the Company from the data.
  - Some departments also had NULL , i removed all rows that had a NULL department.
  - I was also given a bonus mapping/rate Excel file to allocate bonuses to all employees based on their performance rating.I calcualted the bonus rate for each employee and the total amount to be paid to each employee plus the bonus .
  - After allocating bonuses based on their performance , some employees were not entitled to bonus because of their performance. I had to Replace the NULL spaces with 0 for those employees who were not entitled to a bonus.
  - There are more males employees than female employees in Palmoria.
  - A new regulation was adopted which requires manufacturing companies to pay employees a minimum of $90,000. Palmoria doesn't meet up with this requirement as a lot of employees are earning below $90,000.
  - Palmoria would have to adjust their minimum salary for all employees to meet the new requirement so they don't face another bad news headline.
  



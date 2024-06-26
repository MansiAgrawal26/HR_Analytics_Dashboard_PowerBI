## Objective
The objective of this project is to identify the key factors driving employee attrition and provide actionable insights for improving workforce retention in an organization. It helps an organization to improve employee performance and improve employee retention (reduce attrition) by creating a HR Analytics dashboard.

## Project Learnings
- Identified key factors to reduce attrition.
- Improved the hiring process.
- Improved employee experience.
- Made workforce more productive.
- Gained employee trust.

## Steps followed:

[Download the dataset from here](https://github.com/MansiAgrawal26/HR_Analytics_Dashboard_PowerBI/blob/master/HR_Analytics%20Dataset.csv)

**1. Data Gathering:** 
  - Importing raw data .csv file into Power BI & transform to Power Query editor for cleaning and data processing.
          
**2. Data cleaning:**
  - Cleaning is done by removing empty column, removing duplicates, errors etc.
  - Replacing values in column with proper values and naming.
  - Detecting data type of every column, using the auto detect data type function in Power query editor.
          
**3. Data processing:**
  - In the Power Query editor, creating new column called "AttritionCount" by using conditional column feature in add column which is created on the basis of certain condition like (IF attrition = 'Yes' then 1, Else 0).
  - This new column is further used for creating different KPI's and charts.Then creating the Attrition Rate by applying DAX queries, adding new measure (Attrition Rate = SUM([AttritionCount]))/SUM([Employeecount])) in %.
          
**4. Data analysis:**
  - Analysis involves the creation of a range of visual representations, including bar charts, key performance indicators (KPIs), table charts, pie charts, and other relevant visualizations.
  - These tools are utilized to gain insights and present data in a comprehensive and easily understandable manner.


![HR Analytics dashboard](https://github.com/MansiAgrawal26/HR_Analytics_Dashboard_PowerBI/blob/master/HR%20Analytics%20Dashboard.jpg)



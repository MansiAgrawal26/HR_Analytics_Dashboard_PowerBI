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

### Key Questions of the Dashboard :

    What is the Total Employee Count ?
    What is the employee's Average Age & Average Salary ?
    What is the Attrition Count of men and women ?
    What is employees Working years at the Company ?
    Which Department has maximum employee ?
    What is the Gender distribution ?
    Which Education Field has maximum employees ?
    Which Business Travel has maximum employees ?

### Learned about:
1. Calculated Field: To Calculate Attrition Rate & Active Employees
2. Matrix table: To show Job Satisfaction rating
3. Donut chart and Pie Chart
4. Bar Chart and Cluster chart 📊
5. KPI(Key Performing Indicators) and Slicer.
6. Filters: Used to filter data according to gender

### Key Insights Summary:
1. **Total Employees:** The organization has grown significantly, currently employing 1470 individuals, indicating substantial growth and scale.
2. **Attrition Analysis:** A total of 237 employees left the organization. Among them, 150 were male, and 87 were female, indicating a higher attrition rate among males.
3. **Departmental Attrition:** The Sales Department experienced the highest attrition rate at 20.6%, suggesting potential areas for improvement in employee retention strategies in this department.
4. **Education Field Impact:** Employees in the life sciences field had the highest attrition rate, emphasizing the need to address retention challenges in this specific area.
5. **Job Role Affected:** The sales role had the highest attrition rate, indicating a need for focused retention efforts in this department to reduce turnover.
7. **Attrition Rate by Gender for Different Age Group:**  The attrition count among the age group of 26-35 years 606 which is maximum among the other age groups.
   
![HR Analytics dashboard](https://github.com/MansiAgrawal26/HR_Analytics_Dashboard_PowerBI/blob/master/HR%20Analytics%20Dashboard.jpg)


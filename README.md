# Hr attrition-Dashboard


## Problem Statement

The Human Resources department is experiencing a significant level of employee attrition, which is impacting operational efficiency and increasing recruitment and training costs. The goal is to understand the key factors driving employee turnover, predict which employees are at risk of leaving, and recommend strategies to reduce attrition.




### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values. 
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : Visual filters (Slicers) were added for four fields named "Human Resources", "Reserch & Development", & "Sales".
- Step 7 : Six card visuals were added to the canvas, one representing Total EMP, Average salary, average age, attrition rate, attrition, & average year at company.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.
- Step 8 : A stacked column chart was also added to the report to show attrition by age, and salary. 
- Step 9 : While creating visual, field named "Gender" was also added to the Treemap, thus number of employees are also seggregated according the gender. 
- Step 10 : Area chart Visual was used to represent different attrition of age.
- Step 11 : Matrix used to show satisfaction ratings with job role.
- Step 12 : Donut chart used to show attrition by education.

 
 # Report Snapshot (Power BI DESKTOP)

 
![Hr attrition dashboard](https://github.com/user-attachments/assets/79c1d365-84b9-4e26-9710-1e363b1f17d7)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

### Objectives  
- 1 : Analyze historical HR data to identify patterns and trends in employee attrition.
- 2 : Understand the key factors that influence employee decisions to leave the organization (e.g., salary, job satisfaction, workload, management, etc.).
- 3 : Develop a predictive model to identify employees at high risk of attrition.
- 4 : Provide actionable insights and recommendations to HR for improving employee retention.         
### Key Questions 
- 1 : What are the key demographics (age, gender, job role, department, etc.) and organizational factors (workload, work-life balance, compensation) contributing to attrition?
- 2 : Can we identify any early warning signs of employees who are likely to leave?
- 3 : What changes can be implemented to reduce attrition and increase employee satisfaction?
### Data Requirements (To address the problem, the following data points are typically required)
- 1 : Employee demographics (age, gender, education level, marital status)
- 2 : Employment details (job role, department, years at company, years in current role, salary, promotions, performance ratings)
- 3 : Work environment factors (workload, work-life balance, overtime, job satisfaction, relationship with management)
- 4 : Employee attrition data (whether an employee has left, and if so, why)

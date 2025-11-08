# Human Resources Project
This project explores Human Resource (HR) Analytics using data-driving insights to help organizations make informed decisions. It focuses on analyzing employee data to uncover trends in attrition, performance and workforce diversity.

### Data Source
The source of this dataset is kaggle.com. the primary dataset used in this analysis is HR.csv

### Tools
- Excel - Data Cleaning
- SQL - Data Analysis
- Power BI - Data Visualization

### Data Cleaning
1. Remove duplicated rows
2. Replace null values
3. Data formatting

### Exploratory Data Analysis
1. What is the total number of employees?
2. What is the attrition rate?
3. What is the average income?
4. Does income affect attrition?

### Analysis
```
SELECT COUNT(*) FROM EMPLOYEE
  WHERE ENDDATE IS NOT NULL
```

### Result/Findings
1. Total number of employees is 140
2. A total of 14 employees left the firm
3. Te attrition rate is 1.24%

### Recommendations 
1. Improve employee retention to reduce employee attrition

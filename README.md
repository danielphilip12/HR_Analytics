# HR Employee Attrition Analysis

Source: https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction

## Overview

This project was to analyze the factors that contribute the most to why employees attrition. 

## Objectives

- Analyze employee attrition patterns
- Identify employee/workplace characteristics associated with attrition
- Explore relationships between compensation, experience, age, and tenure
- Build an interactive Power BI dashboard

## Dataset

This dataset contains 1470 rows of data, with each row representing a single employee. This data contains information such as: Age, Marital Status, Years with the Company, Years since last Promotion, Monthly Income, etc. 

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI
- DAX

## Exploratory Data Analysis

The Jupyter Notebook contains futher analysis to help determine categorical groups for attributes such as monhtly income, total working years, etc. in order to better show the separation of these groups and their individual attrition rates. 

## Power BI Dashboard

### Page 1 — HR Attrition Analytics

![Page 1](overview_page.png)

- Attrition Rate: 16.12%
- Men attrition more then Women, but only by a slight amount
- Overtime has a large effect on attrition, doing so at a rate 3x higher than employees who did not work overtime
- Employees with less than two years at the company have some of the highest attrition rates, at 36.36% for employees with less than one year and 28.86% for employees with 1–2 years.
- The highest attrition rate by role is Sales Representatives
- Attrition rates are highest among younger employees, particularly employees ages 18–25.

### Page 2 — Attrition Factors

![Page 2](attrition_factors_page.png)

- Employees working overtime have an attrition rate of 30.5%, nearly 3× the 10.4% rate of non-overtime employees.
- Employees with lower job satisfaction show higher attrition, particularly among those working overtime..
- Employees with 0–3 years in their current role have a 20.8% attrition rate, compared with 4.9% among employees with 10–12 years.

### Page 3 — Employee Profile, Compensation & Tenure

![Page 3](emp_profile_page.png)

- As the number of total working years goes up, the attrition rate appears to go down.
- We can see in the scatterplot that employees with less than 10 years of total working years attrition much more commonly, signified by the large cluster of red (attrition) points, compared to the more spread out points past the 10 year mark. 
- Among employees ages 26–35, attrition falls from 24.69% for those with 0–5 years at the company to 9.38% for those with 11+ years.

## Key Findings

1. Overtime is strongly associated with attrition. Employees working overtime have a 30.53% attrition rate compared with 10.44% among employees who do not work overtime.
2. Attrition is higher among less-experienced employees. Employees with 0–5 years of total working experience have a 28.80% attrition rate, compared with 7.73% among employees with 21+ years.
3. Sales Representatives have substantially higher attrition than the company average. Their attrition rate is 39.76%, approximately 2.5× the overall rate of 16.12%.
4. Early-career employees have particularly high attrition. Employees ages 18–25 have a 35.77% attrition rate, substantially above the company-wide rate of 16.12%.

## Limitations

This analysis identifies associations between employee characteristics and attrition within the dataset. The results should not be interpreted as causal relationships or as a predictive model of individual employee attrition.
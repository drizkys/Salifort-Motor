# Predicting Predicting Employee Turnover at Salifort Motors

## Overview
The objective of this project is to analyze employee turnover at Salifort Motors by identifying the key factors contributing to attrition and developing predictive models to determine the likelihood of employees leaving the organization.
This analysis utilized HR department data encompassing various employee-related metrics
The final logistic regression model effectively highlighted the primary drivers of employee turnover and achieved a commendable accuracy of 82% in predicting employee retention.

## Business Understanding
According to the HR dataset, 83% of employees have left the company.
Understanding the factors that contribute to employee attrition is crucial for developing an effective employee retention strategy.

## Data Understanding
The HR dataset comprises self-reported information provided by employees.
It contains data from 14,999 unique employees and includes 10 features.
These features encompass details such as satisfaction levels, performance evaluation scores, number of projects undertaken, average monthly working hours, tenure, work accident status, attrition status, promotion history, department, and salary.

| Fearures | Description |
|-------------|-------------|
| satisfaction_level | The employee’s self-reported satisfaction level [0-1] |
| last_evaluation | Score of employee's last performance review [0–1] |
| number_project | Number of projects employee contributes to |
| average_monthly_hours | Average number of hours employee worked per month |
| time_spend_company | How long the employee has been with the company (years) |
| work_accident | Whether or not the employee experienced an accident while at work |
| left | Whether or not the employee left the company |
| promotion_last_5years | Whether or not the employee was promoted in the last 5 years |
| department | The employee's department |
| salary | The employee's salary (low, medium, or high) |

The boxplot below highlights the presence of outliers in certain features.
Since logistic regression is highly sensitive to outliers, it is essential to address and remove them to ensure the development of a robust and accurate model.

<img width="477" alt="image" src="https://github.com/user-attachments/assets/db435fb0-da4a-47c5-83c7-d6d17fa9b709" />

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
The boxplot below highlights the presence of outliers in certain features.
Since logistic regression is highly sensitive to outliers, it is essential to address and remove them to ensure the development of a robust and accurate model.

<img width="477" alt="image" src="https://github.com/user-attachments/assets/db435fb0-da4a-47c5-83c7-d6d17fa9b709" />

## Modelling and Evaluation
- The model successfully identified the key factors influencing employee attrition and achieved a decent accuracy of 82% in predicting employee retention.
- However, it struggled to accurately predict employees who are likely to leave, as evidenced by the low recall (23%) and moderate precision (48%) for the leaving class.
- The strongest predictor of attrition is satisfaction, which has a significant negative relationship with leaving.
- Other important factors include tenure (positive influence) and work accident (negative influence).
- Fetures like salary level and number of project had weaker but still relevant impacts on attrition.

<img width="442" alt="image" src="https://github.com/user-attachments/assets/963dc352-84a2-44c0-87e2-2f043251fdce" />
<img width="370" alt="image" src="https://github.com/user-attachments/assets/b8e4e5cc-e134-4b9e-a815-9abf534856c4" />


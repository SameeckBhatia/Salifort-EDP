# Google Certificate Capstone

## Prompt

"As a data specialist working for Salifort Motors, you have received the results
of a recent employee survey. The senior leadership team has tasked you with
analyzing the data to come up with ideas for how to increase employee retention.
To help with this, they would like you to design a model that predicts whether
an employee will leave the company based on their department, number of
projects, average monthly hours, and any other data points you deem helpful."

## Plan

### Stakeholders

- Company customers
- Company employees
- Company executives
- Company HR department

### Goal

- To reduce costs related to replacing employees who have left and increase 
retention rates.

### Data Dictionary

| variable              | description                                                       |
|-----------------------|-------------------------------------------------------------------|
| satisfaction_level    | The employee’s self-reported satisfaction level [0-1]             |
| last_evaluation       | Score of employee's last performance review [0–1]                 |
| number_project        | Number of projects employee contributes to                        |
| average_monthly_hours | Average number of hours employee worked per month                 |
| time_spend_company    | How long the employee has been with the company (years)           |
| work_accident         | Whether or not the employee experienced an accident while at work |
| left                  | Whether or not the employee left the company                      |
| promotion_last_5years | Whether or not the employee was promoted in the last 5 years      |
| department            | The employee's department                                         |
| salary                | The employee's salary [low, medium, high]                         |
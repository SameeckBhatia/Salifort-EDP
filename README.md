# Salifort EDP: Employee Departure Predictor

## Prompt

"As a data specialist working for Salifort Motors, you have received the results
of a recent employee survey. The senior leadership team has tasked you with
analyzing the data to come up with ideas for how to increase employee retention.
To help with this, they would like you to design a model that predicts whether
an employee will leave the company based on their department, number of
projects, average monthly hours, and any other data points you deem helpful."

## Plan

### Data Dictionary

| variable                  | description                                                       |
|---------------------------|-------------------------------------------------------------------|
| ``satisfaction_level``    | The employee’s self-reported satisfaction level [0-1]             |
| ``last_evaluation``       | Score of employee's last performance review [0-1]                 |
| ``number_project ``       | Number of projects employee contributes to                        |
| ``average_montly_hours``  | Average number of hours employee worked per month                 |
| ``time_spend_company``    | How long the employee has been with the company (years)           |
| ``Work_accident``         | Whether or not the employee experienced an accident while at work |
| ``left``                  | Whether or not the employee left the company                      |
| ``promotion_last_5years`` | Whether or not the employee was promoted in the last 5 years      |
| ``Department``            | The employee's department                                         |
| ``salary``                | The employee's salary [low, medium, high]                         |

## Analyze

### Hypothesis Tests

- Attrition rate by ``promotion_last_5years``
- Attrition rate by ``work_accident``
- Attrition rate by ``salary``

## Construct

### Feature Engineering

- ``satisfaction``
- ``performance``
- ``overtime``
- ``projects_per_year``

### Final Model

- Decision Tree Classifier
- Recall: 91%
- Most important features: ``number_project``, ``satisfaction_high``, ``avg_monthly_hours``

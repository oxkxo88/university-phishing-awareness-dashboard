# Data Dictionary

## 1. Purpose

This document defines the fields used in the project's Excel task tracker. Consistent field definitions help improve data quality and reporting accuracy.

## 2. Task Tracker Fields

| Field | Description | Expected Values or Format |
|---|---|---|
| TaskID | Unique identifier for each task | Text, e.g. T001 |
| TaskName | Short description of the task | Non-empty text |
| Workstream | Project area to which the task belongs | Planning, Assessment, Training, Communications, Delivery |
| OwnerRole | Role responsible for the task | Text, e.g. Project Manager |
| DueDate | Target completion date | Excel date |
| Status | Current task status | Not Started, In Progress, Completed, On Hold |
| Priority | Importance of the task | High, Medium, Low |
| PercentComplete | Proportion of the task completed | Number from 0 to 1, formatted as a percentage |
| ProgressLabel | Text label derived from PercentComplete | Complete, In Progress, Not Started |

## 3. Data Quality Rules

- Each TaskID should be unique.
- TaskName must not be blank.
- DueDate must contain a valid date.
- Status and Priority should use the configured dropdown options.
- PercentComplete must be between 0% and 100%.
- ProgressLabel should be calculated from PercentComplete rather than entered manually.

## 4. Reporting Considerations

- Task counts should be based on the task records in the table.
- Completion KPIs should use consistent definitions.
- Invalid or missing data should be investigated before reporting.
- All example data is synthetic and does not represent a real university.

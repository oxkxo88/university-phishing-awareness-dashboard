# Test Plan

## 1. Purpose

This test plan defines how the Excel tracker, VBA automation, and future Power BI dashboard will be tested.

## 2. Test Environment

- Microsoft Excel desktop on Windows
- Macro-enabled Excel workbook (`.xlsm`)
- Synthetic project data
- Power BI Desktop (planned for dashboard testing)

## 3. Test Cases

| Test ID | Component | Test Procedure | Expected Result |
|---|---|---|---|
| TC-01 | Task Table | Check that the task table contains the expected column headers. | All required columns are present. |
| TC-02 | Status Dropdown | Select each available task status. | Only the configured status options are offered. |
| TC-03 | Priority Dropdown | Select each available priority. | High, Medium, and Low are offered. |
| TC-04 | Progress Formatting | Enter 1, 0.6, and 0 in the completion column. | Values display as 100%, 60%, and 0%. |
| TC-05 | Due-Date Warning | Set an incomplete task's due date to today. | Its due-date cell is highlighted. |
| TC-06 | Due-Date Warning | Set a completed task's due date to today. | Its due-date cell is not highlighted. |
| TC-07 | Task Count Macro | Run the task-counting macro with five task records. | The message reports five tasks. |
| TC-08 | Valid Data | Run the validator with correct task names and completion values. | No issues are reported. |
| TC-09 | Invalid Completion | Temporarily enter 150% completion. | The validator identifies the invalid value. |
| TC-10 | Missing Task Name | Temporarily remove a task name and run the validator. | The validator identifies the missing name. |
| TC-11 | Summary Formulas | Change a task status. | The relevant status count and completion KPI update. |
| TC-12 | Power BI Dashboard | Compare dashboard KPIs with verified source data. | The displayed results agree with the source calculations. |

## 4. Test Execution Record

Record the actual outcome for each test when it is performed.

| Test ID | Actual Result | Status | Notes |
|---|---|---|---|
| TC-01 to TC-12 | Not yet fully recorded | Pending | Update after executing each test. |

## 5. Defect Handling

If a test fails:

1. Record the observed behaviour.
2. Compare it with the expected result.
3. Investigate the cause.
4. Correct the issue.
5. Repeat the test and record the outcome.

## 6. Completion Criteria

Testing is complete when the required test cases have been executed, failures have been resolved or documented, and the results have been recorded accurately.

A test must not be marked as passed until its result has actually been observed.

# Project Requirements

## 1. Purpose

This document defines the functional and non-functional requirements for the University Phishing Awareness Programme Dashboard.

## 2. Functional Requirements

| ID | Requirement | Priority |
|---|---|---|
| FR-01 | The project tracker must record task names, owners, due dates, statuses, priorities, and completion percentages. | High |
| FR-02 | The tracker must provide dropdown lists for task status and priority. | High |
| FR-03 | The tracker must highlight tasks that are due today or overdue and not completed. | High |
| FR-04 | The VBA validator must identify tasks with missing names. | High |
| FR-05 | The VBA validator must identify completion values outside the 0–100% range. | High |
| FR-06 | The workbook must calculate total tasks and task counts by status. | High |
| FR-07 | The project dashboard must display overall delivery progress. | High |
| FR-08 | The dashboard should display milestone performance, risks, budget variance, and aggregated awareness metrics. | Medium |

## 3. Non-Functional Requirements

| ID | Requirement |
|---|---|
| NFR-01 | The project must use synthetic data only. |
| NFR-02 | The workbook should be understandable to a user with basic Excel knowledge. |
| NFR-03 | Calculated metrics should update when the underlying data changes. |
| NFR-04 | Project documentation must explain the purpose and limitations of the dashboard. |
| NFR-05 | Public repository files must not contain confidential information or personal data. |

## 4. Acceptance Criteria

- The tracker contains a structured Excel table.
- Status and priority dropdowns work.
- The due-date warning highlights incomplete tasks due today or earlier.
- The VBA validator reports missing task names and invalid completion percentages.
- The task-count macro returns the correct number of records.
- The dashboard displays clearly labelled KPIs based on the synthetic data.
- Testing results and known limitations are documented.

## 5. Requirement Traceability

Requirements will be checked against the completed workbook, VBA macros, dashboard, and test results. Any requirement that is not implemented will be recorded as incomplete rather than reported as successful.

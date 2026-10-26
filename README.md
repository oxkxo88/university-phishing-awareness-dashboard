# University Phishing Awareness Programme Dashboard

## Project Overview

This portfolio project demonstrates how project management, Excel VBA, Power BI and cybersecurity awareness analytics can be combined to plan and monitor a university phishing awareness programme.

The project uses **synthetic data** and a fictional university scenario. It does not contain real university staff data or actual institutional performance results.

## Project Objectives

- Track project tasks, deadlines, priorities and completion status.
- Build Excel-based validation tools using VBA.
- Analyse staff training coverage and phishing simulation outcomes.
- Create interactive Power BI dashboards to monitor programme performance.
- Document project requirements, milestones, risks, budget and testing.

## Tools and Technologies

- Microsoft Excel
- VBA (Visual Basic for Applications)
- Microsoft Power BI
- DAX (Data Analysis Expressions)
- CSV
- GitHub

## Dashboard Preview

### Project Overview

![Project Overview Dashboard](docs/images/project-overview.png)

### Cybersecurity Awareness Metrics

![Awareness Metrics Dashboard](docs/images/awareness-metrics.png)

## Key Metrics

The synthetic dataset supports analysis of:

- Task completion and overdue tasks
- Staff training coverage
- Phishing reporting rate
- Phishing click rate
- Department-level training and simulation comparisons
- Trends across October–December 2026

The figures shown in the dashboard are illustrative outputs from synthetic data, not verified real-world results.

## Repository Structure

```text
university-phishing-awareness-dashboard/
├── README.md
├── .gitignore
├── docs/
│   ├── images/
│   │   ├── project-overview.png
│   │   └── awareness-metrics.png
│   ├── project-charter.md
│   ├── requirements.md
│   ├── work-breakdown-structure.md
│   ├── risk-register.csv
│   ├── raci-matrix.csv
│   ├── milestones.csv
│   ├── budget.csv
│   └── test-plan.md
└── data/
    ├── project-tasks.csv
    ├── awareness-metrics.csv
    └── README.md
```

*Note: The tree above illustrates the intended organisation. Adjust individual filenames to match the files actually present in your repository.*

## Project Documentation

The `docs/` folder contains project planning artefacts, including requirements, milestones, risk management, responsibilities and testing documentation.

The `data/` folder contains synthetic CSV datasets used to build the Excel and Power BI components.
## Technical Implementation

### Excel and VBA
- Structured project-task data with task IDs, owners, priorities, due dates, statuses and completion percentages.
- Applied data validation and conditional formatting to improve data consistency and readability.
- Developed VBA macros to count project tasks and validate task records.
- Tested the validation process to confirm that it detects data-entry errors.

### Power BI and DAX
- Built an interactive project dashboard with task counts, completion rate, overdue-task tracking, charts and a task schedule.
- Created DAX measures for task completion rate and overdue tasks.
- Developed a cybersecurity awareness dashboard with training coverage, phishing reporting and phishing click-rate metrics.
- Added department comparisons, monthly trend charts and a reporting-period slicer to support interactive analysis.

### Illustrative Dashboard Metrics

The synthetic awareness dataset currently produces the following aggregate metrics:

| Metric | Illustrative result |
|---|---:|
| Staff training coverage | 86% |
| Phishing reporting rate | 56% |
| Phishing click rate | 12% |

These are calculated from synthetic data created for this portfolio project. They are not real university statistics or independently validated measures of programme effectiveness.

### Project Management
- Defined project requirements, scope, milestones, responsibilities and risks.
- Organised supporting artefacts and datasets in a GitHub repository.
- Documented testing activities and captured dashboard screenshots for project presentation.
  
## Learning Outcomes

This project demonstrates practical experience in:

- Project tracking and data validation
- Basic VBA automation
- Data modelling and DAX measures
- Interactive dashboard design
- Cybersecurity awareness metrics
- Project documentation and version control

## Limitations

This is a portfolio demonstration using synthetic data. The metrics do not establish the effectiveness of a real phishing awareness programme, and no actual university systems or staff records were used.

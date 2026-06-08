# AI Project Monitoring Dashboard

## Overview

AI Project Monitoring Dashboard is a Power BI solution designed to monitor project performance, workforce productivity, client satisfaction, and AI-generated risk indicators in real time. The dashboard consolidates multiple business functions into a single analytical platform, enabling organizations to make informed, data-driven decisions.

---

## Problem Statement

Organizations managing multiple AI projects often face challenges in tracking project progress, monitoring employee productivity, assessing client satisfaction, and identifying potential risks. This project addresses these challenges by providing a centralized dashboard for real-time project monitoring and performance analysis.

---

## Objectives

* Monitor project performance through interactive dashboards.
* Evaluate workforce productivity using employee activity metrics.
* Analyze client satisfaction through ratings and feedback.
* Identify project risks using AI-generated risk indicators.
* Provide management with actionable insights for decision-making.

---

## Dataset Description

The dashboard utilizes a synthetic enterprise dataset containing over 100,000 records generated for analytical purposes.

### Projects Table

Contains information related to:

* Project Budget
* Project Status
* Timeline
* Risk Levels

### Employees Table

Stores employee information including:

* Department
* Designation
* Experience

### Tasks Table

Contains:

* Task Assignments
* Priority Levels
* Completion Percentages
* Work Effort Metrics

### Productivity Table

Tracks:

* Employee Productivity Scores
* Hours Worked
* Tasks Completed

### Client Feedback Table

Stores:

* Client Ratings
* Satisfaction Scores

### AI Predictions Table

Contains AI-generated project risk metrics:

* Delay Risk
* Budget Risk
* Resource Risk

---

## Data Modeling

Relationships were established between tables to enable integrated analysis.

### Key Relationships

* Projects → Tasks
* Projects → Client Feedback
* Projects → AI Predictions
* Employees → Tasks
* Employees → Productivity

This relational model enables cross-functional analysis across projects, employees, productivity, client feedback, and risk indicators.

---

## Dashboard Components

### KPI Cards

The dashboard provides the following key performance indicators:

* Total Projects
* Total Employees
* Total Hours Worked
* Average Productivity Score
* Average Client Rating
* Tasks Completed

### Interactive Filters

Users can filter dashboard data based on:

* Department
* Project Duration
* Risk Level
* Project Name

### Visualizations

#### Project Status Distribution

Displays the proportion of projects across various project status categories.

#### Delay Risk Gauge

Shows the overall project risk level based on AI-generated predictions.

#### Top Projects by Budget

Highlights projects with the highest budget allocations.

#### Employee Productivity Analysis

Analyzes employee performance using productivity scores and experience levels.

#### Risk Analysis Table

Provides project-level visibility into:

* Delay Risk
* Budget Risk
* Resource Risk

---

## Key Insights

* The organization manages 250 projects across multiple departments.
* More than 1,000 employees contribute to project execution.
* Productivity levels remain relatively consistent across departments.
* AI-generated risk indicators help identify projects requiring immediate attention.
* Client ratings indicate generally positive stakeholder satisfaction.
* High-budget projects can be monitored for efficient resource utilization.

---

## Benefits

* Centralized project monitoring.
* Improved workforce performance tracking.
* Enhanced risk management.
* Better client satisfaction analysis.
* Faster data-driven decision-making.
* Interactive and user-friendly reporting.

---

## Tools and Technologies

* Power BI
* Data Modeling
* Data Visualization

<img width="1433" height="766" alt="Screenshot 2026-06-08 175244" src="https://github.com/user-attachments/assets/48be2a24-1532-4b6d-9f5a-f2ba4fcd94c0" />

---


## Conclusion

The AI Project Monitoring Dashboard successfully integrates project, employee, client, and risk-related information into a single analytical platform. Through interactive visualizations, KPI tracking, and AI-generated risk insights, the dashboard enables stakeholders to monitor organizational performance efficiently and make informed business decisions.

This project demonstrates the effectiveness of Business Intelligence tools in improving project governance, workforce productivity, risk management, and strategic planning.

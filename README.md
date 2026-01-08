# 🏦 Bank Loan Detection & Risk Scoring 

## Table of Content

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Data Workflow](#data-workflow)
- [Data Source](#ddata-sources)
- [Data Analysis (SQL Queries)](#data-analysis-(sql-queries))
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
- [Data Visualization](#data-visualization)
- [Key Metrics](#key-metrics)
- [Insights and Findings](#Insights--Findings)
- [Future Enhancements](#Future-Enhancements)
- [Dahsboard Previews](#dashboard-previews)

## Project Overview

- This project aims to analyze bank loan application data to evaluate credit risk, detect potential loan defaults, and support informed lending decisions.

- The dataset was self-created and cleaned using Excel, analyzed using SQL, and visualized using Power BI to build an interactive business dashboard. The project simulates a real-world banking analytics use case followed by financial institutions to reduce loan default risks.

## Objectives

- Create and clean a structured loan dataset using Excel
- Analyze customer financial behavior and loan risk factors
- Understand drivers behind loan approval and rejection
- Categorize customers into Low, Medium, and High Risk
- Build a Power BI dashboard for business-friendly insights
- Demonstrate end-to-end data analytics workflow

## Data Workflow

  ### Dataset Creation (Excel)
  
- Manually created a structured bank loan dataset
- Defined customer, loan, and risk-related attributes

  ### Data Cleaning (Excel)
  
- Removed duplicates
- Handled missing values
- Standardized column names and formats
- Validated numerical ranges (credit score, income, DTI)

  ### Data Analysis (SQL)

- Performed aggregations and filtering
- Analyzed approval rates, risk categories, and trends
- Extracted key business insights

  ### Data Visualization (Power BI)

- Built interactive dashboards
- Used KPIs, bar charts, line charts, and scatter plots
- Enabled slicers for dynamic analysis

## Data Source

- Primary Source: Self-created dataset
Tool Used: Microsoft Excel
File Format: CSV

<a href="https://github.com/rajasekar23-code/Bank-Loan-detection-and-Risk-Scoring/blob/main/bank%20loan%20detection%20and%20risk%20scoring.csv">Data set

## Data Analysis (SQL Queries)

### SQL was used to answer business-driven questions such as:

- Loan approval vs rejection rates
- Risk category distribution
- Impact of credit score on approvals
- Effect of DTI ratio on loan outcomes
- Default history analysis

### Examples of SQL analysis performed:

- GROUP BY for risk and loan status analysis
- COUNT() and SUM() for approval metrics
- CASE WHEN logic for risk categorization
- Filtering high-risk and default-prone customers

## Exploratory Data Analysis (EDA)

#### Key analytical questions explored:

01. What is the overall loan approval vs rejection rate?
02. Which risk category has the highest loan rejections?
03. How does credit score affect loan approval decisions?
04. At what DTI ratio do loan rejections increase sharply?
05. Do customers with previous defaults always fall under high risk?
06. What income range has the highest approval rate?
07. How many customers fall into each risk category?
08. Are high loan amounts more likely to be rejected?
09. Which customer segment shows the highest default probability?
10. Are medium-risk customers being approved under flexible policies?

## Data Visualization

- The Power BI dashboard includes:
- Loan Approval vs Rejection KPI cards
- Risk category distribution charts
- Credit Score vs Loan Status analysis
- DTI Ratio vs Approval trend charts
- Customer segmentation visual
- Interactive slicers for deep analysis

### Dashboard File:

<a href="https://github.com/rajasekar23-code/Bank-Loan-detection-and-Risk-Scoring/blob/main/Bank%20Loan%20detection%20%26%20Risk%20Scoring.pbix">Dashboard

## Key Metrics

- Total Loan Applications
- Approval Rate (%)
- Rejection Rate (%)
- Average Credit Score
- Average Loan Amount
- Average DTI Ratio
- Risk-wise Customer Count
- Default Customer Percentage

## Insights and Findings

- Credit score is a major factor influencing loan approval
- High DTI ratios significantly increase rejection probability
- Customers with previous defaults are predominantly high-risk
- Medium-risk customers are sometimes approved, indicating policy flexibility
- Risk-based segmentation helps identify potential defaulters early

## Future Enhancements

- Add predictive modeling for loan default probability
- Integrate Python (ML models) for risk scoring
- Add borrower demographic analysis
- Deploy dashboard using Power BI Service
- Automate data refresh and reporting

## Dahsboard Previews:

### Overall Dashboard

  <img width="648" height="376" alt="Total Applications" src="https://github.com/user-attachments/assets/27d3d72d-67e8-463e-adef-8f924f9e3d12" />


### After Selecting Medium Risk

  <img width="647" height="374" alt="By selecting Medium Risk" src="https://github.com/user-attachments/assets/c861838c-d26c-4ece-af40-de15a79f867e" />

  

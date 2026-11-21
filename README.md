# Bank Loan Analysis | SQL, Python, Excel, Power BI & Tableau

## Project Overview

This project focuses on analyzing bank loan data to understand lending performance, borrower behavior, repayment patterns, and overall loan portfolio quality.

I worked with loan application data to calculate important business KPIs, analyze good and bad loans, identify monthly trends, and understand how different borrower characteristics relate to loan performance.

The project uses SQL, Python, Excel, Power BI, and Tableau to perform data analysis and present the results through reports and interactive dashboards.

## Dataset Overview

The dataset contains loan application and borrower information.

| Dataset Information | Value |
|---|---:|
| Total Records | 38,576 |
| Total Columns | 24 |
| Data Period | 2021 |
| Total Loan Applications | 38,576 |
| Good Loan Applications | 33,243 |
| Bad Loan Applications | 5,333 |

The dataset includes information such as loan amount, funded amount, total payment, interest rate, debt-to-income ratio (DTI), loan purpose, employment length, home ownership, and loan status.

## Tools & Technologies

| Tool | Usage |
|---|---|
| Excel | Data cleaning, Pivot Tables and analysis |
| SQL | Data analysis, KPI calculations and queries |
| Python | Data cleaning and exploratory data analysis |
| Pandas & NumPy | Data manipulation |
| Matplotlib | Data visualization |
| Power BI | Interactive dashboards and reporting |
| Tableau | Data visualization and dashboard development |

## Key Performance Indicators (KPIs)

The following metrics were calculated to understand the overall loan portfolio.

| KPI | Result |
|---|---:|
| Total Loan Applications | 38,576 |
| Total Funded Amount | $435.76 Million |
| Total Amount Received | $473.07 Million |
| Average Interest Rate | 12.05% |
| Average DTI | 13.33% |
| Good Loan Applications | 33,243 |
| Good Loan Percentage | 86.18% |
| Bad Loan Applications | 5,333 |
| Bad Loan Percentage | 13.82% |

### Good Loan vs Bad Loan Analysis

Loans were divided into two categories:

**Good Loans**
- Fully Paid
- Current

**Bad Loans**
- Charged Off

| Metric | Good Loans | Bad Loans |
|---|---:|---:|
| Applications | 33,243 | 5,333 |
| Application Percentage | 86.18% | 13.82% |
| Funded Amount | $370.22M | $65.53M |
| Amount Received | $435.79M | $37.28M |

## Analysis Performed

### 1. SQL Analysis

Used SQL to analyze loan applications and calculate business KPIs.

Key analysis included:

- Total loan applications and funded amounts.
- Total amount received from borrowers.
- Month-to-date (MTD) and previous month-to-date (PMTD) analysis.
- Good loan and bad loan analysis.
- Average interest rate and DTI calculations.
- Loan status distribution.
- State-wise loan applications and funding.
- Loan purpose analysis.
- Employment length and home ownership analysis.
- Loan term analysis.

SQL concepts used:
- SELECT, WHERE and GROUP BY
- Aggregate Functions
- CASE Statements
- Joins
- CTEs
- Subqueries
- Date Functions
- Conditional Aggregation

### 2. Python Analysis

Used Python for data inspection, cleaning, and exploratory data analysis.

Key activities:

- Loaded and explored the loan dataset using Pandas.
- Checked data types and missing values.
- Identified duplicate records.
- Performed data cleaning and preprocessing.
- Analyzed loan status and borrower characteristics.
- Calculated important loan performance metrics.
- Created visualizations to understand patterns in the data.

Libraries: Pandas, NumPy and Matplotlib.

### 3. Excel Analysis

Used Excel to organize and analyze loan application data.

Work included:

- Data cleaning and formatting.
- Data validation.
- Pivot Tables and Pivot Charts.
- Loan purpose analysis.
- State-wise loan analysis.
- Funded amount and payment analysis.
- Summary reports and KPI calculations.

### 4. Power BI Dashboard

Created interactive dashboards to monitor loan performance and key business metrics.

The dashboard covers:

- Overall loan application summary.
- Total funded amount and amount received.
- Good loan vs bad loan performance.
- Monthly loan application trends.
- State-wise loan distribution.
- Loan purpose analysis.
- Employment length analysis.
- Home ownership and loan term analysis.
- Interactive filters and slicers.

### 5. Tableau Dashboard

Created visual reports to explore loan performance and borrower patterns.

Analysis includes:

- Loan status distribution.
- Monthly loan trends.
- State-wise performance.
- Good loan vs bad loan comparison.

## Key Insights

Based on the analysis, the following observations were identified:

1. Out of 38,576 loan applications, 33,243 were classified as good loans, representing 86.18% of total applications.
2. A total of 5,333 applications were classified as bad loans, accounting for 13.82%.
3. The total funded amount was approximately $435.76 million, while the total amount received was approximately $473.07 million.
4. Debt consolidation was the most common loan purpose.
5. Loans with a 36-month term were more common than loans with a 60-month term.
6. Fully Paid loans contributed the largest share of the amount received.
7. Interest rate and debt-to-income ratio were useful metrics for comparing loan performance across borrower segments.

## Project Structure

```text
bank-loan-analysis/
│
└── bank-loan-analysis/
    ├── SQL/
    ├── Python/
    ├── Excel/
    ├── PowerBI/
    ├── Tableau/
    └── README.md
```

## What I Learned

Through this project, I gained practical experience in:

- Working with financial datasets.
- Cleaning and preparing raw data.
- Writing SQL queries for business analysis.
- Performing exploratory data analysis using Python.
- Calculating and validating business KPIs.
- Creating interactive dashboards.
- Converting raw data into meaningful business insights.

## Conclusion

This project helped me understand how data analytics can be used to evaluate loan performance, analyze borrower behavior, and monitor financial KPIs.

By working with multiple tools, I practiced the complete analytics process, from data preparation and querying to visualization and business reporting.

## About Me

**Mohammad Varish**

B.Tech in Computer Science and Engineering

Skills: Excel | SQL | Python | Power BI | Tableau | Data Analytics

GitHub: https://github.com/mvaris54

LinkedIn: https://linkedin.com/in/mohammad-varish1/

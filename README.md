# Insurance-Data-Analysis

## Overview

This project is a comprehensive data analysis initiative focused on insurance data. It explores key metrics such as premium amounts, coverage amounts, claim amounts, policy types, customer demographics (e.g., gender, age groups), and claim statuses. The goal is to derive actionable insights for insurance companies, such as identifying trends in claims, high-risk policy types, and demographic patterns to optimize risk management, pricing strategies, and customer segmentation.

The project includes:
- A sample dataset of insurance policies and claims.
- A visualization dashboard built with tools like Tableau, Power BI, or similar (based on the provided screenshot).
- Scripts for data processing, analysis, and visualization (e.g., in Python or R).

This analysis can help stakeholders understand claim rejection rates, premium distributions, and correlations between variables like age, gender, and policy type.

## Key Features

- **Data Exploration**: Analyze trends in premiums, claims, and coverage across demographics.
- **Interactive Dashboard**: Visualizations including pie charts for gender distribution, bar graphs for claim amounts by policy type and age group, and metrics for total premium, coverage, and claim amounts.
- **Insights Generation**: Identify patterns such as higher claim amounts in certain age groups or policy types (e.g., Health, Travel, Auto, Life).
- **Claim Status Breakdown**: Track approved, rejected, pending, and settled claims.
- **Scalable Analysis**: Easily extendable to larger datasets for real-world applications.

## Sample Data Overview

The project includes a sample dataset (provided as `sample_data.png` or in CSV format if exported). Here's a brief summary of the data structure:

| Column          | Description                          | Example Values                  |
|-----------------|--------------------------------------|---------------------------------|
| Policy Number   | Unique identifier for the policy     | P1, P2, etc.                    |
| Customer ID     | Unique customer identifier           | C1, C2, etc.                    |
| Gender          | Customer's gender                    | Male, Female                    |
| Age Group       | Customer's age category              | 31-40, 41-50, etc.              |
| Policy Type     | Type of insurance policy             | Auto, Travel, Health, Life      |
| Start Date      | Policy start date                    | 13-03-2024, etc. (DD-MM-YYYY)   |
| End Date        | Policy end date                      | 13-03-2025, etc. (DD-MM-YYYY)   |
| Premium Amount  | Amount paid for the policy           | 2405.64, 10573.73, etc.         |
| Coverage Amount | Total coverage provided              | 85734.51, 86064.92, etc.        |
| Claim Amount    | Amount claimed (if applicable)       | NULL or values like 10390.60    |
| Claim Status    | Status of the claim                  | Pending, Rejected, Settled      |

- **Dataset Size**: The sample includes ~20 records, but the project is designed for larger datasets.
- **Key Insights from Sample**:
  - Policies span types like Auto, Travel, Health, and Life.
  - Claims include statuses such as Pending, Rejected, Settled.
  - Demographics: Mix of male/female customers across age groups (e.g., 31-40, 41-50, 51-60).

For a full dataset, export the provided image to CSV or use synthetic data generation scripts.

## Dashboard Overview

The project features a dashboard (screenshot provided as `dashboard.png`) for interactive visualization. Key elements include:

- **Metrics**:
  - Total Premium Amount: 5.97M
  - Total Coverage Amount: 600.33M
  - Total Claim Amount: 16.90M

- **Visualizations**:
  - **Pie Chart**: Gender distribution (e.g., Male: 50%, Female: 50%).
  - **Bar Graphs**:
    - Claim amount by policy type (e.g., Health highest at ~7.2M, followed by Auto, Travel, Life).
    - Claim amount by age group (decreasing trend from Adult to Young Adult).
    - Travel amount by policy type.
  - **Claim Status Bar**: Breakdown of claims (e.g., Settled: 4.4k, Rejected: 3.4k, Pending: 2.3k, etc.).

The dashboard is built using [Power BI]. To view it interactively, open the provided file or recreate it using the sample data.


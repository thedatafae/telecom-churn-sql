# Telecom Churn Analysis (SQL Project)

This repository contains a comprehensive **telecom customer churn analysis** project using SQL. The analysis explores customer behavior, subscription patterns, and factors influencing churn, providing actionable insights and recommendations for business decision-making.


## Repository structure
```
telecom-churn-sql/
│
├── data/
│ ├── customers.csv # Customer demographic information
│ ├── subscriptions.csv # Subscription details and billing info
│ └── usage_metrics.csv # Customer usage patterns and support interactions
│
├── sql/
│ └── churn_analysis.sql # SQL queries used to analyze churn and related metrics
│
├── reports/
│ └── insights_and_recommendations.pdf # Business insights and recommendations derived from analysis
│
└── README.md # Project overview and documentation
```

## Dataset Overview

- **Customers.csv**: Contains demographic information including `CustomerID`, `Age`, `Gender`, and `Tenure`.
- **Subscriptions.csv**: Includes subscription type, contract length, total spend, payment delays, and churn indicators (`Churn` as 0/1).
- **Usage_metrics.csv**: Records customer interactions such as usage frequency and support calls.
- **Total Rows**: ~440,800 combined across all datasets.


## Objectives

The main goals of this project are:

1. Analyze **customer churn patterns** in a telecom context.
2. Identify key factors influencing churn (age, gender, contract length, payment behavior, usage, support calls).
3. Evaluate revenue impact across different customer segments.
4. Provide **actionable recommendations** for retention strategies.


## Key Analysis Questions

The SQL queries address business-relevant questions such as:

- What is the **overall churn rate**?
- Which **subscription type** or **contract length** experiences the highest churn?
- How does **age**, **gender**, or **tenure** affect churn?
- Are **payment delays** or **support calls** linked to churn?
- Who are the **top high-value customers** by total spend?
- Which **tenure group** contributes most to revenue?
- How does **usage frequency** correlate with churn?



## SQL Queries

All analysis queries are available in:

`sql/churn_analysis.sql`

- The queries include both **aggregate calculations** and **grouped churn analysis**.
- Uses basic SQL functions like `COUNT`, `SUM`, `AVG`, `ROUND`, and `GROUP BY`.
- Designed to extract insights for both business metrics and decision-making.



## Insights & Recommendations

Detailed findings and actionable recommendations are provided in:

`reports/insights_and_recommendations.pdf`

Key highlights include:

- Subscription type and contract length influence churn significantly.
- Female customers have a higher churn rate than male customers.
- Higher support calls and payment delays correlate with higher churn.
- Age and tenure affect customer retention and spending patterns.
- High-value customers are identified for targeted retention strategies.



## How to Use This Repository

1. **Load the data** from the `data/` folder into your SQL environment.
2. **Run the queries** from `sql/churn_analysis.sql` to reproduce the analysis.
3. **Review the insights** in `reports/insights_and_recommendations.pdf`.
4. Optionally, **modify queries** to explore additional business questions or segment analysis.



## Technologies Used

- SQL (PostgreSQL/MySQL compatible syntax)
- CSV for dataset storage
- PDF for reporting insights



## Author

**Faizan Ahmed Khan**  
- BS Computer Science, HITEC University, Pakistan  
- Visiting Student, Skolkovo Institute of Science and Technology (InteRussia STEM Fellow)  
- 🌐 [Portfolio](https://thedatafae.framer.website) | 🔗 [LinkedIn](https://linkedin.com/in/thedatafae)


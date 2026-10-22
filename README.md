# Home Credit — Exploratory Data Analysis

## Project Overview

This project explores applicant characteristics, financial information, and previous loan application history to identify patterns associated with payment difficulties.

The analysis uses Python to assess data quality, examine variable distributions, explore relationships, and investigate three research questions.

## Research Questions

1. How is applicant age associated with payment difficulties?
2. How are external source scores associated with payment difficulties?
3. How is previous loan application history associated with payment difficulties?

## Datasets

| Dataset | Rows | Columns |
|---|---:|---:|
| Application data | 307,511 | 122 |
| Previous application data | 1,670,214 | 37 |

The datasets are linked using `SK_ID_CURR`.

## Tools and Skills

- Python
- Pandas and NumPy
- Matplotlib
- Exploratory Data Analysis
- Data cleaning and missing-value assessment
- Descriptive statistics and correlation analysis
- Data visualization

## Key Findings

- Payment difficulty rates were higher among younger applicants in the analysed age groups.
- Higher external source score quartiles were associated with lower payment difficulty rates.
- Applicants with more than 10 previous applications had a higher payment difficulty rate than applicants without previous applications.

## Limitations

This project focuses on exploratory analysis. The findings describe associations and do not establish causation or confirm predictive performance.

## Files

- `home_credit_eda.ipynb` — Notebook containing the analysis, Python code, visualizations, and findings.

## Disclaimer

This project is for educational and portfolio purposes. The findings should not be used as the sole basis for real-world credit decisions.

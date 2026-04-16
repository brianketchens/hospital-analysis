# Hospital Patient Analysis

An exploratory and predictive analysis of inpatient hospital care patterns 
developed as a portfolio demonstration of healthcare data analytics competency 
in R.

## Project Overview

This project analyzes 55,500 inpatient patient records spanning May 2019 
through May 2024, examining length of stay, billing patterns, admission 
characteristics, and test result outcomes across six medical conditions, 
three admission types, and five insurance providers.

The analysis demonstrates a production-oriented analytical workflow including 
a reusable data cleaning pipeline, consistent visualization standards, and 
structured predictive modeling using the tidymodels framework — skills directly 
applicable to hospital analytics, clinical operations, and healthcare 
business intelligence roles.

## Key Skills Demonstrated

| Skill | Implementation |
|---|---|
| Functional programming | Custom reusable cleaning function applied via `purrr::map()` |
| Feature engineering | LOS calculation, date features, age groups, billing tiers |
| Data quality management | Audit trail flagging — 108 negative billing records documented |
| Data visualization | Custom `ggplot2` theme applied consistently across all charts |
| Predictive modeling | Two `tidymodels` pipelines with proper train/test evaluation |
| Analytical communication | Null results interpreted and reported with clinical context |

## Repository Structure

```
hospital-analysis/
├── data/
│   └── healthcare_clean.csv        # Cleaned analytical dataset
├── hospital_analysis.Rmd           # Full analytical report (R Markdown)
├── hospital_dashboard.Rmd          # Interactive flexdashboard
├── hospital_analysis.html          # Rendered HTML report
├── hospital_dashboard.html         # Rendered HTML dashboard
└── README.md                       # This file
```

## Report Sections

1. **Executive Summary** — Key findings at a glance
2. **Background & Objectives** — Analytical questions and dataset overview
3. **Data Preparation** — Cleaning pipeline, quality flagging, feature engineering
4. **Exploratory Findings** — Four visualizations with operational interpretation
5. **Predictive Modeling** — Linear and logistic regression via tidymodels
6. **Limitations** — Honest assessment of synthetic data constraints
7. **Recommendations** — Extensions for real clinical data environments

## Key Findings

- Average length of stay was **15.5 days** with less than one day of variation 
across all 18 condition-admission type combinations
- Billing averaged **$25,539** per admission with no material payer mix 
differential across five insurance providers
- Predictive modeling confirmed absence of learnable signal — consistent with 
synthetically generated data where outcomes are sampled independently of 
patient characteristics
- Recommendations for extending this framework to HCUP administrative data 
are provided in the report

## Tools and Packages

| Category | Tools |
|---|---|
| Data manipulation | `tidyverse`, `janitor`, `skimr` |
| Visualization | `ggplot2`, `plotly` |
| Modeling | `tidymodels` |
| Reporting | `R Markdown`, `knitr`, `kableExtra` |
| Dashboard | `flexdashboard`, `DT` |

## Data Source

Prasad, R. (2024). *Healthcare Dataset*. Kaggle.  
https://www.kaggle.com/datasets/prasad22/healthcare-dataset

## Author

**Brian E. Ketchens**  
[LinkedIn](https://linkedin.com/in/brian-ketchens) | 
[GitHub](https://github.com/brianketchens)

---
*Analysis conducted in R | Report generated with R Markdown*
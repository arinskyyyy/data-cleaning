# Data Cleaning Portfolio

**Author:** Chaitanya (@arinskyyyy)  
**Credential:** Minor in Artificial Intelligence — IIT Ropar (2024)  
**Stack:** Python · Pandas · NumPy · Jupyter Notebook  

An end-to-end collection of 5 automated data cleaning pipelines spanning real-world domains — astrophysics, healthcare, e-commerce, finance, and social media analytics. Each project transforms raw, messy source data into a fully structured, ML-ready dataset using production-grade Python pipelines.

---

## Projects

| # | Project | Domain | Rows Cleaned | Key Challenge |
|---|---------|--------|-------------|---------------|
| 01 | [Kepler's Exoplanet Pipeline](./01_NASA_Exoplanet_Archive_(Astrophysics)) | Astrophysics | 9,564 → 8,945 | 7,270 missing values, extreme outliers, categorical encoding |
| 02 | [Renal Calculi Medical Pipeline](./02_Renal_calculi) | Healthcare | Multi-source merge | Duplicate patients, inconsistent medical features, dataset merging |
| 03 | [E-Commerce Sales Pipeline](./03_E-commerce%20Sales%20Data%20Pipeline) | Retail | 224 orders | Mixed currencies, invalid SKUs, inconsistent date formats |
| 04 | [Financial Transactions Fraud Prep](./04_Financial%20Transactions%20Fraud%20Prep) | Finance & Banking | 350 transactions | Mixed timestamp formats, fragmented merchant names, outlier capping, feature engineering |
| 05 | [Social Media Analytics Cleanup](./05_Social%20Media%20Analytics%20Cleanup) | Marketing | 292 posts | 4-platform schema unification, timezone normalization, test account removal |

---

## What Each Pipeline Delivers

Every project in this repository follows the same rigorous standards:

- **Zero nulls** in the final output dataset
- **Automated pipeline** — runs end-to-end with minimal manual input
- **Documented decisions** — every cleaning step is explained in the notebook
- **Clean CSV output** — immediately usable for ML modeling or BI dashboards
- **Reproducible** — virtual environment + requirements file included in each folder

---

## Domains Covered

```
Astrophysics   ████████████████████  NASA Kepler exoplanet records
Healthcare     ████████████████████  Kidney stone patient data
E-commerce     ████████████████████  Online sales transactions
Finance        ████████████████████  Fraud detection prep
Social Media   ████████████████████  Omnichannel engagement metrics
```

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.14 | Core language |
| Pandas | Data manipulation and pipeline logic |
| NumPy | Numerical operations and outlier handling |
| Jupyter Notebook | Interactive development and documentation |
| Git & GitHub | Version control |

---

## Repository Structure

```
data-cleaning/
├── 01_NASA_Exoplanet_Archive_(Astrophysics)/
│   ├── cleaning_pipeline.ipynb
│   ├── cleaned_cumulative.csv
│   ├── images/
│   ├── environment.yml
│   ├── requirements.txt
│   └── README.md
├── 02_Renal_calculi/
│   ├── cleaning_pipeline.ipynb
│   ├── cleaned_merged_renal_calculi.csv
│   ├── herbal_drugs.csv
│   ├── phytochemicals.csv
│   └── README.md
├── 03_E-commerce Sales Data Pipeline/
│   ├── cleaning_pipeline.ipynb
│   ├── ecommerce_sales_raw.csv
│   ├── cleaned_ecommerce_sales_raw.csv
│   ├── images/
│   ├── environment.yml
│   ├── requirements.txt
│   └── README.md
├── 04_Financial Transactions Fraud Prep/
│   ├── cleaning_pipeline.ipynb
│   ├── images/
│   ├── environment.yml
│   └── README.md
└── 05_Social Media Analytics Cleanup/
    ├── cleaning_pipeline.ipynb
    ├── cleaned_csv.png
    ├── environment.yml
    └── README.md
```

---

## About

This portfolio was built as part of my applied learning at IIT Ropar's Minor in Artificial Intelligence program, with a focus on data engineering fundamentals. Each pipeline reflects production-oriented thinking — not just cleaning data, but building systems that could scale.

For freelance data cleaning and preprocessing work:  
**Fiverr:** [fiverr.com/arinskyyyy](https://fiverr.com/arinskyyyy)  
**GitHub:** [github.com/arinskyyyy](https://github.com/arinskyyyy)
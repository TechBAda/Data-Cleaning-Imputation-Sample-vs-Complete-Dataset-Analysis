# Data Cleaning & Missing Value Imputation 

## Project Overview
This project performs an end-to-end data cleaning and preprocessing workflow using two related datasets:

- **sample_data.csv**
- **complete_data.csv**

The core objective is to explore missing values, apply appropriate imputation strategies, compare cleaned outputs, and prepare the dataset for downstream modeling.

---

## Datasets
- **sample_data.csv** — Contains missing or incomplete records used for cleaning demonstrations.
- **complete_data.csv** — Fully populated dataset used for comparison and validation.

---

## Key Data Cleaning Steps
- Identifying missing values across rows and columns  
- Dropping duplicate entries  
- Recoding inconsistent values  
- Outlier detection  
- Imputation using:
  - Mean / median  
  - Mode (categorical)  
  - Forward / backward fill  
- Comparing imputed sample data with complete dataset  
- Merging cleaned datasets  

---

## Exploratory Data Analysis
Performed analysis on:
- Column distributions  
- Missingness patterns  
- Row-level completeness  
- Data type reconciliation  
- Summary statistics  

Visualization tools:
- `pandas`
- `matplotlib`
- `seaborn`

---

##  Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Google Colab  

---

##  Repository Structure
project/
│
├── notebooks/
│ └── DataCleaning_MissingValues_Imputation.ipynb
│
├── data/
│ ├── complete_data.csv
│ └── sample_data.csv
│
└── README.md

---

##  Key Outcomes
- Understanding of real-world missing data patterns  
- Application of multiple imputation strategies  
- Comparison of cleaned vs complete datasets  
- Professional workflow suitable for analytics and ML preparation  

---

### Author
**Adanma Okoroafor**  
MS Artificial Intelligence & Business Analytics (FinTech)  
University of South Florida  


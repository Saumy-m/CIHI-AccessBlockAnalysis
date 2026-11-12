# CIHI-AccessBlockAnalysis
Evaluating Canadian ER Access Block index and forecasting patient surges using CIHI NACRS data to reduce hospital wait times.

## 1. Problem Statement:
In 2025–2026 (Q1–Q4), Canadian Emergency Departments (EDs) faced severe operational bottlenecks: while the median wait time for an initial physician assessment sat at roughly 2 hours, 1 in 10 patients waited over 5 hours, and 90% of admitted patients remained in the ED for up to 46.5 hours—despite total annual unscheduled visits declining by 3.1% (from 16.1M to 15.6M).

This project investigates the root drivers of this Access Block paradox by analyzing historical Q1–Q4 patient volume trends, triage acuity, and admission-to-discharge wait ratios from CIHI NACRS data. Using pandas and XGBoost, the analysis builds a predictive forecasting framework to anticipate seasonal patient surges and high-acuity bottlenecks—enabling hospital administrators to proactively optimize physician shift schedules, align diagnostic capacity, and mitigate severe overcrowding before wait times spike.

## 2. Key Findinngs and Impact (Summary)



## 3. Data Source & Attribution
* Primary Dataset: [CIHI NACRS Emergency Department Visits and Lengths of Stay (2025–2026, Q1–Q4)](https://www.cihi.ca/en/nacrs-emergency-department-visits-and-lengths-of-stay) — Download the `.xlsx` data tables directly from the landing page and place them in `data/raw/`.

* Attribution: Data sourced from the Canadian Institute for Health Information (CIHI). All analyses, Access Block Index calculations, and predictive models in this repository are independent work.


## 4. Analytical Methodology & Tech Stack
* Data Cleaning & Feature Engineering (`pandas`)
* Access Block Ratio Formulation
* Time-Series Forecasting (`XGBoost`, `scikit-learn`)

## 5. How to Run This Project
* Setup steps (`pip install -r requirements.txt`) and folder guide

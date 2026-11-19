# Data Exploration Projects

Exploratory data analysis (EDA) notebooks on public datasets, plus SQL exploration of COVID-19 data.

## Contents

| File | Dataset | What it explores |
|---|---|---|
| `911.ipynb` | Emergency (911) calls | Call reasons (EMS, Traffic, Fire) by day of week, month and hour; busiest townships |
| `covid19.ipynb` | COVID-19 by country | Cases and deaths by WHO region, countries with most active cases, correlation of deaths with other measures |
| `loan_data.ipynb` | Lending Club loans | Loan purposes, FICO score and interest rate by credit policy, which loans are not fully paid |
| `sql/covid_project.sql` | COVID deaths and vaccinations (`sql/*.xlsx`) | Death rate, infection rate vs population, highest counts by country and continent, vaccinations |

## Tools

Python · pandas · NumPy · Matplotlib · Seaborn · SQL Server (T-SQL)

## How to run

The notebooks were written in Google Colab and read their CSV files from `/content/`. To run them locally, download the dataset, place the CSV next to the notebook, and change the path in the `pd.read_csv(...)` cell.

```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook
```

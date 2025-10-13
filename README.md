# Chinook SQL Query Examples

A small, personal collection of Jupyter notebooks to practice and demonstrate SQL query skills using the **Chinook** sample database (SQLite).

## What’s in this repo
- `data/Chinook_Sqlite.sqlite` — Chinook SQLite database (sample data)
- `notebooks/01_basic_select.ipynb` — basic SELECT, filtering, sorting
- `notebooks/02_joins_and_aggregations.ipynb` — joins, aggregations, CTE examples, windows function
- `environment.yml` — conda environment (reproducible)
- `.gitignore` — ignore rules for notebooks and OS/IDE files

## Goals
This repository is a demonstration of practical SQL skills:
- composing joins and aggregations
- grouping and ranking results
- using CTEs to structure intermediate results
- mixing SQL with Python (pandas + SQLAlchemy) for exploratory analysis

## Quick start (reproduce locally)
1. Clone the repo:
   ```bash
   git clone <your-repo-url>
   cd chinook_sql_query_examples

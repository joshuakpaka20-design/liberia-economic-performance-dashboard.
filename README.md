# Liberia Economic Performance Dashboard (2010–2025)

A beginner-to-intermediate portfolio project demonstrating a practical analytics workflow with **Python, Pandas, Matplotlib, SQLite SQL, and Power BI**.

> **Important data note:** This repository uses an illustrative practice dataset. The figures are **not verified official statistics for Liberia** and must not be used as factual economic reporting, policy evidence, or investment advice.

## Project objectives

- Inspect data quality, types, duplicates, and annual coverage.
- Explore GDP, GDP growth, inflation, and GDP per capita.
- Calculate trade balance and compare exports with imports.
- Examine population growth, internet usage, and electricity access.
- Practice SQL aggregations, `CASE`, `GROUP BY`, `HAVING`, subqueries, CTEs, `LAG()`, `RANK()`, and `PARTITION BY`.
- Prepare an analysis-ready CSV for Power BI visualization.

## Tools

- Python
- Pandas
- Matplotlib
- SQLite (`sqlite3`)
- Jupyter Notebook
- Power BI Desktop and DAX (dashboard build)

## Repository structure

```text
liberia-economic-performance-dashboard/
├── README.md
├── requirements.txt
├── .gitignore
├── liberia_economic_analysis.ipynb
├── data/
│   ├── liberia_economic_practice.csv
│   └── liberia_economic_analysis.csv
├── sql/
│   └── analysis_queries.sql
└── power_bi/
    └── README.md
```

## Run the notebook

1. Clone or download the repository.
2. Install the Python dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook or JupyterLab from the repository root.
4. Open `liberia_economic_analysis.ipynb`.
5. Run cells from top to bottom.

The notebook reads `data/liberia_economic_practice.csv`, performs analysis, and writes `data/liberia_economic_analysis.csv`. It also creates a local SQLite database named `liberia_economic.db` while running the SQL section.

## Selected findings from the practice data

- Highest annual GDP growth: **8.7% in 2013**.
- Lowest annual GDP growth: **−3.0% in 2020**.
- Highest inflation: **27.6% in 2019**.
- Exports are lower than imports in every year in this dataset.
- Largest trade deficit: approximately **US$1.10 billion in 2014**.
- GDP per capita rises from **US$513.40 in 2010** to **US$915.30 in 2025**.
- Internet-use and electricity-access percentages rise across the period.

These are observations about the practice dataset only—not verified claims about Liberia's actual economy.

## Power BI dashboard

The analysis-ready dataset is `data/liberia_economic_analysis.csv`. Suggested visuals:

1. KPI cards: average GDP growth, average inflation, latest GDP, latest GDP per capita, and average trade balance.
2. GDP trend (2010–2025).
3. GDP growth versus inflation.
4. Exports versus imports.
5. Trade balance by year.
6. GDP per capita trend.
7. Internet use versus electricity access.

See [`power_bi/README.md`](power_bi/README.md) for dashboard notes. Add your `.pbix` file and a dashboard screenshot here when ready.

## Limitations

- The data is illustrative/synthetic and is not sourced from LISGIS, the World Bank, or another official provider.
- There are only 16 annual observations.
- The analysis is descriptive; correlation does not prove causation.
- Validate any real-world conclusion against official data before using it outside this learning portfolio.

## Skills demonstrated

**Data cleaning · Exploratory data analysis · Feature engineering · Python · Pandas · Matplotlib · SQL · SQLite · Window functions · KPI development · Power BI · Data storytelling**

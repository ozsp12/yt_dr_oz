# Data Analyst Fast Track

Companion material for the video lesson **[Data analyst fast track: examples of commonly used Python, SQL, and DAX functions](https://youtu.be/dLDmXewxwpA)**.

## Contents

The notebook starts with a synthetic student dataset and covers common operations across three ecosystems:

- **Python and pandas:** inspection, selection, filtering, grouping, sorting, missing values, and reading or writing CSV and Parquet files;
- **SQL and DuckDB:** `SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`, aggregations, and basic creation, insertion, and deletion operations;
- **DAX and Power BI:** aggregation functions, filter context, iterators, and conditional functions.

## Files

| File | Purpose |
|---|---|
| [`fast_track.ipynb`](fast_track.ipynb) | Computational walkthrough for the lesson |
| [`df_fast_track.csv`](df_fast_track.csv) | Tabular data with a `;` delimiter |
| [`df_fast_track.parquet`](df_fast_track.parquet) | Columnar version of the same data |
| [`fast_track.pbix`](fast_track.pbix) | Report for Power BI Desktop |

## Running the notebook

From the repository root, activate the environment and launch JupyterLab:

```bash
conda activate ai-data-citizen
jupyter lab
```

Run the notebook from this folder so that relative paths to the CSV and Parquet files resolve correctly. Synthetic data generation uses a fixed seed and reference date, allowing the results to be reproduced.

## Note on DAX

DAX is more than a variant of SQL. Its expressions are evaluated within row and filter contexts specific to the tabular model. The functions listed in the notebook provide an introduction; real-world measures require a coherent dimensional model and correctly defined relationships.

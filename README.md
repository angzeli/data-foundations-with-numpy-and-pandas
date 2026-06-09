# 📘 Data Foundations with NumPy and pandas

This repository is a beginner-friendly, data-focused bridge from basic Python data structures to plot-ready tables.

The immediate purpose is to prepare learners for a later Matplotlib tutorial. Before figures can be clear, the underlying data needs to be readable, inspected, cleaned, transformed, reshaped, and exported in a deliberate way.

The longer-term purpose is to support practical workflows that may later branch into scientific measurement data, FYP analysis workflows, finance data workflows, and project-specific tools such as chem-lab-forge or a market-criticism-index.

---

## 🎯 What Part 1 Covers

Part 1 focuses on the foundations needed before plotting:

- NumPy arrays, pandas Series, and pandas DataFrames
- Reading and inspecting CSV files
- Selecting, filtering, and sorting rows and columns
- Cleaning numeric data and missing values
- Creating derived columns with vectorized calculations
- Reshaping wide and long data
- Grouping replicates and building summary tables
- Joining metadata with measurements
- Exporting clean, plot-ready CSV files

---

## 🚫 What Part 1 Intentionally Does Not Cover

This is not a full NumPy or pandas reference course.

Part 1 avoids:

- advanced indexing edge cases
- full statistical modelling
- dashboard or web app development
- scraping, APIs, or automation workflows
- machine-learning preprocessing pipelines
- finance-specific chapters
- Matplotlib figure design

Those topics can be added later once the data foundations are stable.

---

## 📚 Recommended Order

Work through the notebooks in order inside `part_1/`:

1. `01_data_containers_for_plotting.ipynb`
2. `02_reading_and_inspecting_csv_data.ipynb`
3. `03_selecting_filtering_and_sorting_data.ipynb`
4. `04_cleaning_numeric_data_and_missing_values.ipynb`
5. `05_vectorized_calculations_and_derived_columns.ipynb`
6. `06_wide_long_and_tidy_data.ipynb`
7. `07_grouping_aggregation_and_replicates.ipynb`
8. `08_joining_metadata_with_measurements.ipynb`
9. `09_exporting_plot_ready_data.ipynb`
10. `10_mini_project_raw_csv_to_plot_ready_table.ipynb`

Each notebook is intended to be runnable from top to bottom without depending on hidden state from another notebook.

---

## 🧭 How This Prepares for Matplotlib

Matplotlib usually needs either clean `x` and `y` arrays or a DataFrame with clear columns for variables, groups, labels, and summary statistics.

Part 1 teaches how to get there:

- raw CSV data becomes inspected DataFrames,
- string-like numeric columns become real numeric columns,
- metadata is joined to measurements,
- replicates are summarized without deleting the raw observations,
- and final tables are exported for later plotting.

The next tutorial series can then focus on figure design instead of fixing avoidable data problems inside plotting code.

---

## 🌱 Future Extensions

This project is deliberately general.

Later parts can extend the same patterns to:

- lab-style measurement tables,
- FYP data cleaning and reporting workflows,
- finance time series and portfolio-style data,
- domain-specific measurement campaigns,
- and reusable plotting pipelines.

The core idea stays the same: keep raw data raw, build clean intermediate tables, and make the final plotting data explicit.

# 📘 Part 1 — Data Foundations for Plotting

Part 1 teaches the NumPy and pandas foundations needed before plotting. The focus is not on memorising every API method, but on building clean, inspectable, plot-ready data structures from small raw tables.

The notebooks are intentionally practical: each topic starts from a small toy dataset, introduces one data concept, shows a worked example, and closes with a short takeaway.

---

## 🎯 Learning Path

1. `01_data_containers_for_plotting.ipynb` — arrays, Series, DataFrames, shape, and labels
2. `02_reading_and_inspecting_csv_data.ipynb` — `read_csv`, basic inspection, and raw-data discipline
3. `03_selecting_filtering_and_sorting_data.ipynb` — columns, rows, `loc`, `iloc`, filtering, and sorting
4. `04_cleaning_numeric_data_and_missing_values.ipynb` — missing values, invalid numbers, and raw vs cleaned data
5. `05_vectorized_calculations_and_derived_columns.ipynb` — unit conversion, normalization, and baseline subtraction
6. `06_wide_long_and_tidy_data.ipynb` — `melt`, `pivot`, and tidy long-form data
7. `07_grouping_aggregation_and_replicates.ipynb` — means, standard deviations, counts, and standard errors
8. `08_joining_metadata_with_measurements.ipynb` — `merge`, metadata, join validation, and unmatched rows
9. `09_exporting_plot_ready_data.ipynb` — processed data folders and `to_csv`
10. `10_mini_project_raw_csv_to_plot_ready_table.ipynb` — full raw CSV to plot-ready table workflow

---

## 🧠 Pedagogical Shape

Each notebook follows a consistent pattern:

- why the topic matters for plotting,
- what the concept is,
- how to use it in a small worked example,
- what to watch out for,
- and the key takeaway.

The notebooks use standard NumPy and pandas. Matplotlib is deliberately left for a later tutorial series.

---

## 📦 Data

Small CSV examples live in `../data/part1/`.

The notebooks use relative paths and include a small project-root helper so they can be run either from the repository root or from inside `part_1/`.

Generated processed CSV files are written to `../data/part1/processed/` when the export notebooks are run. These generated CSV files are ignored by git so learners can rerun the notebooks without creating repository noise.

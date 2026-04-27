# World Cup Dashboard

A small project containing a Tableau dashboard that visualizes historical World Cup results.

This repository contains the dashboard workbook, the dataset used to build the visualizations, and a screenshot preview.

## What I made

- A Tableau workbook/dashboard that explores World Cup match results and related statistics.
- Visualizations include (examples): match results over time, top scorers, team performance by tournament, and summary statistics.

## Files in this repository

- `dashboard/World_Cup_Dashboard.twbx` — Tableau packaged workbook containing the dashboard (open with Tableau Desktop or Tableau Public).
- `dataset/world_cup_results.xlsx` — Source dataset used for the visualizations (Excel file).
- `screenshot/` — Screenshot(s) showing the dashboard preview.
- `README.md` — This file.

## How to open and view

1. Install Tableau Desktop or Tableau Public (Tableau Public is free).
2. Open `dashboard/World_Cup_Dashboard.twbx` in Tableau.
3. If Tableau prompts for data sources, point it to `dataset/world_cup_results.xlsx` (should be embedded in the packaged workbook already).

## Notes and recommendations

- The repo currently tracks some binary files and macOS system files (e.g. `.DS_Store`). If you prefer a cleaner repo, consider adding a `.gitignore` with entries like:

	- `.DS_Store`
	- `*.twbx` (if you want to keep workbook binaries out of version control)
	- `*.xlsx` (if datasets are large and should be stored elsewhere)

- If you want large files removed from history, I can help rewrite history safely (we can use BFG or `git filter-repo`).

## Contributing

If you'd like me to make improvements (add README details, add a `.gitignore`, move datasets to Git LFS, or extract CSVs), tell me which items and I'll implement them and push the changes.

## Contact

Owner: keshavgoel2101 (GitHub: `git@github.com:keshavgoel2101`)

---

Updated README to list contents and opening instructions.
# World_Cup_Dashboard

# Iris Analysis Project

## Overview
This project analyzes the Iris dataset using Python and Pandas.

## Requirements
- Python
- uv
- Pandas
- Jupyter Notebook

## Setup Instructions

1. Open a terminal in the project directory.
2. Install the project dependencies:

   uv sync

3. Start Jupyter Notebook:

   uv run jupyter notebook

4. Open iris_analysis.ipynb.
5. Run all notebook cells from top to bottom.

## Dataset
The dataset is stored in data/iris.csv.

## Analysis
The notebook explores the dataset structure, calculates descriptive statistics,
counts flower species, compares average measurements, and filters records
based on petal length.

## Output Files
- output/species_summary.csv
- output/filtered_iris.csv

## Findings
The analysis compares numerical measurements across the Iris species.
The filtered dataset contains flowers with petal lengths greater than 5 cm.
# Data Cleaning Project: Cafe Sales Dataset

This project focuses on cleaning and preparing raw data for analysis. The process involves identifying and handling missing values, removing duplicates, detecting outliers, and correcting data inconsistencies to improve data quality.

## Objective
- Identify and handle missing values.
- Detect and remove duplicates records.
- Identify and handle outliers.
- Correct inconsistent data formats and data types.

## Tools and Technologies
- Python
- Pandans
- NumPy
- Matplotlib
- UV
- Jupyter Notebook

## Project Workflow
1. **Data Loading:** Import the raw dataset into Python.
2. **Data Inspection:** Examine the dataset structure, data types, and summary statistics.
3. **Data Cleaning:** Handle missing values, duplicates, inconsistencies, and outliers.
4. **Data Validation:** Verify that the cleaned dataset meets the required quality standards.
5. **Data Export:** Save the cleaned dataset for further analysis.

## Project Structure

```text
cafe_sales_data_cleaning/
|
|--- dataset/
|   |---dirty_cafe_sales.csv        # original dataset
|   └── clean_cafe_sales.csv        # cleaned dataset
|
|--- cafe_sales.ipynb               # notebook
|
|--- Main.py
|
|--- outliers_hndling.ipynb         # Notebook for practising outlier detection and handling
|
|--- pyroject.toml
|--- README.md
└── uv.lock
```

## Installation

1. Clone the repository

    ```bash
        git clone https://github.com/ikinoti/cafe_sales_data_cleaning.git
    ```

2. Install UV   # checkout uv online documentation for guidance

3. Navigate to the project folder

    ```bash
        cd cafe_sales_data_cleaning/
    ```

4. sync the environment and dependencies:
    ```bash
        uv sync
    ```

## How to Use
Open the Jupyter Notebook file and run the cells sequentially to inspect, clean, and export the dataset.

## Results
The project aims to produce a clean, consistent, and reliable dataset suitable for further analysis and visualisation.

## Author
kinoti

## Licence
This project is available for educational and learning purposes.
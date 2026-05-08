# Healthcare Data Cleaning Project (Python)

## Overview
This project focuses on cleaning and preparing a "messy" healthcare dataset using Python and the Pandas library. The goal was to transform raw data into a clean format suitable for further statistical analysis.

## Key Challenges Addressed
* **Data Type Conversion:** Fixed inconsistent types (e.g., converting "Eighty" to `80.0`) and ensured numeric columns were correctly cast as `float` or `int`.
* **Anomaly Detection:** Identified and handled outliers, such as impossible ages (150) and extreme heart rate readings (250).
* **Feature Standardization:** Standardized temperature readings by converting Celsius to Fahrenheit and cleaned categorical values in the `RiskLevel` column.
* **Missing Values:** Handled `NaN` values and "Unknown" entries using mean/median imputation.

## Tools Used
* **Python 3**
* **Pandas**
* **NumPy**

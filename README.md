# Pressure-Derived Modeling of Vascular Aging Using NHANES and PWDB

This repository contains the Python analysis code and output tables for the manuscript:

**A Pressure-Derived Biomechanical Framework for Modeling Age-Associated Vascular Stiffening in Public Cardiovascular Data**

## Overview

This study uses public NHANES 2017–2018 blood pressure data and PWDB baseline virtual pulse-wave data to evaluate pressure-derived markers of vascular aging.

The analysis calculates:

- Pulse pressure
- Mean arterial pressure
- Relative stiffness index
- Apparent compliance index
- Age-group trends
- Correlation analysis
- Multivariable regression models
- Directional comparison with PWDB pulse-wave variables

## Files

- `arterial_stiffness_analysis.ipynb`: Python notebook used for data cleaning, analysis, and figure generation.
- `table1_cohort_characteristics.csv`: NHANES cohort characteristics.
- `table2_age_group_trends.csv`: NHANES age-group pressure-derived vascular trends.
- `table3_regression_summary.csv`: NHANES adjusted regression summary.
- `table4_age_correlations.csv`: NHANES age correlations.
- `table4_pwdb_validation_table.csv`: PWDB validation table.
- `table5_pwdb_age_correlations.csv`: PWDB age correlations.
- `table6_pwdb_linear_trends.csv`: PWDB linear trend results.
- `table7_directional_agreement.csv`: Directional agreement between NHANES and PWDB trends.

## Data Sources

The NHANES 2017–2018 data are publicly available from the Centers for Disease Control and Prevention National Center for Health Statistics.

The Pulse Wave Database baseline subject data are publicly available through Zenodo.

## Software

The analysis was performed in Python using:

- pandas
- NumPy
- SciPy
- statsmodels
- Matplotlib

## Author

Arman Mohammed  
Frisco Centennial High School

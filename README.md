# Arizona County Education & Health Analysis (2020–2024)

This project analyzes the relationship between school distribution and health metrics across Arizona counties from 2020 to 2024. The goal is to assess correlations between normalized school data (schools per 10,000 residents) and public health outcomes using polynomial regression (degrees 1–3). 

## Features

- Normalizes school counts (by type and class) per 10,000 residents.
- Merges annual county-level health data.
- Applies polynomial regression (degrees 1, 2, and 3) between school and health metrics.
- Tracks R² values for each relationship across 2020–2024.
- Saves top 5 relationship plots for each polynomial degree.
- Exports CSVs summarizing model strength.

![degree1_Drug_Overdose_Mortality_Rate_(Hispanic)_vs_MIDDLE_PER_10K](https://github.com/user-attachments/assets/7e5bebac-1d20-4381-b01d-fe804366a47d)

![newplot](https://github.com/user-attachments/assets/f4088416-f986-447b-9d08-d02e61dd9886)

## Data Sources

- **School data:** Arizona Department of Education
- **Population data:** U.S. Census Bureau
- **Health metrics:** County Health Rankings & Roadmaps

## Outputs
- relationship_summary_degree_1.csv, degree_2.csv, degree_3.csv: **Ranked model results**
- top_model_r2_all_degrees_2020_to_2024.csv: **R² trends across all years**
- top_relationship_plots/: **Saved top 5 plots per degree**

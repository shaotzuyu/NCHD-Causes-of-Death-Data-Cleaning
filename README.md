# NCHS-Causes-of-Death-Data-Cleaning

This repository contains working code & ideas using county-level causes of death records from the US National Vital Statistics System (NVSS), ACS, or census.
Detailed descriptions are provided in the files.

File Descriptions
1. MMR-calculation.R
  - Purpose: Calculates the Multiple Mortality Rate (MMR) for each county and year.
  - Function: Analyzes death records to identify cases with multiple distinct ICD-10 cause-of-death classifications and computes MMR at the county level.

2. NVSS-CoD-loop.R
  - Purpose: Prepares county-level mortality data (2000–2022) for analysis by standardizing cause-of-death coding.
  - Function: Cleans, formats, and ensures each county has complete cause-of-death and age-group mortality records to allow accurate comparisons over time.
    
3. NVSS-CoD-network.R
  - Purpose: A working project using a network approach to analyze multiple underlying causes of death across counties.
  - Function: Constructs county-level networks based on shared cause-of-death patterns.

# Module-1-Healthcare-Data-Analysis-and-Insights
Module 1: Healthcare assignment

Overview
The objective of this project is to analyze a comprehensive healthcare dataset containing medical examinations, hospitalization details, and customer profiles. The goal is to perform data cleaning, transformation, and analysis to extract actionable insights regarding patient health profiles, medical histories, and healthcare costs.

The assignment is divided into four main sections:

1. Data Cleaning 
  This section focuses on handling missing or incomplete data points within the dataset:
  Identifying missing values designated by a ? symbol.
  Imputing missing date information (filling month with "Sep" and year with the rounded average).
  Using mode imputation (most frequent value) to fill missing entries for smoker, Hospital tier, and City tier.
  Handling any missing State ID values by labeling them as "Unknown".

2. Data Transformation 
  This step prepares and structures the data for deeper analysis:
  Splitting customer full names into Title, First Name, and Last Name.
  Converting structural columns like NumberOfMajorSurgeries into a clean numerical format.
  Fixing formatting inconsistencies in the data and standardizing currency fields.
  Creating custom categorical data columns: Weight Status (derived from BMI) and Diabetes Status (derived from HbA1C).
  Consolidating separate birth details to create a standard Date of Birth field and calculating each patient's actual age as of June 8, 2023.

3. Data Exploration, Analysis & Visualization 
  Using Excel Pivot Tables and Pivot Charts, you are required to merge all underlying data tables via VLOOKUP into a master sheet named "Healthcare" and visually analyze specific correlations:
  Pie/Donut Charts: To show cancer history distribution among smokers vs. non-smokers, as well as surgical histories based on transplant status.
  Column/Bar Charts: To compare how healthcare charges vary by weight/diabetes status and across different hospital tiers by state.
  Line/Scatter Plots: To explore correlations between age and clinical metrics (BMI, HbA1C) as well as overall healthcare costs.

4. Dashboard Creation
  The final deliverable is an interactive, consolidated Excel Dashboard containing all the charts listed above. It must include functional interactive Slicers for both Weight Status and Diabetes Status so a user   can filter the entire dataset dynamically with a single click.

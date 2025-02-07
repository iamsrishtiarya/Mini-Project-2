# Mini-Project-2
# *Vaccination Data Analysis and Visualization*

*Objective:*
Analyze global vaccination data to understand trends in vaccination coverage, disease incidence, and effectiveness. Data will be cleaned, and stored in a SQL database. Power BI will be used to connect to the SQL database and create interactive dashboards that provide insights on vaccination strategies and their impact on disease control.

*Business Use Cases:*
Public Health Strategy:
Assess the effectiveness of vaccination programs in different regions and populations.
Prioritize areas with low vaccination coverage for targeted interventions.
Disease Prevention:
Identify diseases with high incidence rates despite vaccination efforts, suggesting vaccine inefficacies or areas for improvement.
Support policies on booster vaccines or new vaccine introductions.
Resource Allocation:
Determine regions with low vaccination coverage and plan targeted resource distribution to improve vaccination rates.
Forecast vaccine demand based on current trends for better supply chain management.
Global Health Policy:
Provide data-driven recommendations for vaccination policy formulation.
Support governments and health organizations with evidence on vaccine effectiveness.

*Approach:*

Data Cleaning.

Handle Missing Data: Impute missing values or remove incomplete records.

Normalize Units: Ensure consistency in units across datasets (e.g., percentage of coverage, number of reported cases).

Date Consistency: Format date fields uniformly across tables for easier analysis.
SQL Database Setup

Create Tables: Store the extracted and cleaned data into relational SQL tables (e.g., vaccination data, disease incidence data, antigen data).

Normalize Data: Structure the data into separate tables (e.g., vaccines, diseases, countries, years) to avoid redundancy and improve querying performance.

Data Integrity: Implement primary and foreign keys to ensure referential integrity.
Power BI Integration. 

Connect Power BI to SQL Database:
Use Power BI’s SQL connector to link to the SQL database and pull in the relevant tables for analysis.
Set up scheduled refreshes for updated data.
Data Visualization in Power BI

Create Interactive Dashboards:
Use Power BI to create dynamic and visually engaging reports with filters and slicers for users to explore the vaccination data.
Visualize vaccination rates, disease incidence, and antigen coverage over time and across regions.

Key Visualizations:
Geographical Heatmaps: Display vaccination coverage and disease incidence by region.
Trend Lines/Bar Charts: Show trends in vaccination coverage, disease rates, and effectiveness over multiple years.
Scatter Plots: Correlate vaccination coverage and disease incidence across different countries or regions.
KPI Indicators: Track progress toward vaccination goals and health targets.

Exploratory Data Analysis (EDA):
Analyze vaccination coverage, disease incidence trends, and regional disparities using statistical summaries and correlation analysis. Visualize insights with bar charts, heatmaps, and line graphs to identify patterns, highlight low-coverage areas, and assess the impact of vaccination on disease reduction.

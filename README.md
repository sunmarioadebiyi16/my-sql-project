COVID-19 Data Exploration

This project explores global COVID-19 data using SQL, focusing on case counts, death rates, and vaccination progress. It demonstrates a variety of SQL techniques for data analysis and prepares results for visualization.

📊 Features & Analysis

The SQL script includes:

Data exploration: Select key fields (location, cases, deaths, population).

Case vs. Deaths: Calculates the likelihood of death if infected.

Case vs. Population: Shows percentage of population infected.

Infection & Mortality Rankings: Countries and continents with the highest rates.

Global Trends: Aggregated totals and death percentages worldwide.

Vaccination Progress: Rolling calculations of vaccinated populations.

Reusable Views: Created for visualization in BI tools.

🛠️ Skills & Techniques Used

Joins

Common Table Expressions (CTEs)

Temporary Tables

Window Functions

Aggregate Functions

Data Type Conversion

View Creation

📂 Files

COVID Portfolio Project - Data Exploration.sql
Main SQL script containing queries, transformations, and view creation.

🚀 Getting Started

Import the SQL file into your SQL environment (SQL Server recommended).

Ensure you have the following tables available:

CovidDeaths

CovidVaccinations

Run queries step by step or execute the entire script.

Use the PercentPopulationVaccinated view for visualizations in Power BI, Tableau, or other BI tools.

📈 Example Insights

Probability of death if infected in different countries.

Infection rates relative to population size.

Vaccination rollout and its impact across continents.

🔮 Next Steps

Connect the output to a dashboard (Power BI, Tableau, etc.).

Automate data refreshes with scheduled jobs.

Expand analysis with demographic breakdowns.

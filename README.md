# A/B Test Results Dashboard (Tableau)

This repository showcases an interactive dashboard built in Tableau Public for the analysis of A/B test results. The dashboard allows for dynamic filtering by continent and date range.

---

## Live Interactive Dashboard

### [ Click here to view the interactive dashboard on Tableau Public]([https://public.tableau.com/views/CreateYourABTestingTool_17617488603990/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link])

---

##  Dashboard Preview

![Tableau Dashboard Preview 1](Tableau%201.png)
![Tableau Dashboard Preview 2](Tableau%202.png)

## 🎯 Project Goal

The main objective was to create a comprehensive Tableau dashboard to analyze the results of a marketing A/B test. The dashboard is designed to be filtered by continent and specific time intervals (the test period) to provide granular insights.

## 📋 Project Execution Steps

This project was built following these key steps:

1.  **Data Generation:** A sample dataset was generated to simulate the results of an A/B test, including session events, A/B group assignments, country/continent, date, conversions, and other relevant metrics.
2.  **SQL Aggregation:** An SQL query was written to pre-aggregate key metrics (sessions, users, conversion rate, average order value, etc.) grouped by test variant (A vs. B) and time.
3.  **Data Import:** The resulting aggregated CSV/file was imported into Tableau Public.
4.  **Dashboard Creation:** A Tableau visualization was built to compare Group A vs. B performance. The dashboard includes:
    * Time-series charts for key metrics.
    * A map visualization for continental performance.
    * Summary tables for key metrics.
5.  **Dynamic Filtering:** Interactive filters were added to the dashboard, allowing users to drill down by:
    * Continent
    * Date/Period (to isolate the active test period)
6.  **Publishing:** The final dashboard was published to Tableau Public.

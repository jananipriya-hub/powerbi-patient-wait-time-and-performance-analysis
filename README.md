# Patient Wait Time & Performance Analysis

## Project Overview
This project focuses on analyzing hospital efficiency and understanding what causes long patient wait times. Using an Emergency Room (ER) dataset, I built a dashboard to track how long patients spend in different stages of their visit—from registration to seeing a medical professional.

## Project Objective
The main goal was to find bottlenecks in the hospital's daily operations and see how factors like staff availability, time of day, and urgency levels affect total patient wait times and overall satisfaction.

## Tools I Used
* **Power BI** (For building the data model and creating visual dashboards)
* **Power Query** (For cleaning data, handling empty values, and changing data types)
* **DAX** (For creating calculated measures like average wait times and satisfaction trends)

## Dataset
The dataset contains operational records for multiple hospitals (including Springfield General, Northside Community, and Riverside Medical). It tracks patient IDs, visit dates, urgency levels, nurse-to-patient ratios, specialist availability, and a breakdown of time spent in registration, triage, and consultation.

## Data Cleaning
Before building the charts, I used Power Query to clean up the raw data:
* Fixed date formats and split the timestamps to get clean days of the week and times of day.
* Checked for missing values in critical columns like specialist availability.
* Standardized text columns like hospital names and regions for accurate filtering.

## Dashboard Features
* **Key KPI Cards:** Displays high-level summaries like Total Visits, Average Wait Times, and Count of Unique Patients.
* **Peak Time Heatmaps:** Matrix tables showing wait times broken down by days of the week and times of day to find the busiest hours.
* **Operational Charts:** Bar charts and line graphs comparing total wait times against hospital names, urgency levels, and patient outcomes.

## Insights & Recommendations
* **Peak Hour Bottlenecks:** Patient wait times spike significantly during specific times of day and evening shifts, showing a clear need for better staff scheduling during those hours.
* **Staffing Correlations:** Lower specialist availability and low nurse-to-patient ratios directly correlate with higher critical wait times. Hospital branches should adjust staff rotations based on these predictable weekday peaks to improve patient satisfaction.

## How to Use It
Download the `.pbix` file from this repository and open it in Power BI Desktop to interact with the filters.

## Author
Janani Priya N

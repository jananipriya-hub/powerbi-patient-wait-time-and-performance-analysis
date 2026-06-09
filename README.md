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

## Insights 
1. **High Volume and Bottlenecks at Specific Branches:** Riverside Medical Center and Northside Community Hospital show the highest volume of patient cases, causing major tracking bottlenecks compared to smaller branches like Springfield or Summit Health.
2. **Critical Wait Time Thresholds:** Patients classified under "Critical" urgency levels face a high volume of cases (over 1,740 records), stretching hospital resources thin during peak emergencies.
3. **Low Satisfaction Drivers:** The average patient satisfaction score sits relatively low at **2.77 out of 5.00**, which directly correlates with the long wait times seen in the operational heatmaps.
4. **Time of Day Variations:** Patient wait times and volume fluctuate significantly by shift, with clear spikes during the Afternoon and Evening blocks compared to Early Morning hours.
5. **Varying Patient Outcomes:** A significant portion of the total patient volume results in actual hospital admissions ("Admitted") rather than quick discharges, meaning bed availability directly delays the triage process.

## Recommendations
1. **Allocate Resources to High-Volume Branches:** Increase staffing, beds, and desk clerks specifically at Riverside Medical Center and Northside Community Hospital to handle their disproportionately high patient loads.
2. **Prioritize Critical Care Workflows:** Streamline the fast-track lane for the 1,740+ "Critical" status patients to reduce their average total wait time and improve emergency survival outcomes.
3. **Target the 2.77 Satisfaction Score:** Implement feedback collection at discharge to find out if the low 2.77 score is caused by staff behavior or simply long wait times in the lobby.
4. **Smooth Out Shift Transitions:** Deploy overlap shifts for nurses and specialists between afternoon and evening blocks to ensure patient processing doesn't stall during staff handovers.
5. **Optimize Bed Management for Admissions:** Since a large number of patients end up admitted, connect the emergency room dashboard to the main hospital ward tracking system to speed up bed assignments.
  
## How to Use It
Download the `.pbix` file from this repository and open it in Power BI Desktop to interact with the filters.

## Author
Janani Priya N

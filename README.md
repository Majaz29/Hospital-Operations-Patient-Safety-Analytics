# Hospital Operations & Patient Safety Analytics

## Project Overview
This project analyzes hospital operations data from 2020–2024 to understand the relationship between bed occupancy, staff responsiveness, and unassisted patient falls.

The goal was to identify operational patterns that may help hospitals monitor patient safety during periods of high bed occupancy.

## Key KPIs
- Average Licensed Bed Occupancy Rate
- Unassisted Fall Rate per 1,000 Patient Days
- Staff Responsiveness Score
- Staff Responsiveness Benchmark

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Power BI
- Jupyter Notebook

## Data Preparation
- Loaded and inspected the raw dataset
- Checked data types and dataset structure
- Checked for missing values
- Removed an unnecessary empty column
- Reviewed descriptive statistics and unusual observations
- Created Month and Year fields for trend analysis
- Exported the cleaned dataset for Power BI analysis

## Analysis Performed
- Exploratory Data Analysis (EDA)
- Monthly and yearly trend analysis
- Bed occupancy analysis
- Unassisted fall rate analysis
- Staff responsiveness analysis
- Correlation analysis
- Power BI dashboard development

## Key Findings
- Average bed occupancy was approximately **96.2%**.
- Average unassisted fall rate was **2.61 per 1,000 patient days**.
- Average staff responsiveness score was approximately **63.1**.
- Bed occupancy and fall rate had a **positive correlation of 0.70**, indicating that higher occupancy was associated with higher fall rates.
- Staff responsiveness and fall rate had a **negative correlation of -0.79**, indicating that better staff responsiveness was strongly associated with lower fall rates.
- Bed occupancy and staff responsiveness had a **negative correlation of -0.37**.
- Bed occupancy increased from approximately **94.6% in 2020 to 97.2% in 2023**, before slightly decreasing in 2024.
- Fall rates increased through 2022–2023 and improved in 2024.

## Dashboard
An interactive Power BI dashboard was developed to monitor:
- Bed occupancy
- Unassisted fall rates
- Staff responsiveness
- Yearly staff responsiveness benchmarks
- Relationship between bed occupancy and patient falls
- <img width="1022" height="808" alt="Hospital_Dashboard_screenshort" src="https://github.com/user-attachments/assets/6c9901a4-f735-4770-b69f-c0b47ba59921" />


## Recommendations
- Closely monitor staff responsiveness during periods of high bed occupancy.
- Strengthen patient monitoring and fall-prevention practices during higher-risk periods.
- Review staffing and resource allocation when occupancy is high.
- Include staffing levels, patient acuity, and unit-level data in future analysis to better understand the drivers of patient falls.

## Conclusion
The analysis found meaningful relationships between hospital occupancy, staff responsiveness, and patient falls. Higher bed occupancy was associated with higher fall rates, while better staff responsiveness was associated with fewer falls.

These findings represent associations and do not establish causation.

# Maternal-Health-Risk-Analysis
![](maternal_health.jpg)

##	introduction

Maternal health is one of the most critical aspects of public health. Pregnancy and childbirth complications account for a significant number of deaths globally, especially in developing regions. Identifying health risk factors early can prevent severe complications for both mother and child.
This project analyzes a **Maternal Health dataset** with the goal of uncovering key health indicators associated with maternal risk levels. Using Excel and Power Query, the dataset was cleaned, transformed, and analyzed to extract insights. Dashboards were developed to summarize findings, and recommendations were provided for improving maternal health monitoring.

##  Objectives
- Clean and prepare the dataset for analysis.
- Categorize vital health indicators (Blood Pressure, Blood Sugar, Heart Rate, and Temperature) into clinical ranges.
- Examine the relationship between maternal risk levels and health indicators.
- Build dashboards to communicate results effectively.
- Provide recommendations that can guide maternal healthcare decisions.
##  Dataset overview
- Rows & Columns: 453 rows  & 7 columns
#### Original Features:
![](https://github.com/christopherstanleyobinna-rgb/Maternal-Health-Risk-Analysis/blob/main/Orignal_%20dataset.jpg)
- Age
- Systolic Blood Pressure (SBP)
- Diastolic Blood Pressure (DBP)
- Blood Sugar (BS)
- Heart Rate
- Temperature
- Risk Level
![](Orignal_dataset.jpg)

#### New Features Created:
- Age group
- SBP Category (Low, Normal, High)
- DBP Category (Low, Normal, High)
- Blood Sugar Category (Low, Normal, High)
- Temperature Category (Normal, Elevated, Fever, High Fever)
- Heart Rate Category (Low, Normal, High).
  This expanded the dataset from 7 columns to 13 columns for deeper analysis.
  
## Tools and techniques
- Power Query Editor → Data cleaning, removing duplicates, handling missing values.
- Excel Functions & Formulas → IF, COUNTIFS, VLOOKUP, nested formulas for categorization.
- Pivot Tables → Summarization of risk levels across health indicators.
- Excel Dashboards → Data visualization and interactive reporting
  
## Data Preparation
![(https://raw.githubusercontent.com/username/repo/main/images/overview_Dashboard.jpg)](https://github.com/christopherstanleyobinna-rgb/Maternal-Health-Risk-Analysis/blob/main/Data_preparation.jpg)
#### Steps taken during preparation:
- Cleaned column headers and standardized formats.
- Removed duplicate records.
- Handled missing values appropriately.
- Created categorical columns for better segmentation of vital signs.
- Verified ranges to ensure accuracy of health classifications.
 ## Analysis and Dashboard
#### Dashboard 1 – Maternal Risk Overview
![(https://raw.githubusercontent.com/username/repo/main/images/overview_Dashboard.jpg)](https://github.com/christopherstanleyobinna-rgb/Maternal-Health-Risk-Analysis/blob/main/overview%20_dashboard.jpg)
- Distribution of mothers across risk levels (Low, Mid, High).
- Age group comparison against risk levels.
- Proportion of high risk mothers with High or Very High Blood sugar.
#### Dashboard 2 – Health Indicators Analysis
![(https://raw.githubusercontent.com/username/repo/main/images/overview_Dashboard.jpg)](https://github.com/christopherstanleyobinna-rgb/Maternal-Health-Risk-Analysis/blob/main/key_indicators.jpg)
- Classification of Systolic & Diastolic BP into Low, Normal, High.
- Categorization of Blood Sugar into Low, Normal, High.
- Distribution of Temperature (Normal, Elevated, Fever, High Fever).
- Heart Rate categorization.
## Key insight
![](https://github.com/christopherstanleyobinna-rgb/Maternal-Health-Risk-Analysis/blob/main/Analysis.jpg)
- Blood Pressure: Most mothers had normal Diastolic BP, but 37% showed high systolic BP, a major contributor to high maternal risk.
- Temperature: temperature readings among high risk mothers were mostly normal (65.18%) but around 32% of high risk mothers has fever or high fever which suggests it play a significant but not dominant role in maternal health risk
- Blood Sugar: A combined 100 of high risk mothers has elevated blood sugar (43 prediabetes and 57 are at Diabetes level), highlighting hyperglycemia as a strong risk factor in maternal health complications
- Heart Rate: Surprisingly, all 112 high-risk mothers recorded normal heart rates, suggesting HR alone may not be a strong indicator of risk.
  ## Recommendations
  ![](https://github.com/christopherstanleyobinna-rgb/Maternal-Health-Risk-Analysis/blob/main/maternal%20image.jpg)
- Clinical Monitoring: Continuous tracking of blood pressure and temperature for expectant mothers.
- Preventive Care: Health education programs on nutrition and lifestyle to reduce risk factors.
- Early Intervention: Regular maternal checkups to detect abnormal BP, BS, or temperature early.
- Healthcare Systems: Strengthen maternal health record-keeping to improve monitoring and decision-making.
## Conclusion
This project demonstrates how Excel and Power Query can be applied to real-world health datasets to uncover meaningful insights. By expanding and categorizing data, we identified key risk indicators such as fever and hypertension. With proper monitoring, education, and healthcare interventions, maternal risks can be reduced significantly.

The project not only highlights the importance of data-driven decisions in healthcare but also showcases the role of data analysis tools in delivering actionable insights.



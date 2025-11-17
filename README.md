# Emergency-Response-Analysis-
Data analysis and dashboard project examining emergency response delays and access to care using real-world structured dataset.

Data: [Emergency_Response_and_Access_to_Care_Dataset.xlsx](https://github.com/user-attachments/files/23587208/Emergency_Response_and_Access_to_Care_Dataset.xlsx)

Images: ![1002090186](https://github.com/user-attachments/assets/dd2ee786-bfca-49cf-8c01-e82b284a69f2)
![1002090185](https://github.com/user-attachments/assets/1d20bb6a-7eef-478c-8dcc-a22be0a92eb8)

Emergency Response and Access to Care Analysis

Overview:

This project explores delays in ambulance response, access to hospital care, and the socioeconomic factors influencing emergency outcomes.
Using structured incident data, I analysed how time, distance, overcrowding, population patterns and income levels affect survival during medical emergencies.

The project includes:
Exploratory data analysis
Data cleaning and transformation
Measures and DAX calculations
Multi-page Power BI dashboard
Insights and recommendations

Dashboard Structure

🔹 Page 1: Emergency Response and Access to Care

Key Metrics Displayed:

Total incidents
Average ambulance response time
Mortality rate
Average distance to nearest hospital
Response delay categories
Average response time and distance by area type
Average response time by region and area
Hospital overcrowding and patient outcomes


🔹 Page 2: Socioeconomic Analysis

Metrics Displayed:

Age group distribution by gender
Mortality rate by income level
Number of deaths by region and area
Population density vs response time (scatter analysis)
Mortality rate by age


Data Transformations

Converted Reported Time and Arrival Time to datetime format.
Created Actual Response Time column, using Arrival – Reported.

Created measures for:
Total deaths
Mortality rate (%)


Added Region, gender and Area Type as slicers for improved filtering.



Visualisations Used

Bar charts

Line chart

Stacked charts

Scatter plots

Cards/KPIs


Designed using theme colours:
#427AA1, #064789, #EBF2FA


Key Insights

•Rural areas face higher response times due to long travel distance.
•Overcrowded hospitals show poorer patient outcomes.
•Mortality is higher among lower-income patients.
•Younger and older age groups present different vulnerability patterns.
•Regions differ in accessibility and emergency efficiency.




Recommendations

•Improve ambulance distribution in high-delay regions.
•Expand emergency units in consistently overcrowded hospitals.
•Reduce travel distance through decentralised health centres.
•Integrate traffic and mapping technology into ambulance routing.
•Implement socioeconomic support programs for vulnerable groups.

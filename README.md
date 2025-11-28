# Healthcare-Efficiency-Analysis-Hip-Replacement-Surgery-in-New-York-State-for-2016-
This project analyzes New York State hospital discharge data (2016) for elective hip replacement surgeries to uncover opportunities for improving operational efficiency. Using Power Query for data cleaning and Power BI for modeling and visualization, the analysis focuses on key metrics such as Length of Stay (LOS) and Cost per Discharge.

## Executive Summary: 
Healthstat, a fictitious consulting firm, needs to analyze statewide hospital discharge data from New York (2016) to identify opportunities to improve operational efficiency. The analysis focuses on elective hip replacement surgeries and aims to uncover factors affecting Length of Stay (LOS) and Cost per Discharge, highlight high-cost or high-LOS hospitals, and support data-driven decision-making. 

## Business Problem: 
Operational efficiency is crucial in healthcare because it impacts patient throughput, total operational cost, and resource utilization. 
Length of Stay (LOS) is a key efficiency metric—shorter LOS reduces cost and increases hospital capacity. 

## The main business questions were: 
1. Which hospitals have unusually high LOS or cost per discharge? 
2. Who are the top outliers? 
3. What factors influence LOS and cost the most? 

## Results: 
### General Insights: 
1. 151 hospitals performed hip replacements.
2. 26,000 total discharges.
3. Overall average LOS = 2.6 days.

### Efficiency Findings:
1. Females had higher average LOS (2.7 days) vs. males (2.5 days).

![Image Alt](https://github.com/mohmadahmedabdelwahed/Healthcare-Efficiency-Analysis-Hip-Replacement-Surgery-in-New-York-State-for-2016-/blob/7d1b4ed76a588a2dff9e94f6ac9b2ce34588a24c/Screenshots/1.%20los%20by%20gender.png)

2. NYC hospitals showed the highest average LOS (2.8) and average cost levels (26k).

![Image Alt](https://github.com/mohmadahmedabdelwahed/Healthcare-Efficiency-Analysis-Hip-Replacement-Surgery-in-New-York-State-for-2016-/blob/70d453586af1e61bcef865d35120fff839a817d2/Screenshots/2.%20Average%20Cost%20per%20discharge%20by%20hospital%20name.png)

![Image Alt](https://github.com/mohmadahmedabdelwahed/Healthcare-Efficiency-Analysis-Hip-Replacement-Surgery-in-New-York-State-for-2016-/blob/70d453586af1e61bcef865d35120fff839a817d2/Screenshots/3.%20Average%20LOS%20by%20service%20area.png)

3. Syosset hospital showed the highest average LOS among the top 15 hospitals by total discharges with an average LOS of 3.2 days and a total discharge of 441.

![Image Alt](https://github.com/mohmadahmedabdelwahed/Healthcare-Efficiency-Analysis-Hip-Replacement-Surgery-in-New-York-State-for-2016-/blob/70d453586af1e61bcef865d35120fff839a817d2/Screenshots/4.%20LOS%20%26%20total%20discharge%20by%20hospital%20name.png)


### Cost & LOS Outliers: 
5 hospitals in NYC exceeded the 90th percentile in cost per discharge. 

![Image Alt](https://github.com/mohmadahmedabdelwahed/Healthcare-Efficiency-Analysis-Hip-Replacement-Surgery-in-New-York-State-for-2016-/blob/70d453586af1e61bcef865d35120fff839a817d2/Screenshots/6.%20los%20%26%20cost%20per%20dischrage.png)

### Root Causes Identified: 
1. When the severity of illness is extreme, it significantly increases LOS and cost (even though it represents only 2.38% of cases).
2. When the risk of mortality is extreme, it increases LOS and cost.
3. Hospital location (NYC) is associated with higher costs and LOS.

## Business Recommendations: 
1. Investigate high-cost outliers to understand operational inefficiencies.
2. Focus on NYC hospitals, which consistently show higher LOS and costs. 




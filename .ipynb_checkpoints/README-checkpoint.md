# Phase 1 Project

This project analyzes historical aviation accident data to provide data-driven insights into safety patterns across various aspects of the aviation industry. For investors, these insights offer valuable context on the relative safety of different types of aircraft, regions, and operational conditions—factors that contribute to identifying safer investment opportunities in aviation.

## Business Understanding
The primary audience for this analysis is investors seeking to understand the aviation industry's safety landscape to make informed investment decisions. Key questions for investors may include:

* Which aircraft types demonstrate the highest and lowest rates of safety incidents?
* What types of flights have the highest and lowest risk (passenger, private, cargo ect...)? 
* How does location impact the risk and what are areas that are safest to fly? 

## Data Understanding and Analysis
### Source of Data
This project analyzes aviation accidents from National Transportation Safety Board from 1962 to 2023 for private and commercial flights by location, airplane model and accident severity. These accidents range in severity from fatal to uninjured passengers, the goal is to assess risk by type, injury/fatality rate, make and flight type to provide recommendations for the business on the aircraft with the lowest risk and safest investment.

### Description of Data
The dataset includes information on:

* Date and Location: Details on when and where accidents occurred, highlighting high-risk regions.
* Aircraft Type and Operator: Information on aircraft models and operators involved in incidents.
* Weather Conditions: Environmental factors, which often play a role in accident likelihood.
* Injury Severity: Information pertaining to severity of injury (uninured, minor, serious and fatal) and how many of each occured

## Key Visualizations
Average Fatality Rate by Purpose of Flight: This chart shows the average fatality rate by purpose of flight. Ariel Application had the lowest fatality rate. 
![alt text](images/Screenshot 2024-10-27 at 11.04.01 PM.png)
Average Fatality Rate by Aircraft Make: This chart shows which Aircraft make has the lowest fatality rate with samples of each instance over 30 to assure statistical signifigance. 
![alt text](images/Screenshot 2024-10-27 at 11.04.26 PM.png)
Average Fatality Rate by Location: The fatality rate by location shows which states/territories have a fatality rate of under 1. If the states/territories was over 1 then we recommend that they do not fly in those areas. 
![alt text](images/Screenshot 2024-10-27 at 11.04.41 ßPM.png)

Tableau Dashboard Link: https://public.tableau.com/app/profile/isaac.buck/viz/Project1Workbook_17299782724070/Project1Dashboard?publish=yes


## Conclusion
Based on the analysis of these three parameters, my recommendation to investors on the safest investments is for Ariel Applications using the GRUMMAN ACFT ENG COR-SCHWEIZER aircraft and any location in the United States excluding Virgin Islands, Atlantic Ocean, Gult of Mexico, Washington D.C. and Guam. 

* Purpose of Flight: Aerial Applications
    * Reason: lowest average fatality rate of any flight type at %13.0870 with 4712 recorded instances
* Aircraft Make: GRUMMAN ACFT ENG COR-SCHWEIZER
    * Reason: lowest average fatality rate of any make with %1.7241 rate per accident. 1 fatality out of 58 aviation incidents.
* State/Territory Location (US Only): Any location excluding Virgin Islands, Atlantic Ocean, Gult of Mexico, Washington D.C. and Guam
    * Reason: The 5 locations listed above have a mean of over 1.00 meaning death is likely to occur in an aviation accident.



+++
title = "Assessing the Impact of Opioid Prescription Drug Policies on Mortality Trends"
date = 2023-12-15
+++

#### Collaborators - Jiayi Zhou, Jiechen Li, Ayush Gupta, Divya Sharma 
Here is the link: [Project Link](https://github.com/JiayiZhou36/opioid-2023-group-8-final-opioid).

## Data
-  [Opioid prescribing rates](https://www.washingtonpost.com/national/2019/07/18/how-download-use-dea-pain-pills-database/?arc404=true) from DEA's Automatioin of Reports and Consolidated Orders System (ARCOS) detailing all transactional data of controlled substances sales by drug companies on a county level from 2006-2019
-  [Drug overdose mortality](https://www.dropbox.com/s/kad4dwebr88l3ud/US_VitalStatistics.zip?dl=0) counts from US National Vital Statistics System compressed mortality files for county-years 2003-2015
-  [County-level populations](https://wonder.cdc.gov/bridged-race-population.html) from CDC for rate denominators


## Methods

-  *Pre-post analysis*: Compare trends before and after policy changes
-  *Difference-in-difference models*: Contrast changes against demographically similar control states lacking interventions to isolate impact
-  Address missing mortality data using *imputation* process leveraging data properties to generate estimates suitable for advanced econometric analyses

## Outcomes

-  Opioid prescribing rates per capita
-  Drug overdose mortality rates

## Key Questions

-  How do implementations of prescription regulations affect the volume of opioids prescribed at the county level?
-  What is the impact of stricter opioid drug monitoring policies on overdose mortality rates?

## Test and Control States
The three test states examined in this analysis targeting prescriber practices are Florida, Texas, and Washington. Florida implemented stricter regulations and oversight on pain clinics along with enforcement crackdowns beginning in 2010. Texas expanded access controls for prescription drug monitoring in 2007 to reduce diversion and doctor shopping. Washington augmented requirements for frequent utilization checks and guidelines adherence in 2011 to impact prescribing decisions.

To account for underlying secular trends, neighboring states with highly aligned demographic, socioeconomic, and cultural profiles but lacking similar interventions in the given time period will provide control comparisons. Namely, these are Georgia, Alabama, and Tennessee for Florida policies; Oklahoma, Arkansas, and Louisiana for the Texas case; and Oregon and Idaho for Washington's regulations. The difference-in-difference design will contrast changes in outcomes in these aptly matched triplets against their test state to isolate the association between tightened restrictions and changes in opioid prescribing and mortality post-reform.

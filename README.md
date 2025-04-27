# Group 1 MIST 4610 Group Project 2
# Team Name:
21479 Group 1

# Team Members: 
1) Brett Bailey [@brettbailey04](https://github.com/brettbailey04)
2) Brooke Credendino [@BrookeCredendino](https://github.com/BrookeCredendino)
3) Mohammed Omar [@momo103103](https://github.com/momo103103)
4) Evan Langley [@elangley424](https://github.com/elangley424)
5) Soham Gupta [@GHSohamGupta](https://github.com/GHSohamGupta)
6) Charlie Jones [@jonescharlie](https://github.com/jonescharlie)

# Topic: 
COVID-19 Mortality By Age and Sex

# Context & Motivation: 
COVID‑19 has been one of the deadliest pandemics in modern history, disproportionately impacting different demographic group

# Scope & Granularity: 
Nationwide and state‑level counts, broken out by sex (“Male,” “Female,” “All Sexes”) and age groups (Under 1, 0–17, …, 85+)

# Analysis Objectives:
Examine, identify, and understand demographic and state-wide patterns in COVID‑19 mortality

# Why It Matters:
Informs targeted public‑health interventions and resource allocation
Highlights equity gaps and helps tailor future pandemic responses

# Source:
Publisher: Centers for Disease Control and Prevention (CDC) 

Maintainer: National Center for Health Statistics (NCHS)

URL Access:  https://data.cdc.gov/NCHS/Provisional-COVID-19-Deaths-by-Sex-and-Age/9bhg-hcku

Last Updated: September 27, 2023 (the dataset is now static)

# Data:
A. Temporal & Aggregation Fields: 

Data As Of (Date): Date the extract was published (e.g., “09/27/2023”).

Start Date (Date): Beginning of the reporting window (e.g., “01/01/2020”).

End Date (Date): End of the reporting window (e.g., “09/23/2023”).

Group (String): Aggregation level—one of:

By Total (cumulative over full period)

By Year (annual totals) - Calendar year when Group = “By Year” or “By Month”; NaN otherwise.

By Month (monthly totals) -  Month number (1–12) when Group = “By Month”; NaN otherwise.



B. Demographic & Geographic Fields: 

State (String (Geographical Role: State/Province)): Jurisdiction where death occurred (50 states + DC, Puerto Rico, and “United States” for national totals).

Sex (String): “Male”, “Female”, or “All Sexes”.

Age Group (String): Predefined age bins, e.g.:

“Under 1 year”

“0–17 years”

“18–29 years”

…

“75–84 years”

“85+ years”

“All Ages”



C. Mortality Measures (all Number(whole)): 

Each numeric column shows the provisional count of deaths for the specified category and grouping:

COVID‑19 Deaths: Deaths with COVID‑19 as an underlying or contributing cause

Total Deaths: All‑cause mortality

Pneumonia Deaths: Deaths from pneumonia (excluding influenza and COVID‑19)

Pneumonia and COVID‑19 Deaths: Deaths where both pneumonia and COVID‑19 were involved

Influenza Deaths: Deaths from influenza

Pneumonia, Influenza, or COVID‑19 Deaths: Combined deaths from any of these three causes


# Questions:
# Q1: How did COVID-19 death rates vary across difference age groups within separate states?

# Q1 Choice: 

We chose this question as a sort of a baseline to further our understanding of what trends really existed between mortality and demographics such as age and gender. This baseline served to identify basic causal relationships between existing statisitics in the various states across the nation and develop a better fundametal understanding of the situation that presented itself during COVID-19 for us to build onto for our following question which would highlight a more analytical and deeper understanding of the discrepencies brought about in terms of mortality during the pandemic.

# Q1 Data Manipulation
N/A

# Q1 Data Model:

<img width="896" alt="Screenshot 2025-04-27 at 2 47 33 PM" src="https://github.com/user-attachments/assets/e5be3037-972b-4a00-bb4a-402275a0496d" />

<img width="568" alt="Screenshot 2025-04-27 at 2 37 07 PM" src="https://github.com/user-attachments/assets/e0c05a11-8976-4d41-b779-26e4a3ba8161" />

<img width="755" alt="Screenshot 2025-04-27 at 2 37 29 PM" src="https://github.com/user-attachments/assets/458391d4-ef68-48f9-89dd-8a5ff4791d83" />


# Q1 Analysis:
1) Age Based Mortality Correlation Present
   
A) Varies in steepness per state

B) Strain on healthcare systems with high elderly population (eg. Florida and California)

C) Middle age clicking point

D) Majority of deaths are 50+

2) Population Density Driven Mortality Discrepancies
   
A) Higher State Population = Higher Mortality #s

B) Lower State Population = Lower Mortality #s


# Q1 Importance:

1.1) Vulnerability Patterns

A) State Specific Issues

B) Negligence

1.2) Age Based Trends

A) Elderly

B) Working Class

1.3) Population To COVID-19 Mortality Correlation

A) High Pop. -> Higher Mortality

B) Low Pop. -> Lower Mortality


2.1) Local Resource Planning

A) State-Level Policy

B) Quarantining

C) Vaccine Mandates

2.2) Appropriate Hospital Equipment Allocation

A) Ventilators

B) Staffing 

C) ICU Beds


3.1) Future Forecasting

A) Critical States

B) Dedicated Support

C) Structured Response

D) Effective Mandates

3.2) Critical Demographics

A) Localized Healthcare

B) Specified Guidelines




# Q2: Why did the male‑to‑female disparity in monthly COVID‑19 death counts for the 50–64 age group reach its peak earlier and at a higher magnitude in Southern states (e.g., Florida, Texas, Georgia) than in Pacific Coast states (e.g., California, Oregon, Washington) during various phases throughout 2020–2023?

# Q2 Choice: 

We chose this question primarily due to the fact that it would give us insigh as to why the 50-64 year age group was the clicking point in mortality. Most deaths were found in this group and we wanted to look deeper into what factors played into it. We already came into the question knowing that this was a immune succetible group and that it was still considered part of the working class. We chose the Southern and Coastal states as they were two distinct groups in terms of political ideology and overall response to the pandemic. We believed that by asking this question and utilizing the data we could confirm our prior insights and build upon what really citnributed to the accelerated mortality especially among men during various stages of the pandemic.

# Q2 Data Manipulation:

<img width="944" alt="Screenshot 2025-04-27 at 2 35 22 PM" src="https://github.com/user-attachments/assets/b82c1483-ae8d-4c8f-a7f0-c0983a6fa476" />

# Q2 Data Model:

<img width="771" alt="Screenshot 2025-04-27 at 2 36 02 PM" src="https://github.com/user-attachments/assets/06fb38b1-cbf6-4228-950d-f23c4430af24" />

<img width="772" alt="Screenshot 2025-04-27 at 2 36 08 PM" src="https://github.com/user-attachments/assets/dbcc94ee-40cc-4617-ae2a-e8c85f84217c" />

# Q2 Analysis:
1) Spikes of Gender Oriented Mortality Discrepancies

A) 3 Waves of Excess Male Deaths (Above Women Death Counts)

B) Original Variant (Winter 2020-2021)

C) Delta Variant (Summer 2021)

D) Omicron and Other Onward Variants (Late 2022)

E) Middle aged working class men the most impacted

F) Adoption of vaccines dulled COVID-19 death disparities (Mid 2021)

2) Pacific V.S Southern Spike Timing and Magnitude Differences

A) Southern states spike first and with higher intensity

B) Premature easing of southern state restrictions

C) Slower southern state adoption of vaccines



# Q2 Importance:

1.1) Underlying Factors

A) Predisposed Demographics

B) Working Class

C) Middle Aged

D) Socially active

1.2) State Level Policy

A) Delayed and Eased restrictions

B) Vaccine hesitancy


2.1) Optimize Care Outreach

A) Vaccination Efforts

B) Standardized

C) Prompt

2.2) Policy Guidance

A) Social Distancing

B) Quarantine Guidelines

C) Mask mandates


3.1) Future Prevention

A) Data driven strategies

B) Rapid and timed intervention

C) Pre-Protection of “at-risk” demographics

# Packaged Workbooks

Q1: 
https://github.com/BrookeCredendino/Group-1-Project-2/blob/main/COVID%20work%20book.twb

Q2: 
https://github.com/BrookeCredendino/Group-1-Project-2/blob/main/COVID-19GenderDisparity.twbx

# Sources:

NIH.gov - https://pmc.ncbi.nlm.nih.gov/articles/PMC9698608/ 

CDC.gov - https://covid.cdc.gov/covid-data-tracker/#variant-proportions

Census.gov - https://www.census.gov/data/tables/time-series/demo/popest/2020s-state-total.html

Independent Living in California - https://conciergecareadvisors.com/independent-living-california/

Nursing Home Outbreaks (2020) - https://www.pbs.org/newshour/health/nursing-home-outbreaks

Dataset - https://data.cdc.gov/NCHS/Provisional-COVID-19-Deaths-by-Sex-and-Age/9bhg-hcku






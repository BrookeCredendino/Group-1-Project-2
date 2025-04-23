# Group-1-Project-2

COVID-19 Deaths By Sex and Age

Group 1: Brett, Brooke, Evan, Mohammed, Soham

Context & Motivation: COVID‑19 has been one of the deadliest pandemics in modern history, disproportionately impacting different demographic group
Scope & Granularity: Nationwide and state‑level counts, broken out by sex (“Male,” “Female,” “All Sexes”) and age groups (Under 1, 0–17, …, 85+)
Analysis Objectives:
Examine, identify, and understand demographic and state-wide patterns in COVID‑19 mortality
Why It Matters:
Informs targeted public‑health interventions and resource allocation
Highlights equity gaps and helps tailor future pandemic responses

Publisher: Centers for Disease Control and Prevention (CDC)
Maintainer: National Center for Health Statistics (NCHS)
URL Access:  https://data.cdc.gov/NCHS/Provisional-COVID-19-Deaths-by-Sex-and-Age/9bhg-hcku
Last Updated: September 27, 2023 (the dataset is now static)

Data:
A. Temporal & Aggregation Fields
Data As Of (Date): Date the extract was published (e.g., “09/27/2023”).


Start Date (Date): Beginning of the reporting window (e.g., “01/01/2020”).


End Date (Date): End of the reporting window (e.g., “09/23/2023”).


Group (String): Aggregation level—one of:


By Total (cumulative over full period)


By Year (annual totals) - Calendar year when Group = “By Year” or “By Month”; NaN otherwise.


By Month (monthly totals) -  Month number (1–12) when Group = “By Month”; NaN otherwise.

B. Demographic & Geographic Fields
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

C. Mortality Measures (all Number(whole))
Each numeric column shows the provisional count of deaths for the specified category and grouping:

COVID‑19 Deaths: Deaths with COVID‑19 as an underlying or contributing cause

Total Deaths: All‑cause mortality

Pneumonia Deaths: Deaths from pneumonia (excluding influenza and COVID‑19)

Pneumonia and COVID‑19 Deaths: Deaths where both pneumonia and COVID‑19 were involved

Influenza Deaths: Deaths from influenza

Pneumonia, Influenza, or COVID‑19 Deaths: Combined deaths from any of these three causes

Questions:

Q1: How did COVID-19 death rates vary across difference age groups within separate states?

#HCDE410
Files for HCDE410 - Assignment A1

Adapted from # cdsw-2020 https://wiki.communitydata.science/Seattle_open_data


# A1 — Working with Open Data

**Dataset:** Burke-Gilman Trail counter north of NE 70th St
**Source:** https://data.seattle.gov/Transportation/Burke-Gilman-Trail-north-of-NE-70th-St-Bicycle-Cou/2z5v-ecg8/about_data  (pulled 2026-10-12)
**License / terms of use:** Public Domain, as listed in the dataset's metadata on data.seattle.gov (attribution: City of Seattle; dataset owner: Zuniga, Rafael). 

## Questions I asked
- Q1: Which hour is the trail busiest and quietest? (Busiest 5 pm, quietest 2 am.)
- Q2: Do cyclists and pedestrians use the trail at different times of day? (Yes: bikes peak at 8 am and 5 pm, pedestrians at 9 am.)
- Q3: Is there evidence of commuting? (Yes for bikes on weekdays, not for pedestrians.)
- Q4: Are mornings and evenings mostly opposite directions? (Yes for bikes: north in the morning, south in the evening.)

## How to re-run
Open `A1.ipynb` and run all cells (needs `requests`, `pandas`, `matplotlib`).

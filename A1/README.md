#HCDE410
Files for HCDE410 - Assignment A1

Adapted from # cdsw-2020 https://wiki.communitydata.science/Seattle_open_data

```
# A1 — Working with Open Data

**Dataset:** Burke-Gilman Trail counter north of NE 70th St
**Source:** https://data.seattle.gov/Transportation/.../2z5v-ecg8  (pulled 2026-10-12)
**License / terms of use:** <find it on the dataset's page and note it here>

## Questions I asked
- I used Claude for starter code. I ran every cell to produce the plots and tables, which I used my own judgment to answer the questions. What I asked:
- I asked how I could get the precise numbers from a graph. Claude suggested printing a table of values, which I added to my Q1–Q4 cells so my answers cite exact values.
- I asked how to add titles and axis labels to a plot, and I added them to every plot.
- The original code Claude proposed only included bikes, so I pushed back as the assignment doesn't limit Q4 to bikes. I asked Claude for its rationale and then decided to include pedestrians. The code now plots both bikes and pedestrians in each direction.


## How to re-run
Open `A1.ipynb` and run all cells (needs `requests`, `pandas`, `matplotlib`).
```
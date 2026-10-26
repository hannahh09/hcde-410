Exercises and assignments for HCDE410: Human Data Interaction. Everything here is a work in progress unless otherwise noted :)

#HCDE 410 A2 - Exploring sources of bias in data
**Dataset:** Wikipedia Talk Corpus (crowdworker demographics and toxicity labels), the training data behind Google Jigsaw's Perspective API
**Source:** 
Figshare:
https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Toxicity/4563973
https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Aggression/4267550
https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Personal_Attacks/4054689
(downloaded 2026-10-24)
**License / terms of use:** CC0 public domain dedication, as listed on the dataset’s Figshare page (attribution: Wulczyn, Ellery; Thain, Nithum; Dixon, Lucas (2016))

## Questions I asked
- Q1–Q4: Who are the workers? (63.6% male; 81.5% English not first language; 86.3% aged 18–45; 39.8% hold a bachelor's degree, the largest group.)
- Q5: Is data missing? (Yes: `age_group` is blank for 112 of 5,781 workers, 1.94%.)
- Q6: What if duplicates were kept? (7,971 workers instead of 5,781; percentages change by 0.7 points or less.)
- Q7–Q8: How do the workers compare with US internet users, and what problems could this training data cause? (Workers skew male, young, and non-native English; see notebook.)
- Q9–Q12: Who made the toxicity labels? (83.5% of labelers have demographics; among labels with demographics, 66.0% are from men and 82.6% from non-native English speakers.)

## How to re-run
Put the Figshare data files in `wikipedia_datasets/` next to `hcde410-a2.ipynb` and run all cells (needs `pandas`, `matplotlib`).
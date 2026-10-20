# Corporate Wellness: Sleep & Stress Index

An interactive Power BI dashboard that explores how sleep, stress, and lifestyle relate to each other across 374 people, 11 occupations, and 3 BMI categories.

![Dashboard overview](screenshots/dashboard_overview.png)

## Project Goal

To help a corporate wellness team see which groups of employees have sleep disorders and high stress, so they can decide where to focus support. Slicers for gender, BMI category, and occupation let users drill into specific groups.

## Dashboard Contents

- **KPI cards:** sleep duration, stress level, number of people, and heart rate
- **Sleep disorders by occupation:** a bar chart of people per occupation, split by disorder type
- **Sleep disorder breakdown:** a donut chart of Insomnia, Sleep Apnea, and None
- **Quality of sleep by BMI category:** a column chart comparing BMI groups
- **Stress level vs. % with sleep disorder:** a column chart showing the disorder rate at each stress level

## Key Insights

- **41% of people (155 of 374) have a sleep disorder:** 78 with Sleep Apnea (21%) and 77 with Insomnia (21%).
- **Occupation matters a lot.** Among the larger groups, Salespeople (94%), Nurses (88%), and Teachers (78%) have the highest disorder rates, while Engineers (10%), Doctors (10%), and Lawyers (11%) have the lowest.
- **The disorder type differs by job.** Nurses mostly have Sleep Apnea (61 of 73), while Salespeople (29 of 32) and Teachers (27 of 40) mostly have Insomnia.
- **Weight is strongly linked to disorders.** 87% of Overweight and 100% of Obese people have a disorder, against 7% of Normal-weight people.
- **Sleep quality follows the same pattern.** Average sleep quality is 7.6 for Normal, 6.9 for Overweight, and 6.4 for Obese.
- **Women have a higher disorder rate than men:** 56% (103 of 185) against 28% (52 of 189).
- **The stress link is not a straight line.** The disorder rate is lowest at stress level 6 (7%) and peaks at level 7 (94%).
- **Averages across everyone:** 7.1 hours of sleep, stress level 5.4, and a heart rate of 70 bpm.

## Tools Used

- **Power BI**: data model, DAX measures (Total People, People With Disorder, % With Disorder), and visuals
- **Figma**: dashboard layout and design [delete if you didn't use it for this one]
- [Excel / SQL / Python, if you used them for cleaning]

## Data

- **Source Kaggle:** Sleep_health_and_lifestyle_dataset
- **Size:** 374 rows, 14 columns (age, gender, occupation, sleep duration, sleep quality, physical activity, stress level, BMI category, heart rate, daily steps, sleep disorder, blood pressure)
- **Cleaning steps:** [e.g. split blood pressure into Systolic and Diastolic columns]
- **Limitation:** Some occupations have very few people (Manager has 1, Sales Representative 2, Scientist and Software Engineer 4 each), so their percentages shouldn't be over-interpreted.

## How to Open the Dashboard

1. Download `sleep_analysis.pbix` from this repository.
2. Open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows only).

## Author

Amira Ibrahim
Aspiring Data Analyst | Assiut, Egypt

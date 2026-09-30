# Marriage and Divorce in America: What Has Changed, and Who Divorces?

DATA 201 capstone project, LaGuardia Community College, October 2026.
By Susana Fernandez Rivera.

## Research questions

1. How have marriage and divorce rates changed over time, and how does New York compare to the rest of the country?
2. Was 2019 different from the trend?
3. What do divorced people have in common?

## Data

- **CDC / National Center for Health Statistics** — U.S. marriage and divorce rates 2000–2017, and rates by state 1990–2017 (`data/*.xlsx`)
- **U.S. Census Bureau, American Community Survey 2019 1-year PUMS, New York** — 198,788 people with age, sex, marital status, education, and income (`data/acs_2019_ny_persons.csv`)

## What is in this repo

| File | What it is |
|---|---|
| `marriage_divorce_capstone.ipynb` | The full analysis: loading, cleaning, descriptive statistics, charts, and statistical tests |
| `charts/` | The 7 charts the notebook produces |
| `Marriage_Divorce_Capstone_Presentation.pptx` | The presentation slides |
| `PRESENTATION_SCRIPT.txt` | Speaker notes for the recorded presentation |
| `data/` | The raw data files |

## Main findings

- Both marriage and divorce rates fell in the U.S. from 2000 to 2017 (marriage 8.2 → 6.9 per 1,000, divorce 4.0 → 2.9). Both trends are statistically significant.
- New York had a lower divorce rate than the U.S. in every one of those 18 years.
- 2019 was not different: New York's 2019 rates (6.5 marriages, 2.3 divorces per 1,000) sit right on the long downward trend.
- Divorced New Yorkers are older, more often women, earn about $14,000 less per year, and are less likely to hold a bachelor's degree than married New Yorkers. Divorce peaks in the 50s and 60s.

## How to run

Open the notebook in Jupyter (Anaconda) and choose **Kernel → Restart & Run All**. It needs pandas, numpy, matplotlib, scipy, and openpyxl.

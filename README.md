# HR Employee Attrition — Tableau Dashboard

## View the Notebook
> GitHub's notebook renderer can be unreliable. Use the links below for the best experience:

[![Open in nbviewer](https://img.shields.io/badge/Open%20in-nbviewer-orange?logo=jupyter)](https://nbviewer.org/github/ShantanuDeshmukh21/hr-attrition-tableau-dashboard/blob/master/hr_attrition_prep.ipynb)

## Overview
Python-based data preparation and exploratory analysis for an interactive HR Employee Attrition dashboard built and published on Tableau Public. Analyzes 1,470 employees to identify attrition drivers across departments, age groups, income levels, and working conditions.

## Project Files
| File | Description |
|------|-------------|
| `hr_attrition_prep.ipynb` | Data generation, EDA, and CSV export |
| `hr_attrition_clean.csv` | Clean, enriched dataset ready for Tableau |
| `TABLEAU_GUIDE.md` | Step-by-step instructions to build the dashboard |
| `hr_eda.png` | Exploratory analysis charts |

## Tech Stack
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** — data preparation and EDA
- **Tableau Public** — interactive dashboard (published live)

## Key Findings
- Overall attrition rate: ~16%
- Overtime employees leave at nearly 2x the rate of non-overtime workers
- Employees aged 18–25 have the highest attrition rate
- Lower job satisfaction scores strongly correlate with attrition
- Higher monthly income acts as a retention factor

## Live Dashboard
[View on Tableau Public](https://public.tableau.com) ← *Replace with your actual published link*

## How to Run
1. Run `hr_attrition_prep.ipynb` — this generates `hr_attrition_clean.csv`
2. Open Tableau Public and connect to the CSV
3. Follow `TABLEAU_GUIDE.md` to build your dashboard step by step
4. Publish and paste the link above

---
*Author: Shantanu Deshmukh | MS Computer Science, NJIT*

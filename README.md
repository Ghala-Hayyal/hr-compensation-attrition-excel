# HR Compensation & Attrition Analysis (Excel)

![dashboard](dashboard.mov)

## Business Question
Do pay and overtime explain employee attrition? Is there a gender pay gap within job levels?

## Data
[IBM HR Analytics Employee Attrition](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) (Kaggle) — 1,470 employees, 35 attributes. Fictional dataset created by IBM.

## Tools & Techniques
- **Power Query:** import, remove constant columns, set data types
- **Calculated columns:** income bands, tenure bands, age groups, Compa-Ratio, promotion-overdue flag
- **Analysis:** 9 PivotTables + MEDIAN(IF) array formulas for pay comparison by level and gender
- **Dashboard:** KPI cards linked to PivotTables, 4 PivotCharts, 3 slicers (Department, Gender, Job Level)

## Key Findings
| # | Finding | Evidence |
|---|---|---|
| 1 | Overtime triples attrition | 30.5% vs 10.4% |
| 2 | New hires leave most | 29.8% attrition at 0–2 years tenure vs 8.1% at 11+ years |
| 3 | Low pay, high attrition | 28.6% under 3K vs 3.8% at 15K+ |
| 4 | Sales Representatives leave most | 39.8%, highest of all job roles |
| 5 | No gender pay gap within job levels | Median difference under 3% at every level |
| 6 | Delayed promotion did not raise attrition | 14.2% vs 16.5% |

## Recommendations
1. Cap overtime hours and rebalance workloads in high-overtime teams
2. Strengthen onboarding and mentorship in the first two years
3. Review the entry-level pay scale against market rates
4. Review commission structure and targets for Sales Representatives

## Files
- `HR_Compensation_Attrition.xlsx` — data, analysis, dashboard and insights
- `dashboard.png` — dashboard screenshot

## Limitations
The dataset is fictional, and the findings show correlation, not causation.

## Author
Ghala Almutairi — Payroll & Compensation Specialist | Data Analyst
[LinkedIn](https://www.linkedin.com/in/ghalahayyal/)

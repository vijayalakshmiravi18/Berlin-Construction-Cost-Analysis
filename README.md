# Berlin-Construction-Cost-Analysis
## Project Overview 
Excel-based construction cost tracker and budget variance analysis for 10 active construction projects across Berlin, Germany (2023–2024).
## Business Problem
Construction project managers need to track costs across multiple phases and contractors. This project simulates a real analyst workflow : cleaning messy project data, calculating variances, and presenting insights to management.

## Dataset
- 40+ rows of raw project data
- 10 Berlin construction projects
- 4 construction phases: Foundation, Structure, Finishing, MEP
- 10 contractors with daily rates and overhead percentages

## Excel Skills Used
- VLOOKUP & INDEX-MATCH for contractor rate lookups
- SUMIF & SUMIFS for phase and project summaries
- Conditional Formatting (Red/Orange/Green RAG status)
- Nested IF formulas for status classification
- Cross-sheet formula references
- Data cleaning (duplicates, date formats, text standardization)
- Dashboard design with KPI cards

- ## Workbook Structure
| Sheet | Description |
|---|---|
| 1_Raw_Data | Original messy dataset |
| 2_Contractor_Rates | Lookup table with rates |
| 3_Cleaned_Data | Cleaned and calculated data |
| 4_Pivot_Analysis | Cost breakdown by phase and project |
| 5_Budget_vs_Actual | Full variance analysis with RAG status |
| 6_Dashboard | Executive summary dashboard |

## Key Insights
- Overall portfolio variance: -0.4% (slightly under budget)
- Identifies which phases and projects are over budget instantly
- Tracks days delay per project phase
- Contractor performance comparison across all projects

## Tools Used
- Microsoft Excel 365
- GitHub for version control

# HR Attrition — Interactive Excel Dashboard

An interactive Excel dashboard analysing IBM's HR employee attrition dataset using PivotTables, PivotCharts, and Slicers. Built as a companion piece to the [Python-based EDA project](https://github.com/Njabulo-Kubheka/ibm-hr-attrition-analysis), demonstrating the same analytical insights using a different toolset.

---

## Overview

This project takes the same IBM HR Analytics dataset used in my Python analysis and rebuilds the core insights as a fully interactive Excel dashboard — built entirely with native Excel features (no add-ins, no macros).

The goal was to demonstrate that the same business insights can be delivered through Excel's PivotTable and Slicer functionality, which remains one of the most widely used business intelligence tools in real workplaces.

---

## Dataset

| Property | Detail |
|---|---|
| Source | IBM HR Analytics Employee Attrition & Performance (Kaggle) |
| Records | 1,470 employees |
| Features | 35 columns |

---

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel 365 | Core analysis and dashboard tool |
| PivotTables | Data aggregation and summarisation |
| PivotCharts | Visual representation of insights |
| Slicers | Interactive filtering across the dashboard |

---

## Dashboard Features

- **4 linked PivotTables** analysing:
  - Attrition by Department
  - Attrition by Age Group (custom-grouped bands)
  - Average Monthly Income vs Attrition
  - Attrition Rate by Overtime Status

- **4 PivotCharts** visualising each of the above

- **3 interactive Slicers** (Department, Gender, Job Role) — connected across all PivotTables via Report Connections, allowing every chart on the dashboard to filter simultaneously from a single click

- **Single-sheet Dashboard view** — all charts and slicers consolidated onto one page for a clean, presentation-ready report

---

## Key Insights Replicated

- Research & Development has the highest number of employees leaving
- Employees aged 26–35 show the highest attrition
- A clear income gap exists between employees who stayed vs left
- Overtime work is strongly associated with higher attrition rates

(Full detailed findings and business recommendations are documented in the [Python EDA project](https://github.com/Njabulo-Kubheka/ibm-hr-attrition-analysis))

---

## Skills Demonstrated

- Building and linking multiple PivotTables from a single data source
- Custom grouping of continuous data (age bands) within PivotTables
- Creating PivotCharts linked dynamically to PivotTable data
- Configuring Slicers and managing Report Connections across multiple PivotTables
- Designing a clean, single-page interactive dashboard layout
- Translating the same analytical insights across different BI tools (Python vs Excel)

---

## How to Use

1. Download `IBM-HR-Excel-Dashboard.xlsx`
2. Open in Microsoft Excel (365 recommended for full Slicer functionality)
3. Go to the **Dashboard** sheet
4. Click any Slicer button (e.g. a specific department) to filter all charts simultaneously

---

## Related Project

🐍 **Python/Pandas version of this analysis:** [ibm-hr-attrition-analysis](https://github.com/Njabulo-Kubheka/ibm-hr-attrition-analysis) — includes deeper statistical analysis, 8 key findings, and full business recommendations

---

## Author

**Njabulo Kubheka**
BCom Information Systems — University of the Western Cape
[LinkedIn](https://www.linkedin.com/in/njabulo-kubheka) | [GitHub](https://github.com/Njabulo-Kubheka) | [Kaggle](https://www.kaggle.com/njabulokubheka)

# Darjeeling District Education Analytics & Spatial Intelligence

An end-to-end data analytics and spatial analysis project focused on school education in Darjeeling district, West Bengal.

The project combines **Python, QGIS and Microsoft Power BI** to prepare, analyse and visualize education data across administrative units and academic years.

---

## Project Overview

The project analyses school education data with emphasis on:

- Student enrolment
- Gender-wise enrolment
- Enrolment by school stage
- School infrastructure availability
- Year-wise changes
- Administrative-unit comparisons
- Infrastructure–enrolment relationship
- Infrastructure rankings and improvement
- Enrolment rankings and improvement
- Spatial distribution of analytical results

The study covers the academic years represented in the source datasets, with the Power BI analysis focusing particularly on the period from **2015–16 to 2019–20**.

---

## Project Workflow

```text
Government Data
      │
      ├──────────────────────┐
      │                      │
      ▼                      ▼
Education Data          Geographic Data
      │                      │
      ▼                      ▼
Python / Jupyter          QGIS
      │                      │
      ▼                      ▼
Prepared Data        Darjeeling Administrative
      │                   Spatial Layer
      │                      │
      └──────────┬───────────┘
                 ▼
             Power BI
                 │
                 ▼
        Analytics & Visualization

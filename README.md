# Respiratory Disease Surveillance in England

A 6‑day simulated analysis for **UKHSA Field Services**, demonstrating R skills in public health surveillance, outbreak investigation, and data communication.

[**View the Live Dashboard →**](https://marcosorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/06_day6_dashboard.html)

------------------------------------------------------------------------

## 📁 Project Structure

| Day | Title | Focus | Output |
|------------------|------------------|------------------|-------------------|
| 1 | Routine Surveillance | Respiratory mortality trends | [HTML](https://marcosorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/01_day1_surveillance.html) |
| 2 | Outbreak Investigation | C. difficile detection | [HTML](https://marcosorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/02_day2_outbreak.html) |
| 3 | Local Authority Request | MMR coverage in Leicester | [HTML](https://marcosorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/03_day3_data_request.html) |
| 4 | Statistical Comparison | North‑South hypothesis test | [HTML](https://marcosorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/04_day4_statistical.html) |
| 5 | Team Briefing | One‑page synthesis | [HTML](https://marcosorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/05_day5_briefing.html) |
| 6 | Interactive Dashboard | Exploratory data tool | [Dashboard](https://marcosorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/06_day6_dashboard.html) |

------------------------------------------------------------------------

## 📊 Data Sources

| Source | Description |
|----------------------------|--------------------------------------------|
| **Fingertips** | Public health indicators (respiratory mortality, MMR coverage) |
| **UKHSA Data Dashboard** | Infectious disease surveillance (C. difficile) |
| **ONS** | Population estimates and boundaries |
| **NHS Digital** | Hospital Episode Statistics |

------------------------------------------------------------------------

## 🔑 Key Findings

-   **North‑South divide**: Northern regions have 14.1 more respiratory deaths per 100,000 – a **48% higher rate** (p \< 0.001, Cohen's d = 2.4)
-   **Outbreak signal**: East Midlands showed **80% of weeks exceeding** C. difficile threshold
-   **MMR decline**: Leicester fell from **95.8% coverage (2013) to 88.4% (2024)**
-   **Sustained inequality**: The North‑South gap has persisted for over two decades

------------------------------------------------------------------------

## 🛠️ Technical Notes

| Aspect | Detail |
|------------------------------------|------------------------------------|
| **R version** | 4.5.2 |
| **Key packages** | `tidyverse`, `plotly`, `flexdashboard`, `leaflet`, `fingertipsR`, `ukhsadatR`, `effectsize` |
| **Colour schemes** | Viridis (colourblind‑safe) |
| **Interactive elements** | `plotly` for charts, `leaflet` for maps, `DT` for tables |

------------------------------------------------------------------------

## 📋 How This Project Maps to the UKHSA EO Role

This 6‑day simulation was designed to demonstrate every essential criterion for the Epidemiology and Information Analyst (EO) role at UKHSA.

### Essential Criteria – Demonstrated

| Criterion | Evidence in This Project |
|----------------------|--------------------------------------------------|
| Degree or equivalent in data maintenance/analysis | PhD (Imperial) + full R workflow with data caching, version control, and reproducible methods |
| Analytical skills, basic statistical tests | Welch t‑test, Cohen's d, Poisson thresholds, descriptive statistics, p‑value interpretation |
| Experience of report writing | One‑page team briefing (Day 5), Quarto documents with clear interpretation for non‑technical audiences |
| Maintaining/analysing data using common software | R, tidyverse, ggplot2, plotly, leaflet, flexdashboard: full reproducible workflow |
| Experience and understanding of SOPs | Structured 6‑day workflow, data caching, Git version control, reproducible methods |
| NHS / epidemiology / public health experience | Real UKHSA data (Fingertips, UKHSA dashboard), respiratory mortality, C. difficile outbreaks, MMR coverage |
| Good oral and written communication | Plain‑language briefing, stakeholder‑focused outputs (local authority request), interactive dashboard |
| Quality and accuracy under pressure | 6‑day simulated outbreak response with tight deadlines; all analyses reproducible and documented |
| Organisation, prioritisation, teamwork | Structured project with clear phases; simulated multidisciplinary briefing; independent work with stakeholder requests |
| Equality of opportunity | North‑South inequality analysis, health disparities focus, colourblind‑safe visualisations |

### Desirable Criteria – Also Demonstrated

| Criterion | Evidence |
|--------------------------------------|----------------------------------|
| Knowledge of statistical/database/mapping tools | R, ggplot2, plotly, leaflet, DT, sf, flexdashboard |
| Information governance awareness | Use of official UKHSA data sources, data caching, reproducible methods, no redistribution of raw data |
| Ability to adapt queries for research | Custom queries for respiratory mortality, C. difficile surveillance, MMR coverage, North‑South comparison |
| Interest in public health epidemiology | Full project focused on respiratory disease, outbreaks, vaccine coverage, and health inequalities |

### Technical Skills Summary

| Skill | Tools & Methods |
|----------------------|--------------------------------------------------|
| Data acquisition | `fingertipsR`, `ukhsadatR`, API integration, data caching |
| Data wrangling | `tidyverse`, string manipulation, fuzzy matching, joins, pivot operations |
| Statistical analysis | t‑test, Cohen's d, Poisson thresholds, variance ratio, p‑value interpretation |
| Visualisation | `ggplot2`, `plotly`, `leaflet`, heatmaps, colourblind‑safe palettes (viridis) |
| Dashboard development | `flexdashboard`, `DT` tables, interactive elements |
| Reproducibility | Quarto, Git, GitHub, data caching, project structure |

### How to Verify

-   **Live dashboard:** [marcoSorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/06_day6_dashboard.html](https://marcoSorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/06_day6_dashboard.html)
-   **GitHub repository:** [github.com/MarcoSorbona/ukhsa-respiratory-and-outbreak-surveillance](https://github.com/MarcoSorbona/ukhsa-respiratory-and-outbreak-surveillance)
-   All code is public, documented, and reproducible

---

## 🔁 Reproducibility

All analyses are fully reproducible:

1.  **Clone** this repository
2.  **Run** `00_setup.qmd` once to download and cache all data
3.  **Render** any day's `.qmd` file or the dashboard

``` r
# Example: render the dashboard
quarto::quarto_render("06_day6_dashboard.Rmd")
```

------------------------------------------------------------------------

## 📬 Contact

**Marco Sorbona, PhD**\
[LinkedIn](https://linkedin.com/in/marco-sorbona-phd) \| [GitHub](https://github.com/MarcoSorbona)

------------------------------------------------------------------------

## 📄 License

**Code**: MIT © Marco Sorbona\
**Data**: Open Government Licence v3.0 (via Fingertips, UKHSA, ONS, NHS Digital)

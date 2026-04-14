# Respiratory Disease Surveillance in England

A portfolio of public health data science projects for **UKHSA Field Services**, demonstrating R skills in surveillance, outbreak detection, immunisation, statistical analysis, and environmental epidemiology.

[**View the Live Dashboard →**](https://marcosorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/06_day6_dashboard.html)

------------------------------------------------------------------------

## 📁 Project Structure

| \# | Project | Focus | Output |
|------------------|------------------|------------------|------------------|
| 1 | Routine Surveillance | Respiratory mortality trends | [HTML](https://marcosorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/01_day1_surveillance.html) |
| 2 | Outbreak Investigation | C. difficile detection | [HTML](https://marcosorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/02_day2_outbreak.html) |
| 3 | Local Authority Request | MMR coverage in Leicester | [HTML](https://marcosorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/03_day3_data_request.html) |
| 4 | Statistical Comparison | North‑South hypothesis test | [HTML](https://marcosorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/04_day4_statistical.html) |
| 5 | Team Briefing | One‑page synthesis | [HTML](https://marcosorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/05_day5_briefing.html) |
| 6 | Environmental Hazards | Air pollution and respiratory mortality | [HTML](https://marcosorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/environmental.html) |
| 7 | Interactive Dashboard | Exploratory data tool | [Dashboard](https://marcosorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/06_day6_dashboard.html) |

------------------------------------------------------------------------

## 📊 Data Sources

| Source | Description |
|------------------------------------|------------------------------------|
| **Fingertips** | Public health indicators (respiratory mortality, MMR coverage) |
| **UKHSA Data Dashboard** | Infectious disease surveillance (C. difficile) |
| **ONS** | Population estimates and boundaries |
| **NHS Digital** | Hospital Episode Statistics |
| **UK-AIR (DEFRA)** | Air pollution data (PM2.5) |

------------------------------------------------------------------------

## 🔑 Key Findings

-   **North‑South divide**: Northern regions have 14.1 more respiratory deaths per 100,000 – a **48% higher rate** (p \< 0.001, Cohen's d = 2.4)
-   **Outbreak signal**: East Midlands showed **80% of weeks exceeding** C. difficile threshold
-   **MMR decline**: Leicester fell from **95.8% coverage (2013) to 88.4% (2024)**
-   **Sustained inequality**: The North‑South gap has persisted for over two decades
-   **Environmental link**: Positive association between PM2.5 and mortality in 2024 (r = 0.57), persisting after deprivation adjustment

------------------------------------------------------------------------

## 🛠️ Technical Notes

| Aspect | Detail |
|------------------------------------|------------------------------------|
| **R version** | 4.5.2 |
| **Key packages** | `tidyverse`, `plotly`, `flexdashboard`, `leaflet`, `fingertipsR`, `ukhsadatR`, `effectsize` |
| **Colour schemes** | Viridis (colourblind‑safe) |
| **Interactive elements** | `plotly` for charts, `leaflet` for maps, `DT` for tables |

------------------------------------------------------------------------

## 📋 Skills Summary – Evidence for Data Science Roles

This portfolio demonstrates a range of technical and professional skills applicable to epidemiology, public health data science, and data curation roles.

### Technical Skills

| Skill | Tools & Methods | Evidence in Portfolio |
|----------------|------------------------|--------------------------------|
| **Data acquisition** | `fingertipsR`, `ukhsadatR`, `openair`, API integration, data caching | Projects 1, 2, 6 |
| **Data wrangling** | `tidyverse`, string manipulation, fuzzy matching, joins, pivot operations | All projects |
| **Statistical analysis** | t‑test, Cohen's d, Poisson thresholds, variance ratio, correlation, partial correlation | Projects 4, 6 |
| **Visualisation** | `ggplot2`, `plotly`, `leaflet`, heatmaps, colourblind‑safe palettes (viridis) | All projects |
| **Dashboard development** | `flexdashboard`, `DT` tables, interactive elements | Project 7 |
| **Reproducibility** | Quarto, Git, GitHub, data caching, project structure | Entire portfolio |
| **Data curation** | Reusable pipelines, data validation, quality checks, documentation | Projects 1, 6 (data dictionaries, curation reports) |

### Professional Competencies

| Competency | Evidence |
|---------------------------------------|---------------------------------|
| **Analytical skills** | Welch t‑test, Cohen's d, Poisson thresholds, correlation analysis, p‑value interpretation |
| **Report writing** | One‑page team briefing, Quarto documents with clear interpretation for non‑technical audiences |
| **Data governance** | Use of official APIs, data caching, reproducible methods, no redistribution of raw data |
| **Communication** | Plain‑language briefing, stakeholder‑focused outputs (local authority request), interactive dashboard |
| **Quality assurance** | Data validation checks, missing value handling, outlier detection, reproducible workflows |
| **Equality and inclusion** | North‑South inequality analysis, health disparities focus, colourblind‑safe visualisations, accessible outputs |
| **Independent work** | Structured project with clear phases; self‑directed stakeholder requests |

### How This Portfolio Maps to Specific Roles

#### UKHSA Epidemiology and Information Analyst (EO)

| Criterion | Evidence |
|--------------------------------------|----------------------------------|
| Degree or equivalent | PhD (Imperial) + full R workflow with data caching, version control, and reproducible methods |
| Analytical skills, basic statistical tests | Welch t‑test, Cohen's d, Poisson thresholds, descriptive statistics |
| Experience of report writing | One‑page team briefing, Quarto documents |
| Maintaining/analysing data using common software | R, tidyverse, ggplot2, plotly, leaflet, flexdashboard |
| NHS / epidemiology experience | Real UKHSA data (Fingertips, UKHSA dashboard), respiratory mortality, C. difficile outbreaks, MMR coverage |
| Equality of opportunity | North‑South inequality analysis, health disparities focus, colourblind‑safe visualisations |

#### HDR UK / Data Curation Roles

| Criterion | Evidence |
|--------------------------------------|----------------------------------|
| Data curation pipelines | Reusable data processing scripts, validation functions, data dictionaries |
| Data quality assessment | Missing value handling, duplicate detection, range checks, quality reports |
| Documentation | Data dictionaries, curation reports, reproducible workflows |
| Open science | Public GitHub repository, version control, documented code |
| Working with messy data | Handling of API data, inconsistent formats, missing values |

#### General Data Science Roles

| Criterion | Evidence |
|--------------------------------------|----------------------------------|
| Programming (R) | Extensive use of tidyverse, plotly, leaflet, flexdashboard |
| Statistical reasoning | Hypothesis testing, effect sizes, correlation, p‑value interpretation |
| Data visualisation | Interactive plots, maps, heatmaps, colourblind‑safe palettes |
| Reproducible research | Quarto documents, Git version control, cached data |
| Communication | Clear interpretation for technical and non‑technical audiences |

### How to Verify

-   **Live dashboard:** [marcoSorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/06_day6_dashboard.html](https://marcoSorbona.github.io/ukhsa-respiratory-and-outbreak-surveillance/06_day6_dashboard.html)
-   **GitHub repository:** [github.com/MarcoSorbona/ukhsa-respiratory-and-outbreak-surveillance](https://github.com/MarcoSorbona/ukhsa-respiratory-and-outbreak-surveillance)
-   All code is public, documented, and reproducible

------------------------------------------------------------------------

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

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
| **R version** | 4.5.3 |
| **Key packages** | `tidyverse`, `plotly`, `flexdashboard`, `leaflet`, `fingertipsR`, `ukhsadatR`, `effectsize` |
| **Colour schemes** | Viridis (colourblind‑safe) |
| **Interactive elements** | `plotly` for charts, `leaflet` for maps, `DT` for tables |

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
[LinkedIn](https://linkedin.com/in/marco-sorbona) \| [GitHub](https://github.com/MarcoSorbona)

------------------------------------------------------------------------

## 📄 License

**Code**: MIT © Marco Sorbona\
**Data**: Open Government Licence v3.0 (via Fingertips, UKHSA, ONS, NHS Digital)

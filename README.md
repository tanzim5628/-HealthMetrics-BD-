# HealthMetrics BD 🇧🇩

> A comprehensive, fully responsive health and population data dashboard for Bangladesh — built with pure HTML, CSS, and JavaScript. No frameworks. No dependencies beyond Chart.js.


## Overview

HealthMetrics BD is an interactive data analytics platform that visualizes Bangladesh's national health and demographic trends from 1990 to 2024. It presents complex public health data in a clean, accessible, and professional interface designed for researchers, analysts, students, and policymakers.

## Features

- **Interactive KPI cards** — population, life expectancy, infant mortality, and fertility rate with year-over-year context
- **Trend line chart** — switchable between life expectancy, infant mortality, and fertility rate across 35 years
- **South Asia comparison** — Bangladesh ranked against Sri Lanka, India, Nepal, Bhutan, and Pakistan
- **Age structure donut chart** — population breakdown by age group
- **Causes of death** — leading disease burden visualization
- **1990 vs 2024 indicator table** — side-by-side comparison with change badges
- **Global benchmark cards** — Bangladesh vs global averages
- **Urban vs rural stacked bar chart** — urbanization trend 1990–2024
- **Year selector** — all KPI cards update dynamically when switching years
- **Fully responsive sidebar** — fixed drawer on desktop, slide-in hamburger menu on mobile with overlay

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, CSS Grid, Flexbox) |
| Charts | Chart.js 4.4.1 |
| Typography | Plus Jakarta Sans, DM Mono (Google Fonts) |
| Icons | Inline SVG |
| Data | WHO, World Bank, UN DESA, Worldometer |

## Responsive Breakpoints

| Breakpoint | Layout |
|---|---|
| > 1100px | Full sidebar + 4-column KPI + 3-column panels |
| 768px – 1100px | Sidebar + 2-column KPI + 2-column panels |
| < 768px | Hidden sidebar (hamburger drawer) + 2-column KPI |
| < 420px | Single column, fully stacked |

## Data Sources

- World Health Organization (WHO)
- World Bank Open Data
- United Nations Department of Economic and Social Affairs (UN DESA)
- Worldometer Bangladesh

## Getting Started
```bash
git clone https://github.com/yourusername/healthmetrics-bd.git
cd healthmetrics-bd
open healthmetrics-bd.html
```

No build step. No npm install. Just open the HTML file in any modern browser.

## Project Structure
```
healthmetrics-bd/
├── healthmetrics-bd.html   # Single-file application
├── README.md
└── preview.png             # Screenshot for README
```

## License

MIT License — Private

---

*Built with a commitment to making public health data in Bangladesh more visible and accessible.*

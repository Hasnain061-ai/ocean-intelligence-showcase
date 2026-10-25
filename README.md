# Ocean Intelligence

A web portal for NDMA Pakistan that shows how acidity, heat and oxygen in Pakistan's seas have changed since the 1980s, and where they are heading by 2050.

[![Ocean Intelligence: sea-surface temperature trend per decade across Pakistan's Exclusive Economic Zone, 1982-2025](screens/oi-warming.webp)](https://hasnain061-ai.github.io/#ocean-intelligence)

**Demo video:** [watch on LinkedIn](https://lnkd.in/p/dcSiaMx6)

## What it does

- **Acidification, mapped**: surface pH across Pakistan's Exclusive Economic Zone fell from 8.08 in 1985 to 8.02 in 2024, about 16% more acidity, and it fell in every area checked.
- **Warming and marine heatwaves**: the sea has warmed by 1.0 to 1.3 °C since 1982, and days above the marine-heatwave line rose from about 23 a year (1991-2020 average) to about 100 (2021-2025).
- **Low oxygen on the shelf**: in the southwest monsoon, 24% of the Sindh shelf floor sits below 2 mg/L of oxygen.
- **Outlook to 2050**: low- and high-emission paths, side by side or against today.
- **Compare, trends and findings**: swipe, side-by-side or difference views, Mann-Kendall trends for any region or place, and a findings page that explains each result in plain words.
- **A chat assistant**: questions in English or Roman Urdu, answered from the study's numbers.

| | |
|---|---|
| ![The chat assistant answering a Roman Urdu question on marine heatwave days, with a chart and the map.](screens/oi-chat.webp) | ![Map of the part of the pH trend caused by rising dissolved CO2, with a table splitting the trend into CO2, warming, alkalinity and salinity.](screens/oi-drivers.webp) |
| A question in Roman Urdu, answered with the study's numbers, a chart and the map. | What drives the fall in pH: rising CO₂ gives 68%, warming 30%. |
| ![Bar chart of annual sea-surface temperature for the whole zone, 1982 to 2025, with a trend line and the warmest years in red.](screens/oi-sst-chart.webp) | ![Surface pH in 2050 side by side: low emissions on the left, high emissions on the right.](screens/oi-2050.webp) |
| Sea-surface temperature through time, 1982-2025, with its trend. | Surface pH in 2050, low emissions against high emissions. |
| ![Map of marine heatwave days per year in 2021 to 2025, with a table comparing each region with its 1991 to 2020 normal.](screens/oi-heatwave-days.webp) | ![Map of coral reef habitat classes by aragonite saturation, 2020 to 2024, with marginal cells on the Makran shelf.](screens/oi-coral.webp) |
| Marine heatwave days a year, 2021-2025, against the 1991-2020 normal. | Coral habitat class by aragonite saturation, 2020-2024: 37% of the Makran shelf is now marginal. |
| ![Bar chart of surface pH for the whole zone, falling from 1985 to 2024, with a trend line.](screens/oi-analysis.webp) | ![The findings page with cards for acidification, warming, marine heatwaves, oxygen and overall climate pressure.](screens/oi-findings.webp) |
| Surface pH through time, 1985-2024, with its trend. | The main findings, each with what it means. |
| ![Difference map of surface pH, 2015 to 2024 minus 1985 to 1994, lower in every cell.](screens/oi-difference.webp) |  |
| Change in surface pH, 2015-2024 minus 1985-1994: lower everywhere. |  |

## Built with

Mapbox GL JS, JavaScript, Chart.js, Python

## Data

Copernicus Marine (CMEMS-LSCE), NOAA OISST, ERSSTv5, FAO FishStat

## Code and data access

The source code is private and belongs to NDMA Pakistan. To ask about the code or the data,
email **ranahasnain061@gmail.com**, [open an issue](../../issues) in this repository, or message me on
[LinkedIn](https://www.linkedin.com/in/muhammad-hasnain-87450033a/).

---
Built by [Muhammad Hasnain](https://hasnain061-ai.github.io) at NDMA Pakistan.

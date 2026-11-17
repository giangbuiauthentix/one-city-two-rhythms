# One City, Two Rhythms

**Chicago Divvy bikeshare · 2017 · Tableau**

[Explore the interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/giang.bui7732/viz/OneCityTwoRhythms/OneCityTwoRhythms)

How does Chicago’s bikeshare network change from weekdays to weekends? This dashboard compares when and where rides start, using **3.83 million departures across 585 stations** in 2017. Select a station on either map to see its weekday and weekend averages and its hourly departure patterns.

[![One City, Two Rhythms Tableau dashboard showing hourly Divvy departures and side-by-side weekday and weekend station maps](https://public.tableau.com/static/images/On/OneCityTwoRhythms/OneCityTwoRhythms/1.png)](https://public.tableau.com/app/profile/giang.bui7732/viz/OneCityTwoRhythms/OneCityTwoRhythms)

## What the data shows

| Measure | Weekdays | Weekends |
| --- | ---: | ---: |
| Average departures per day | 10,786 | 9,738 |
| Peak hour by month (Chicago time) | 5 p.m. in all 12 months | Between 1 and 3 p.m. depending on the month |

The shift looks different by station. Average daily departures at **Streeter & Grand** more than doubled on weekends, while **Clinton & Washington** saw a **91% decline**.

## Data and methodology

- **Sources.** 2017 Divvy trip records via yingwurenjian on Kaggle, as credited in the dashboard. [Divvy’s official system data](https://divvybikes.com/system-data) provides background and historical trip downloads. Map boundaries are from the [City of Chicago Data Portal](https://data.cityofchicago.org/d/ewy2-6yfk).
- **Cleaning.** Removed 22 duplicate or invalid records, retained trips with positive trip lengths, and used median station coordinates for mapping.
- **Comparison.** Divided departure counts by 260 weekdays or 105 weekend days, including hours with zero departures. Both maps use the same circle-size scale.
- **Interpretation.** Weekdays include holidays. Observed departures reflect usage under existing bike availability and cannot establish trip purpose or unmet demand.

Built by **Giang Bui**.

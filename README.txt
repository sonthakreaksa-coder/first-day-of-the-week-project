First Day of the Week — Data Analysis
=====================================

Question: do more places (and more people) treat Sunday or Monday as the
start of the week, and how does that vary by region?

Files
-----
first-day-of-week.ipynb
    Analysis notebook. Run all cells from this folder.

first-day-of-week.csv
    Territory, ISO alpha-3, first weekday, measurement units, paper size.
    Source: Unicode CLDR supplemental territory information (unicode.org).

population.csv
    2020 population in millions, keyed by alpha-3.
    Source: UN population estimates via gapminder.org.

four-regions.csv
    Gapminder four-region labels (africa, americas, asia, europe).
    Source: gapminder.org.

Questions in the notebook
-------------------------
 1. Territory counts by first weekday
 2. Population by first weekday
 3. Regional pattern by territory count
 4. Regional pattern weighted by population
 5. Friday- and Saturday-first territories
 6. Measurement units vs first weekday
 7. Paper size vs first weekday and region
 8. Join coverage (missing population / region)
 9. First weekday of the 15 largest territories
10. Sunday vs Monday population split by region
11. Summary table (counts, people, averages)
12. Charts

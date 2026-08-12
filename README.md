## Pediatric Non-Accidental Trauma & COVID-19: A 14-Year Retrospective Analysis

This project analyzes over a decade of pediatric emergency department data to understand how the COVID-19 pandemic affected rates of physical child abuse in a rural Appalachian healthcare system. Working with more than 509 confirmed abuse encounters spanning 2010–2024, I built a full analytical pipeline — from statistical hypothesis testing to custom geospatial mapping — to answer a question that matters well beyond the hospital walls: did the pandemic's disruption to schools, healthcare access, and household stability leave a lasting mark on child safety, and where?

What this project does:

Segments 14 years of encounters into pre-, during-, and post-pandemic windows and tests for statistically significant shifts in patient age, insurance status, and case volume using chi-square, Kruskal-Wallis, and ANOVA testing
Builds a custom geospatial heat map of Appalachian zip codes using Census TIGER/Line shapefiles, layering in economic distress data (Distressed Communities Index) to visualize where risk concentrated
Surfaces a striking, policy-relevant finding: case volume didn't just spike during lockdowns — it kept climbing for years afterward, suggesting the pandemic acted as a lasting inflection point rather than a temporary disruption.

Tech stack: Python (pandas, GeoPandas, SciPy, Matplotlib), Census TIGER/Line shapefiles, Distressed Communities Index (EIG).

💡 Why this matters: Aggregate national statistics can hide exactly the regional and community-level patterns that matter most for targeted intervention. This analysis shows how local health systems can use their own data, paired with public economic indicators, to identify at-risk populations without needing large-scale funded infrastructure.

🚀 Possible extensions: This pipeline could be adapted to track other pediatric injury categories, extended to neighboring states for regional comparison, or paired with time-series forecasting to flag emerging hotspots in near-real-time.

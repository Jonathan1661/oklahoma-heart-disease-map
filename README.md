# Oklahoma Heart Disease Map

## Overview
This project maps age-adjusted heart disease prevalence across Oklahoma counties using public health data and county-level geographic boundaries. The goal was to identify geographic patterns in cardiovascular risk and compare them with obesity prevalence.

## Tools Used
- Python
- Pandas
- Plotly
- Jupyter Notebook
- GeoJSON county boundaries

## Key Questions
- Which Oklahoma counties have the highest heart disease prevalence?
- Are there visible regional clusters of higher cardiovascular risk?
- Does obesity follow the same geographic pattern as heart disease?

## Project Steps
1. Loaded county-level Oklahoma health data
2. Filtered to coronary heart disease prevalence
3. Used age-adjusted prevalence for fair county comparison
4. Mapped county-level heart disease prevalence using a choropleth
5. Repeated the process for obesity prevalence for comparison

## Key Findings
- Heart disease prevalence is highest in southeastern Oklahoma counties
- The pattern suggests regional disparities in cardiovascular risk
- Obesity does not perfectly align with the heart disease pattern
- This suggests additional drivers, such as healthcare access or socioeconomic conditions, may contribute to higher heart disease prevalence

## Files
- `notebooks/Heart_Disease_Oklahoma.ipynb` — main notebook
- `data/places.csv` — Oklahoma health dataset from CDC PLACES data portal
- `data/counties.json` — county boundary file for mapping

## Summary
This project demonstrates geospatial analysis, public health data interpretation, and geographic comparison of health outcomes at the county level.

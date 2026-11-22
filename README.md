# India Air Quality Analysis (2022–2026)

## Project Overview
This project explores air pollution patterns across 10 selected Indian cities using publicly available air quality data from data.gov.in.

The goal is to analyse recorded maximum AQI values, compare pollution levels across cities and years, and identify observations falling into different AQI categories.

## Dataset
- Source: data.gov.in
- Original records: 160
- Cleaned records: 154
- Cities covered: 10
- Years covered: 2022–2026
- Observations: October, November, December and January

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed
- Data cleaning and preprocessing
- City-wise maximum AQI analysis
- Year-wise and month-wise AQI comparison
- City-wise average AQI ranking
- AQI category classification
- Severe AQI analysis
- Data visualisation using charts and heatmaps

## Key Findings
- Delhi recorded the highest maximum AQI of 494.
- November had the highest monthly average recorded maximum AQI.
- 77 observations were classified as Very Poor.
- 49 observations were classified as Severe.

## Project Structure
```text
India_Air_Quality_Analysis/
├── data/
│   ├── aqi_data.csv.csv
│   └── cleaned_aqi_data.csv
├── notebooks/
│   └── India_Air_Quality_Analysis.ipynb
└── README.md
```

## Limitations
- The dataset covers only 10 selected cities, not all Indian cities.
- Only October, November, December and January observations are included.
- 2026 contains January observations only.
- The analysis uses recorded monthly maximum AQI values, not daily or annual average AQI.

## Conclusion
This project demonstrates practical skills in Python-based data analysis, data cleaning, exploratory data analysis and data visualisation using a real-world public dataset.

## View Project Notebook

Explore the complete analysis, including data preprocessing, exploratory data analysis, charts, heatmaps, and key findings.

[View India Air Quality Analysis Notebook](notebooks/India_Air_Quality_Analysis.ipynb)
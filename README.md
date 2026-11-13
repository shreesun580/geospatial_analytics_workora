# 🌍 Geospatial Data Analysis – Regional Market Opportunity Analysis

**Workora Data Analytics Virtual Internship Project**

## 📌 Project Overview

This project analyzes geographic market data across India to identify high-potential regional expansion opportunities using location-based data analysis and visualization.

The analysis focuses on monthly search demand, existing competitors, lead conversion rates, income levels, and estimated customer acquisition costs.

## 🎯 Objectives

- Analyze regional market demand across Indian cities and states.
- Validate and clean geographic data.
- Perform state-level market aggregation.
- Calculate regional opportunity scores.
- Identify the top 3 potential expansion regions.
- Build an interactive geographic map using Folium.

## 🛠️ Tools & Technologies

- Python
- Pandas & NumPy
- Matplotlib
- Folium
- Jupyter Notebook
- GitHub

## 📊 Dataset Information

- Total Records: 400
- Total Columns: 11
- Unique Cities: 10
- Unique States: 9
- Missing Values: 0
- Duplicate Records: 0

The dataset contains synthetic city-level coordinates and market indicators.

## 🔍 Analysis Methodology

1. Data Cleaning & Validation
2. Geographic Coordinate Validation
3. State-wise Market Aggregation
4. Regional Demand Analysis
5. Opportunity Score Calculation
6. Interactive Map Visualization

### Opportunity Score Weights

| Metric | Weight |
|---|---:|
| Monthly Search Demand | 40% |
| Lower Competition | 25% |
| Lead Conversion Rate | 20% |
| Median Annual Income | 10% |
| Lower Acquisition Cost | 5% |

## 🏆 Top 3 Opportunity Regions

| Rank | City | State | Opportunity Score |
|---|---|---|---:|
| 1 | Kochi | Kerala | 90.88 |
| 2 | Kolkata | West Bengal | 89.47 |
| 3 | Chennai | Tamil Nadu | 86.30 |

## 🗺️ Interactive Geographic Map

Explore the interactive India market opportunity map:

**[View Interactive Geospatial Map](https://shreesun580.github.io/geospatial_analytics_workora/)**

The map displays 400 regional locations and highlights the top 3 opportunity regions with markers. Click individual markers to explore regional market information.

## 📁 Project Structure

```text
geospatial_analytics_workora/
│
├── README.md
├── index.html
├── geospatial_analytics.ipynb
├── india_regional_market_v2.csv
│
└── output/
    ├── india_geospatial_opportunity_map.html
    ├── geospatial_analysis_report.pdf
    ├── state_market_analysis.csv
    ├── top_3_opportunity_regions.csv
    ├── regional_opportunity_scores.csv
    │
    └── charts/
        ├── state_search_demand.png
        └── top_3_opportunity_regions.png
```

## 💡 Key Findings

- Kochi achieved the highest regional opportunity score.
- Kolkata ranked second based on the weighted opportunity model.
- Chennai ranked third with strong monthly search demand.
- Regional opportunity scores help prioritize locations for further market research.

## ⚠️ Dataset Limitations

The dataset contains synthetic geographic and market indicators. It does not include actual sales revenue, postal codes, verified population counts, or customer density. Search demand is used as a demand indicator, not actual customer volume.

The opportunity score is a custom weighted ranking and does not guarantee business success.

## 👩‍💻 Author

**S. SHREE VATHY**

Data Analytics Intern – Workora

**Project:** Geospatial Data Analysis

**GitHub:** https://github.com/shreesun580/geospatial_analytics_workora

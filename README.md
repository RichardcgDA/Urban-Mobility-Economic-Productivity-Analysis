# Urban-Mobility-Economic-Productivity-Analysis
Python | Pandas | NumPy | Matplotlib | Seaborn

# Urban Mobility & Economic Productivity Analysis 🚦

### An Exploratory Data Analysis of Traffic Congestion and Economic Indicators Across Latin American Cities

**Tools:** Python | Pandas | NumPy | Matplotlib | Seaborn

## Project Overview

Does higher economic productivity translate into better urban mobility?

This project investigates the relationship between **urban traffic congestion and GDP per capita** across major Latin American cities. Using real-world datasets from TomTom Traffic Index and OECD Cities, I cleaned, integrated, and analyzed mobility and economic indicators to identify patterns, evaluate differences between cities, and explore potential priorities for transportation infrastructure investment.

The analysis revealed **no clear relationship between GDP per capita and traffic congestion**, suggesting that economic productivity alone does not explain urban mobility challenges.

## Business Objectives

- Investigate the relationship between traffic congestion and GDP per capita.
- Identify cities experiencing particularly high traffic delays.
- Compare urban mobility indicators across Latin American cities.
- Explore potential opportunities for transportation infrastructure investment.
- Translate analytical findings into actionable recommendations.

## Data Sources

The project combines two datasets:

**1. TomTom Traffic Index**
- Traffic congestion delays.
- Live traffic index.
- Traffic jam length and count.
- Average travel time and delay metrics.

**2. OECD Cities**
- GDP per capita.
- Unemployment rate.
- Population.
- PM2.5 air pollution levels.

**Analysis period:** 2024

**Geographic coverage:** 15 Latin American cities across Argentina, Brazil, Colombia, Mexico, Peru, and Uruguay.

## ⚙️ Methodology

### 1. Data Exploration & Cleaning
- Inspected dataset structures, data types, and missing values.
- Standardized column names using snake_case.
- Converted timestamps into datetime format.
- Cleaned numerical values and corrected data types.
- Prepared population figures for analysis.

### 2. Data Transformation & Integration
- Filtered traffic and economic datasets for 2024.
- Aggregated traffic indicators by city, country, and year.
- Selected relevant economic and mobility variables.
- Combined both datasets using an INNER JOIN equivalent through Pandas `merge()`, matching cities and years.

### 3. Exploratory Data Analysis (EDA)
- Used boxplots to examine traffic delay distributions and identify outliers.
- Created histograms to investigate the distribution of traffic congestion.
- Compared GDP per capita and traffic delays across cities using visualizations.
- Investigated potential relationships between economic and mobility indicators.

## Key Findings

**1. No clear relationship between GDP per capita and traffic congestion**

Cities with higher GDP per capita did not consistently experience higher or lower traffic congestion. This suggests that other factors may play a significant role in urban mobility.

**2. Mexico City stood out as an extreme congestion case**

Mexico City recorded approximately 2,833 minutes in average `jams_delay` in the aggregated dataset, making it a significant outlier compared with other cities.

**3. Traffic congestion varied considerably across cities**

The distribution of traffic delays was positively skewed, with most cities showing lower or moderate congestion levels and a smaller number experiencing substantially higher delays.

## Business Recommendations

Based on the exploratory findings, the analysis identified several opportunities for further investigation:

- **Bogotá:** Consider prioritizing transportation infrastructure and public transit improvements due to its high congestion levels and comparatively lower GDP per capita.
- **Lima:** Investigate urban traffic bottlenecks and opportunities to strengthen public transportation systems.
- **Mexico City:** Conduct a deeper assessment of the economic impact of extreme traffic congestion, given the scale of its delays.
- **Buenos Aires:** Continue monitoring traffic performance and evaluate opportunities to optimize existing infrastructure.

These recommendations represent exploratory priorities, not proven investment outcomes. Additional analysis would be required to establish economic impact and investment returns.

## 🛠️ Technical Skills Demonstrated

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Data Transformation & Integration
- Data Visualization
- Business-Oriented Analytical Thinking

## Project Files

- `S5 ladb_mobility_economy_project_student.ipynb` — Complete analysis, Python code, visualizations, and conclusions.
- `ladb_mobility_economy_2024_clean.csv` — Cleaned and integrated dataset generated during the analysis.

## Final Conclusion

This project demonstrates how data analysis can be used to investigate complex urban challenges and support evidence-based decision-making.

Although the analysis did not identify a clear relationship between GDP per capita and traffic congestion, it highlighted significant differences in mobility conditions across cities and identified areas that warrant further investigation.

The findings reinforce the importance of looking beyond individual economic indicators when evaluating urban transportation challenges.

---

**Author:** Ricardo Cruz Guerra  
**Field:** Data Analytics & Business Intelligence

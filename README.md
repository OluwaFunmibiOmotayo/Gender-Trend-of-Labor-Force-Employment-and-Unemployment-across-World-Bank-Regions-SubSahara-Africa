# Visualizations of the Gender Trend of Labor Force, Employment and Unemployment across World Bank Regions- SubSahara Africa
## Project Overview
This project seeks to understand
- How do male and female labor force participation rates differ across global regions, and which regions exhibit the largest gender disparities?
- How have employment rates for men and women changed over the past two decades, and if gender differences shrinking or widening over time?
- How do economic factors like unemployment, sector type, relate to employment levels for men and women?
- Also, in recent years what is the trend of employment and unemployment in Sub-Saharan Africa.
---

## Data Source
- Dataset obtained from the publicly available dataset from the World Bank Gender Data Portal (Gender Stats CSV).
- Dataset contains annual indicators from 1960 to 2024.

Key variables include:
- Labor force participation rate, female (% of female population ages 15+)
- Labor force participation rate, male (% of male population ages 15+)
- Employment to population ratio, 15+, male (%) 
- Employment in agriculture, female (% of female employment) 
- Employment in agriculture, male (% of male employment) 
- Employment in industry, female (% of female employment) 
- Employment in industry, male (% of male employment) 
- Employment in services, female (% of female employment)
- Employment in services, male (% of male employment) 
- Unemployment, female (% of female labor force) 
- Unemployment, male (% of male labor force) 
- Income Group
- Regions
- Country Name
- Year   
---

## Methodology
The analysis employs the following statistical approaches:
- The data was filtered to only include values from the selected indicators (Labor Force, Employment, Employment by sector, and Unemployment) which was based on the objectives of this study.
- The data which was originally in a wide format with separate columns for years was reshaped to a long format, which would allow us to perform our intended visualizations.

All visualizations used in this project was produced using **Python**. The following tools and libraries were used to obtain the visualizations
- Pandas: This was used for the data cleaning, transformation, filtering for specific indicator to use from the world bank data, creating the time-series structure for the dataset and computing averages across regions.
- Matplotlib: This library allows us to create a customizable chart, heatmaps, and some multi-panel plots. We also employed this library in setting our figure sizes (plt.figure), add titles (plt.title), axes labels (plt.xlabel, plt.ylabel), control layouts (plt.tight_layout), add data sources (plt.figtext), and save figures (plt.savefig).
- Seaborn: used to create the visualization
---

## Files in This Repository
- 'Unemployment_Employment_Report.pdf' - Journal Style pdf report that contains visualizations and report 
- `Unemployment_Employment.ipynb` – Python Code
-  images of the different result in png  
- `README.md` – Project documentation  

---

## Reproducibility
To reproduce the analysis:
1. Install required packages as inclded in the code
2. The code directly downloads the data from the website
2. Run the code

---
## Author
**Oluwafunmibi Omotayo Fasanya** 

PhD Student, Biostatistics and Data science

Louisiana State University Health Sciences Center, New Orleans 



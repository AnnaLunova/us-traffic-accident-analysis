# US Traffic Accident Data Analysis

## Project Overview

This project analyzes the US Accidents dataset to identify patterns related to traffic accident timing, location, severity, weather conditions, and accident duration. The goal is to develop data-driven insights that could help a Department of Transportation audience make better decisions about road safety, resource allocation, and accident prevention.

The analysis follows a structured data science process that includes data understanding, data preparation, exploratory data analysis, statistical testing, dashboard development, and business recommendations.

## Business Problem

Traffic accidents create major public safety, economic, and infrastructure challenges. Transportation agencies need to understand when and where accidents occur most often, which factors may be associated with accident severity, and how safety resources can be prioritized effectively.

This project focuses on answering the following business questions:

- When do traffic accidents occur most often?
- Which states and cities have the highest accident counts?
- How are accident severity and duration distributed?
- Are there differences between daytime and nighttime accident patterns?
- What recommendations can help reduce accidents and improve road safety?

## Dataset

This project uses the US Accidents dataset from Kaggle.

Dataset source: [US Accidents Dataset - Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)

Note: The raw dataset file is large and may not be included directly in this repository. It can be downloaded from Kaggle using the link above.

## Tools and Libraries Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Tableau
- GitHub

## Project Files

- `DS_Capstone_Notebook.ipynb` - Main Jupyter Notebook containing the full analysis
- `traffic_banner.jpg` - Banner image used in the notebook
- `README.md` - Project overview and documentation
- Tableau Dashboard Link - Included in the notebook and below when published

## Analysis Summary

The analysis found several important patterns in the traffic accident data:

- Accidents are most common during weekday commute hours, especially around 7-8 AM and 4-5 PM.
- Accidents occur more often on weekdays than weekends, with Friday showing the highest accident count.
- Accident volume is concentrated in certain states and cities, including California, Florida, Texas, Houston, Miami, and Los Angeles.
- Most accidents are classified as Moderate severity.
- Nighttime accidents have longer average duration than daytime accidents, suggesting possible challenges with visibility, incident detection, or response planning.
- Statistical testing showed significant relationships between accident severity, daylight status, and accident duration, although some numeric relationships were weak and should not be interpreted as direct causation.

## Key Recommendations

1. **Target weekday commute-hour safety interventions**  
   Focus safety efforts during high-risk commute periods, especially around 7–8 AM and 4–5 PM. Potential KPIs include reducing commute-hour accident counts, lowering average incident duration, and tracking before/after changes in targeted corridors.

2. **Prioritize high-volume accident locations for local safety reviews**  
   Use high-count states and cities as starting points for deeper local analysis. Because the location analysis uses raw accident counts, future work should normalize by population, traffic volume, or vehicle miles traveled before making major infrastructure decisions.

3. **Improve nighttime visibility and incident response planning**  
   Review nighttime accident hotspots and consider improvements such as lighting, reflective lane markings, incident detection, and emergency response coordination. Potential KPIs include reducing average nighttime accident duration and improving incident clearance time.

## Tableau Dashboard

The interactive Tableau dashboard for this project can be viewed here:

[US Traffic Accident Analysis Dashboard](https://public.tableau.com/app/profile/anna.lunova/viz/USTrafficAccidentAnalysisDashboard_17814932002320/USTrafficAccidentDashboard?publish=yes)

## How to Use This Repository

1. Open `DS_Capstone_Notebook.ipynb` in Jupyter Notebook or VS Code.
2. Download the dataset from Kaggle if the raw data file is not included.
3. Run the notebook cells in order.
4. Review the analysis, visualizations, statistical tests, and recommendations.
5. Open the Tableau dashboard link to explore the interactive dashboard.

## Limitations

- The dataset is observational, so the analysis can identify patterns and relationships but cannot prove direct causation.
- Some fields in the original dataset contain missing values and required cleaning.
- The 2023 data may not represent a full year, so yearly comparisons involving 2023 should be interpreted carefully.
- Accident counts by state or city may be influenced by population size, traffic volume, reporting practices, and road network size.

## Author

Prepared by Anna Lunova

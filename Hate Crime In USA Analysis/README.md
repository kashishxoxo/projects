# Hate Crime in the USA - Data Analysis & Visualization

## Overview

This project presents a comprehensive data analysis of hate crimes reported across the United States. The goal is to explore patterns, demographic correlations, and state-level trends in hate crime incidents. By leveraging both Python-based Exploratory Data Analysis (EDA) and a Power BI dashboard, the project provides data-driven insights that can assist policymakers, sociologists, and the general public in understanding the scope and impact of hate crimes.

## Objectives

- Analyze state-wise hate crime rates and reporting patterns.
- Identify key demographic and socio-economic indicators related to hate crime prevalence.
- Uncover correlations between variables such as income, education, and hate crime rates.
- Visualize trends through interactive dashboards.

## Dataset Description

The dataset (`hate_crime-csv-2-csv.csv`) was sourced from open government and nonprofit databases and contains metrics related to hate crimes and state-level demographics. Key variables include:

| Column Name                  | Description                                                             |
|------------------------------|-------------------------------------------------------------------------|
| state                        | U.S. state name                                                         |
| median_household_income      | Median income per household                                             |
| share_unemployed_seasonal    | Seasonal unemployment rate                                              |
| share_population_in_metro    | Share of state population in metropolitan areas                         |
| share_non_citizen            | Percentage of non-citizens in the population                            |
| share_white_poverty          | Percentage of white population in poverty                               |
| share_non_white              | Share of non-white population                                           |
| share_vote_trump             | Share of 2016 votes for Donald Trump                                    |
| hate_crimes_per_100k_fbi     | Reported hate crimes per 100,000 population (FBI data)                  |
| avg_hatecrimes_per_100k_fbi  | 3-year average of hate crimes per 100,000 population (FBI)              |

*Note: Some values may be missing or estimated depending on state reporting standards.*

## Analytical Focus Areas

### Demographic Impact

- Relationship between hate crime rate and income levels
- Correlation with non-citizen and non-white population percentages
- Educational attainment and employment rate analysis

### Political and Geographic Trends

- Hate crime incidence in relation to 2016 voting data
- Comparison of metro vs non-metro population shares
- State-wise comparison and ranking based on hate crime metrics

## Methodology

1. **Data Cleaning**
   - Handled missing values and ensured consistent data types
   - Renamed and reformatted columns for readability

2. **Exploratory Data Analysis**
   - Generated correlation heatmaps and pairplots
   - Performed descriptive statistics and visual summaries
   - Analyzed key variable relationships using scatter plots and bar charts

3. **Feature Engineering**
   - Created regional categorizations
   - Computed z-scores for crime rate deviation analysis

4. **Visualization**
   - Developed a Power BI dashboard to represent:
     - Hate crime intensity across states
     - Influencing demographic variables
     - Interactive comparison of top and bottom states

## Power BI Dashboard

The Power BI dashboard (`HateCrime in USA.pbix`) includes:

- State-wise hate crime map
- Filters for demographic variables
- Bar and line charts for trend analysis
- Visual comparison between different socio-political factors

## Tools & Technologies

- **Python (Jupyter Notebook)** – Data cleaning, transformation, and EDA
- **Pandas, NumPy, Seaborn, Matplotlib** – Statistical analysis and visualization
- **Power BI** – Interactive dashboard creation and reporting

## Files Included

- `hate_crime.ipynb` – Jupyter Notebook with EDA code and insights
- `hate_crime-csv-2-csv.csv` – Dataset containing hate crime and demographic data
- `HateCrime in USA.pbix` – Power BI dashboard for interactive exploration

## Conclusion

The analysis reveals that hate crime reporting and intensity vary significantly across states and are influenced by a combination of demographic, economic, and political factors. The insights gained can help in:

- Identifying high-risk areas for targeted policy response
- Understanding correlations between social factors and hate crime prevalence
- Supporting awareness and prevention campaigns with data-backed findings

This project demonstrates how public data can be turned into powerful insights through structured analysis and visualization.


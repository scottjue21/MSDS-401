# COVID-19 Analysis in EU/EEA Countries

## Overview

This project is an exploratory data analysis of daily new COVID-19 cases and deaths in countries across the European Union (EU) and European Economic Area (EEA). The analysis was part of the final exam for the MSDS 401 course, focusing on key statistical techniques for understanding the pandemic’s impact. The project involves data manipulation, visualization, hypothesis testing, correlation, and regression analysis.

The dataset used for the project contains daily case and death statistics, sourced from the [European Centre for Disease Prevention and Control (ECDC)](https://www.ecdc.europa.eu/en/publications-data/data-daily-new-cases-covid-19-eueea-country).

## Project Objectives

The project was divided into four primary tasks:

1. **Exploratory Data Analysis (EDA):**
   - Calculate incidence and fatality rates for each country (cases/deaths per 100,000 individuals).
   - Visualize trends in daily COVID-19 cases and deaths across multiple EU/EEA countries.
   - Explore case fatality rates to understand the relationship between total cases and deaths.

2. **Hypothesis Testing:**
   - Compare COVID-19 incidence rates between two countries using statistical hypothesis testing.
   - Use visualizations and a two-sample t-test to determine whether there is a significant difference in the incidence rates between the selected countries.

3. **Correlation Analysis:**
   - Investigate the correlation between incidence rates and fatality rates across all countries.
   - Select and justify the most appropriate correlation coefficient for this relationship.

4. **Linear Regression Modeling:**
   - Fit a linear regression model to assess the relationship between total new cases and factors like population, population density, and GDP per capita across 20 selected countries.

## R Packages Used

- **ggplot2**: For creating various plots and visualizations.
- **dplyr**: Data manipulation and transformation.
- **Hmisc**: Statistical analysis.
- **rockchalk**: Hypothesis testing and regression modeling.

## Key Insights

1. **EDA Results:**
   - Incidence and fatality rates vary significantly across EU/EEA countries, with some countries exhibiting higher case and death trends.
   - Case fatality rates suggest varying degrees of severity of the pandemic's impact across different regions.

2. **Hypothesis Testing:**
   - A two-sample t-test comparing Spain and Finland’s daily incidence rates showed statistically significant differences between the two countries.

3. **Correlation Analysis:**
   - A moderate positive correlation was found between incidence and fatality rates, indicating that countries with higher incidence rates often experience higher fatality rates.

4. **Regression Analysis:**
   - Population, population density, and GDP per capita were found to be significant predictors of the total new cases across the selected countries.

## Data

The dataset used in this project is publicly available from the European Centre for Disease Prevention and Control (ECDC) and can be accessed [here](https://opendata.ecdc.europa.eu/covid19/nationalcasedeath_eueea_daily_ei/csv).

A data dictionary for the dataset is available [here](https://www.ecdc.europa.eu/sites/default/files/documents/Description-and-disclaimer_daily_reporting.pdf).

## Conclusion

This project provided valuable insights into the impact of COVID-19 in the EU/EEA region, showcasing the power of data analysis techniques in understanding complex phenomena such as a global pandemic.

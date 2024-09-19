# Data Analysis Project 1: Exploratory Data Analysis of Abalone Dataset

This project involves an exploratory data analysis (EDA) of abalone data to identify potential reasons why a previous study failed to accurately predict abalone age using physical measurements. The dataset contains observations from an abalone study conducted in Tasmania, with variables such as length, diameter, height, weight, and ring count (used to estimate age). The objective of this project is to analyze the data, derive meaningful insights, and assess whether the physical characteristics of abalones can be reliably used to estimate their age.

### Project Objectives:
1. Perform exploratory data analysis (EDA) on the abalone dataset.
2. Visualize the data to identify relationships between variables.
3. Investigate why predicting abalone age based on physical characteristics was unsuccessful in the original study.

### Dataset:
- **abalones.csv**: This dataset contains 1,036 observations of abalone from a study conducted in Tasmania. It includes variables such as sex, length, diameter, height, weight, and age (rings).

### Key Variables:
- **SEX**: M (male), F (female), I (infant)
- **LENGTH**: Longest shell length (cm)
- **DIAM**: Diameter perpendicular to length (cm)
- **HEIGHT**: Height perpendicular to length and diameter (cm)
- **WHOLE**: Whole weight of abalone (grams)
- **SHUCK**: Shucked weight of meat (grams)
- **RINGS**: Number of rings (age in years = rings + 1.5)
- **CLASS**: Age classification based on RINGS (A1 = youngest, A6 = oldest)

### Additional Features:
- **VOLUME**: Overall size of abalone (calculated by multiplying LENGTH, DIAM, and HEIGHT).
- **RATIO**: Proportion of meat in abalone (calculated by dividing SHUCK by VOLUME).

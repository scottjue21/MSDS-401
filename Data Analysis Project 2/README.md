# Data Analysis Project 2 Overview

This project involves statistical inference using the abalone dataset. The primary focus is on developing a regression model to predict the age of abalone based on physical measurements, and evaluating binary decision rules. Additionally, a Receiver Operating Characteristic (ROC) curve will be constructed to assess model performance.

### Project Objectives:
1. Develop a linear regression model to predict abalone age.
2. Perform statistical inference using analysis of variance (ANOVA).
3. Evaluate binary decision rules based on classification thresholds.
4. Construct and analyze an ROC curve to measure the classification accuracy.

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

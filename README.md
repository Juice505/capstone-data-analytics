# capstone-data-analytics
Final Capstone Project for Data Analytics Course
Violent Crime Analysis in Maricopa County (2017-2025) Specifically the Phoenix Police Department
Author: Tyler Arias

Overview
This project analyzes violent crime trends in Phoenix, Arizona using public arrest data from the Arizona Department of Public Safety (AZDPS). The analysis explores demographic patterns, gender differences and time-based crime trends. The project also uses predictive modeling, to forecast crime rates up to 2030 and multiple statistical and machine learning techniques. The purpose of this project is to understand historical crime patterns, evaluate demographi disparities, and provide actionable insights for public policy.

Navigating the Repository
Raw Folders: These folders contain the original data before filtering / combining that I used for this project.
2017_2025_combined.csv: Is the combined file after executing the combining_data script used for analysis.
Violent_Crime_Power_BI_Visuals: Provides a visualization of the combined csv file.
analyzing_data: This file provides further insight / analysis structured with by the research questions asked and followed with visuals.

Research Questions
1. Are people of a certain race more likely to commit crime?
2. Is there a difference in violent crime arrests between male and female over time?
3. Have violent crimes increased or decreased from 2017 to 2025?

Data Source
All data was obtained from:
Arizona department of Public Safety Crime Statistics
https://azcrimestatistics.azdps.gov/tops

Technologies Used
Python 3.x
Pandas - data cleaning and manipulation
Matplotlib / Seaborn - data visualization
Statsmodels - linear regression, ordinary least squares (OLS) tests, ARIMA
Scikit-learn - polynomial regression

Key Findings
Gender: Males had significantly higher violent crime arrest totals than females across all years.
Race: Significant differences exist across racial groups in arrest rates.
Trend (2017-2025): Crime increased through 2021 but then sharply declined by 2025.
Forecast: ARIMA predicts that crime will stabilize around 10,900 arrests per year through 2030.

Citation
Arizona Department of Public Safety. (2025). Arizona Crime Statistics. https://azcrimestatistics.azdps.gov/tops

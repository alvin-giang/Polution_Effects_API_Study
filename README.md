<<<<<<< HEAD
as
=======
# Project 1: Clearing the Air
Group 5 - Alvin, Fatema, Bradley and Wendy

## Introduction
This project, "Clearing the Air," aims to investigate the relationships between air pollutants and various health and environmental factors. The project focuses on four main hypotheses:

1. Relationship between Population and Air Pollution
2. Relationship between Seasonal Variations and Air Quality Index
3. Investigating the Relation between Air Pollutants and Respiratory Deaths
4. Investigating the Relation between Air Pollutants and Mental Health

By analyzing these relationships, we aim to gain insights into the impact of air quality on respiratory health, mental health, and overall well-being.

## Hypotheses

1. **Relationship between Population and Air Pollution**:
   - This hypothesis examines the relationship between population density and air pollution levels to identify potential patterns and trends in urban areas.

2. **Relationship between Seasonal Variations and Air Quality Index**:
   - This hypothesis focuses on analyzing seasonal variations in air quality index values to determine how air pollution levels fluctuate throughout the year.

3. **Investigating the Relation between Air Pollutants and Respiratory Deaths**:
   - This hypothesis aims to analyze the correlation between different air pollutants and respiratory-related deaths to understand the potential health risks associated with poor air quality.

4. **Investigating the Relation between Air Pollutants and Mental Health**:
   - This hypothesis explores the potential link between air pollutants and mental health issues, investigating how air quality may impact psychological well-being.

## Methodolody 
### Data Collection
The project utilizes data from various sources, including but not limited to:

    - OpenWeatherMap API

    - [Kaggle](https://www.kaggle.com/)

    - Australian Bureau of Statistics

    - WHO Global Health Observatory

    - Citify

    - Geoapify

    - World Air Quality Index API

    - Ninja API


### Data Pre-processing
The collected data underwent pre-processing to ensure consistency and suitability for analysis. This involved steps such as data cleaning to remove missing or erroneous entries, standardization of data formats, and alignment of data across years and countries. 


### Correlation Analysis
The quantitative analysis involved the use of inferential statistics, specifically correlation analysis, to identify the relation between air pollution levels and various health and environmental factors. Pearson correlation coefficients were then calculated to quantify the strength and direction of the linear relationship between those variables.
Additionally, descriptive statistics, specifically T-test were utilized to compare air quality levels between urban and rural regions in Australia. Beside that, Anova-test also were used to anazlyse the difference between the means of air pollution levels across four seasons.

### Visualization
Scatter plots were generated to visually represent the relationship between air pollutants and various health and environmental factors. Separate plots were created for each pollutants showing how they were influnce by population size or seasonal variations. Linear regression lines were fitted to the scatter plots to illustrate the trend between environmental and health factor, and air quality index.

### Data Filtering
To ensure the robustness of the analysis, data filtering was applied to remove potential outliers or data points that could skew the results. Entries with excessively high air pollutant concentrations or unusually low or high respiratory health issues rates were excluded from the analysis.

### Analysis Outcomes
#### Enviromental factors
The analysis reveals that the correlation between monthly air quality parameters (CO, O3, NO2, SO2, PM2.5, and PM10) and the population density fall within the range of -0.3 to 0.3, indicating a weak linear relationship between the population density and the air pollution levels. This suggests that changess in population density are not strongly associated with changes in the air quality index.

Regarding to Urban and Rural comparision, the analysis reveals that the P-values between 5 over 6 key pollutants are less than 0.05, which indicates that there is a significant difference between the monthly air quality parameters in urban and rural areas. Therefore, the hypothesis was supported and confirmed.

#### Health/Wellbeing factors

Data included the concentration of PM2.5, PM10, and NO2, measured in the micrograms (one-millionth of a gram) per cubic meter. The skewness of that data was as follows: PM2.5 = 1.23, PM10 = 0.91, and NO2 = 0.67. The data for prevalence of despressive mental disorders per country per year was measured as the number of cases reported in the location's population, and percent prevalence was calculated. The skewness was as follows: Number of Cases: 1.76, and Percent Prevalence: -0.34.

The countries with the highest concentration of air pollution were Mongolia, China and Bangladesh. The countries with the lowest concentration of air pollution were Estonia, Finland, and Iceland.

As PM2.5 is considered the most dangerous particle in terms of detrimental health effects, this element was focused on for the purposes of considering correlation between depressive disorders and air pollution. The scatter plot for the data indicated that the correlation coefficient between the elements of air pollution and depressive disorders was -0.26. This suggests that higher pollution levels may be linked to fewer reported cases, possibly due to underdiagnosis in more polluted areas. This finding tracks logically, when considering what we know about the world: often, the highest polluted areas with the highest population density have the least reliable and consistent access to a comprenhensive healthcare system.

The correlation analysis revealed consistent positive correlations between air pollutant concentrations (NOx, SO2, CO, NH3) and respiratory mortality rates (lower respiratory infections and chronic respiratory diseases) across multiple years. Higher pollutant concentrations were associated with increased respiratory mortality rates, highlighting the detrimental effects of air pollution on respiratory health. These findings underscore the importance of implementing effective pollution control measures and public health interventions to mitigate the adverse impact of air pollution on respiratory diseases

### Limiatations
#### Data Comparability 
The WHO data was of a limited comparability between countries due to the omission of some data. This was cited as being due to "language issues or limited accessibility". This translated into a challenge in finding a time period where an adequate number of countries reported on all air pollutant metrics for a number of years.

#### Sample/Socioeconomic Bias
In terms of the Global Burden of Disease study, the subnational locations with available data for query were largely very developed countries, indicating that there may be a sample bias. Also, the study did have sociodemographic index groupings, but did not provide detailed information about which country belonged to which index group. This made it impossible to acount for the socioeconomic element bias if one was present.

#### Limited temporal scope
A one-year timeframe may not capture long-term trends, resulted in certain trends or patterns that occur over longer periods maybe missed.

#### Limited spatial scope 
Focusing solely on data collected in Australia may limnit the generalizability of the findings to other regions or countries. The specific characteristics of Australia may not be representative of global trends. Australia's unique characteristics, including its low population density, stringent environmental regulations, and geographic location, contribute to its notably superior air quality compared to many other countries. Therefore, using Australia as the sample country may introduce sample bias for this study.

### References
1. Australian Bureau of Statistics (2021) Regional Population. Available at https://www.abs.gov.au/statistics/people/population/regional-population/latest-release
2. World Health Organization. WHO Air Quality Database (Update 2022). Available at https://www.who.int/data/gho/data/themes/air-pollution/who-air-quality-database
3. Global Burden of Disease Collaborative Network. Global Burden of Disease Study 2019 (GBD 2019) Population Estimates 1950-2019. Seattle, United States of America: Institute for Health Metrics and Evaluation (IHME), 2020. Available at https://vizhub.healthdata.org/gbd-results/
>>>>>>> 1db1b08 (done)

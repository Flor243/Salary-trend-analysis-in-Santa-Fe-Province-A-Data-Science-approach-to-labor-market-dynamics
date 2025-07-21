# Salary Trend Analysis in Santa Fe Province: A Data Science Approach to Labor Market Dynamics

## Overview
This project conducts a comprehensive analysis of salary trends in Santa Fe Province, Argentina, focusing on the relationship between wages, economic sectors, and regional characteristics. Using data from 2014-2022, the analysis examines salary evolution across different economic activities and geographic areas within the province.

## Research Objectives
- Analyze salary behavior over time in Santa Fe Province by economic sector
- Identify the most representative economic activities in the region
- Investigate the relationship between salary levels, population density, and geographic location
- Develop predictive models for salary trends using linear regression

## Key Findings
- **Manufacturing Industry** and **Wholesale & Retail Commerce** are the most representative economic sectors in Santa Fe Province
- Salaries show seasonal patterns due to mandatory bonus payments (SAC - Sueldo Anual Complementario)
- When converted to USD, salaries show a general declining trend over the analyzed period
- Population density levels correlate with salary ranges across different departments
- Linear regression models explain approximately 35.4% of salary variability

## Dataset
The analysis utilizes multiple datasets from official Argentine sources:
- **Primary Dataset**: Average salaries by department/region and economic sector (monthly frequency, 2014-2022)
- **Supporting Datasets**: 
  - Employment and establishment data by department and activity
  - Population census data (2010, 2022)
  - USD exchange rates from Central Bank of Argentina (BCRA)
  - Monthly inflation rates

### Data Sources
- Datos Argentina (datos.gob.ar)
- INDEC (National Institute of Statistics and Censuses)
- Central Bank of Argentina (BCRA)

## Methodology

### Data Preprocessing
- Handling missing values and outliers
- Currency conversion (ARS to USD) using BCRA exchange rates
- Seasonal adjustment for mandatory bonus payments
- Data normalization and feature engineering

### Exploratory Data Analysis
- Statistical summaries and distribution analysis
- Time series visualization
- Correlation analysis between variables
- Geographic and sectoral comparisons

### Modeling Approach
- Linear regression with multiple explanatory variables:
  - Time trends
  - Economic sector classification
  - Population density levels
  - Inflation rates

## Technical Implementation

### Tools & Libraries
- **Python** for data analysis and modeling
- **Pandas** for data manipulation
- **Matplotlib & Seaborn** for visualization
- **Statsmodels** for regression analysis
- **Scikit-learn** for data preprocessing

### Key Features
- Comprehensive data cleaning pipeline
- Multi-dimensional exploratory analysis
- Statistical modeling with variable significance testing
- Model validation and performance evaluation

## Results Summary
1. **Sector Analysis**: Manufacturing and commerce sectors dominate employment in Santa Fe
2. **Geographic Insights**: Higher population density correlates with better salary levels
3. **Temporal Trends**: Despite nominal increases, real wages (in USD) declined over the study period
4. **Predictive Modeling**: Inflation emerges as the most significant predictor of salary variations

## Future Work
- Incorporate additional economic indicators
- Explore non-linear modeling approaches
- Extend analysis to other Argentine provinces
- Develop real-time salary prediction dashboard

## Academic Context
This project was developed as part of a Data Science Fundamentals course, demonstrating practical application of statistical analysis, data visualization, and predictive modeling techniques to real-world economic data.

---

**Note**: All analysis focuses on formal employment data from the private sector and public companies, providing insights into registered labor market dynamics in Santa Fe Province.

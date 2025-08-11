# Racial Disparities in Arrests — United States, 2020

## 📌 Project Overview
This project analyzes the **2020 arrest data** from the U.S. Office of Juvenile Justice and Delinquency Prevention, focusing on racial disparities across violent crimes, property crimes, and drug-related offenses. Using visual storytelling, statistical modeling, and predictive analysis, the study challenges societal stereotypes, exposes systemic bias, and advocates for equitable policy reforms.

## 📂 Dataset Information
- **Source:** Office of Juvenile Justice and Delinquency Prevention (U.S. Department of Justice)  
- **Year:** 2020  
- **Format:** CSV (cleaned for numeric consistency, missing values removed)  
- **Categories:**  
  - Violent Crime Index: Murder, rape, robbery, aggravated assault  
  - Property Crime Index: Burglary, larceny-theft, motor vehicle theft, arson  
  - Drug-related crimes and other offenses  

## 📊 Methods & Analysis
1. **Data Cleaning & Preprocessing**  
   - Removed commas from numeric fields  
   - Converted values to integers  
   - Dropped incomplete rows  
   - Aggregated arrest counts by race and offense category  
2. **Visualization Techniques**  
   - Histograms for arrest frequency  
   - Scatter plots for offense correlation  
   - Donut & pie charts for proportional comparisons  
   - Area charts for crime distribution  
   - SARIMA forecast modeling for 2010–2030 arrest trends  
3. **Statistical Modeling**  
   - **SARIMA:** Forecasts persistent disparities in arrest trends without convergence  
   - **Linear Regression:** Poor fit (R² = -0.0831) due to limited features  
   - **Random Forest:** Slightly improved but still weak predictive performance (R² = -0.0347)  

## 📌 Key Findings
- **Disproportionate Arrest Rates:**  
  - Black individuals: 26% of total arrests vs. 13% of population  
  - White individuals: Highest total arrests (70%), aligned with population share but masking systemic focus on minorities  
  - American Indians & Asians: Low arrest counts but still subject to stereotypes  
- **Offense Leadership by Race:**  
  - African Americans: Higher involvement in violent offenses  
  - Whites: Majority in property crimes and inter-racial offenses  
  - American Indians: Low substance abuse-related arrests (2.4%)  
  - Asians: Lowest arrest rates (1.6%)  
- **Predicted Trends:**  
  - Arrest disparities projected to persist through 2030 without systemic reform  

## ⚖️ Ethical Considerations
- Avoided reinforcing stereotypes by contextualizing data with socioeconomic and systemic factors  
- Transparent methodology to prevent misinterpretation  
- Advocacy-driven presentation aimed at policymakers, social movements, and communities  

## 🛠 Tools & Technologies
- **Python**: Pandas, Matplotlib, Seaborn, Statsmodels, Scikit-learn  
- **Jupyter Notebook** for analysis & visualization  
- **SARIMA** for time series forecasting  
- **Random Forest & Linear Regression** for exploratory prediction  

## 🚀 Potential Future Work
- Extend dataset across multiple decades for trend consistency analysis  
- Explore regional policing strategies and socioeconomic correlates  
- Integrate qualitative data (court outcomes, sentencing disparities) for deeper insight  

**Author:** Darious Brown  
**Year:** 2025  

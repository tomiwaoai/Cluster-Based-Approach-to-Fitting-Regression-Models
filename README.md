# Cluster-Based-Approach-to-Fitting-Regression-Models

### Project Objectives

- To inspect the efficacy of the features included in the data set for the improvement of average lifespan of the countries.
  
- To determine whether there are better ways to group countries other than developed and undeveloped for the purpose of modeling life expectancy.
  
- To build predictive models that emphasize potential factors which could significantly improve the life expectancy of a population.

### Data Description

Data was retrieved from the World Health Organization’s (WHO) website and consists of health data from 180 countries. 
Our variables include: 

1. Healthy life expectancy (HALE) at birth (years)
   
2. Adult Mortality – mortality rate per 1000 people aged 15-60

3. Infant Deaths – Infant mortality rate (between birth and 11 months per 1000 live births)

4. Alcohol – Recorded alcohol consumption (ages 15+) per capita in liters of pure alcohol

5. Percentage Expenditure – Domestic general government health expenditure (GGHE-D) as a percentage of general government expenditure (GGE) (%)

6. Hepatitis B – Hepatitis B (HepB3) immunization coverage among 1-year-olds (%)

7. BMI – Mean body mass index trends among adults, crude (kg/m²)

8. Polio – polio (Pol3) immunization coverage among 1-year-olds (%)

9. Total expenditure – Domestic general government health expenditure (GGHE-D) as a percentage of gross domestic product (GDP) (%)

10. Diphtheria – diphtheria tetanus toxoid and pertussis (DTP3) immunization coverage among 1-year-olds (%)

11. HIV/AIDS – deaths per 1000 live births with HIV/AIDS (0-4 years)

12. Thinness 5-19 years – prevalence of thinness among adolescents age 5 to 19, BMI < -2 standard deviations below the median (crude estimate) (%)

### Methodology

Employed Python, leveraging libraries such as scikit-learn, pandas, and matplotlib, to develop these classes. The focus was on creating user-friendly and flexible tools that cater to both novice and experienced data scientists.Methodlogy steps include:

- Literature review

- Leave one out cross validation

- KNN algorithm

- Model-based clustering

- Experiments and results
  
### Findings and Conclusion

Countries belonging to cluster 1 and cluster 2 were mostly countries with strong socio-economic status. So, naturally, the problems affecting life expectancy in these countries are different than the countries belonging to clusters 3 and 4, which represent the underprivileged countries. For instance, we noticed the risk of HIV is not on par with the risk in developed countries. We also noticed BMI and Alcohol were significant factors that could affect the life expectancy of the population in developed countries.

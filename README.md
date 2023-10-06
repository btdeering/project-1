# Covid-19 Report

## Factors Contributing to COVID-19 Deaths: A Comprehensive Data Analysis

Introduction

This repository contains data and analysis on the relationship between COVID-19 mortality rates, obesity rates, and respiratory death rates in the United States. The data was cleaned and prepared using Excel, and the analysis was performed using Jupyter notebooks.

Data Cleaning

The data used in this analysis was sourced from publicly available datasets. To ensure accuracy and consistency, the data was cleaned and prepared using Microsoft Excel. This involved removing irrelevant data, filling in missing values, and converting data types where necessary.

Visualization and Analysis

The cleaned data was then imported into Jupyter notebooks where it was visualized and analyzed using various Python libraries such as Pandas, Matplotlib, and Linregress. The analysis focused on exploring the relationship between COVID-19 mortality rates, obesity rates, and respiratory death rates.


Analysis of COVID-19 Death Rates vs Heart Disease Death Rates per State
* The scatter plot of COVID-19 Death Rate vs Heart Disease Death Rate per State shows a positive relationship between the two variables, with a linear regression line y=0.25x + 35.65 and a correlation coefficient r = 0.28.
* The equation of the linear regression line indicates that there is a positive correlation between the Heart Disease Death Rate and the COVID-19 Death Rate. For each one-unit increase in the Heart Disease Death Rate, there is a predicted increase of 0.25 units in the COVID-19 Death Rate. The intercept of the line (35.65) suggests that even in states with a low Heart Disease Death Rate, there is still a predicted COVID-19 Death Rate of around 36.
* The correlation coefficient r = 0.28 suggests a weak positive correlation between the two variables. This means that there is a positive relationship between the Heart Disease Death Rate and the COVID-19 Death Rate, but it is not very strong.
* In conclusion, the scatter plot of COVID-19 Death Rate vs Heart Disease Death Rate per State suggests a weak positive relationship between the two variables, with a linear regression line y=0.25x + 35.65 and a correlation coefficient r = 0.28. However, further research is needed to establish a causal relationship between Heart Disease and COVID-19 Death Rates.
Analysis for Covid-19 Death Rates vs Obesity Rates per State 2021
* This analysis looks at the relationship between Covid-19 death rates and obesity rates per state in the year 2021. The data shows a positive correlation between the two variables, indicating that as obesity rates increase, Covid-19 death rates also tend to increase.
* The regression analysis conducted using the data reveals a linear relationship between obesity rates and Covid-19 death rates per state. The equation of the trend line obtained is y=2.54x + -4.55, where y represents Covid-19 death rates and x represents obesity rates. The slope of the line is positive, indicating that there is a direct relationship between the two variables.
* The r-value of 0.33 indicates a weak correlation between the two variables. While the correlation is positive, it is not particularly strong, suggesting that other factors besides obesity rates may be more important in predicting Covid-19 death rates per state.
* Overall, the analysis suggests that there is a positive relationship between obesity rates and Covid-19 death rates per state in 2021, but this relationship is relatively weak. Further research is needed to better understand the complex interplay between obesity rates, other risk factors, and Covid-19 outcomes.
Analysis of Covid Death Rates vs Respiratory Death Rates per State
* The scatter plot of COVID-19 Death Rates vs Respiratory Death Rates per State shows a positive relationship between the two variables.
* The linear regression line indicates that there is a positive correlation between Respiratory Death Rates and COVID-19 Death Rates.
* The correlation coefficient r = 0.41 suggests a moderate positive correlation between the two variables. This means that there is a positive relationship between Respiratory Death Rates and COVID-19 Death Rates, but it is not very strong.
* In conclusion, the scatter plot of COVID-19 Death Rates vs Respiratory Death Rates per State suggests a moderate positive relationship between the two variables, with a linear regression line y = 1.33x + 48.63 and a correlation coefficient r = 0.41. However, further research is needed to establish a causal relationship between Respiratory Death Rates and COVID-19 Death Rates.

Voting vs Covid

* Using election data states that voted for Joe Biden the most and states that voted for Donald Trump the most were separated into two groups. Those two groups' Covid death rates were compared using a two-sample t-test. The t-test shows no connection between covid death rates and political affiliation.

Demographics vs Covid

* A scatterplot was created for education attainment such as high school only, bachelor's degree only, and master's only vs the Covid death rate. The correlation between education and death rate was weakly correlated. As for the demographics, a scatterplot was created for Whites, Blacks, Hispanics, and Asians vs the Covid death rate. The correlation between demographics/ethnicity and Covid death was weakly correlated as well.

Analysis of COVID-19 Death rates vs Population Density

* The COVID-19 Death rates vs Population Density scatter plot shows a weak positive correlation (R = .33) between death rates and population density in 2020. 
* This demonstrates that states with higher density had higher death rates in 2020.  This may be explained by higher population density making it easier for COVID-19 to spread.
* The COVID-19 Death rates vs Population Density scatter plot shows a weak negative correlation (R= -.33) between death rates and population density in 2021.  
* This demonstrates that states with higher density had lower death rates in 2021.  This may be explained by the ease of distributing vaccines in higher density areas.  High density states may also have had more of the population contract COVID-19 in 2020. This may have led to the population having more immunity in 2021.

Analysis of COVID-19 Death rates vs Vaccination Rate

* The COVID-19 Death rates vs Vaccination Rate scatter plot shows a strong negative correlation (R = -.68) between death rates and vaccination rates. 
* This demonstrates that as vaccine rates increase the death rates decrease.  Our research suggests that vaccinations are the strongest factor affecting deaths from COVID-19. In future pandemics, vaccines should play a major role in reducing deaths.

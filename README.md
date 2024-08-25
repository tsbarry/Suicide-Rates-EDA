# Suicide-rates

## Table of Contents 

- [Project Overview](#project-overview)
- [Data Sources ](#data-sources)
- [Tools](#tools)
- [Methodology](#methodology)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis) 
- [Results Findings](#results-findings)
- [Recommendations](#recommendations)
- [Next Action](#next-action)
- [Tableau](#tableau)

## Project Overview 

This project analyzes global suicide rates using data from the World Health Organization (WHO) and other sources. It examines suicide rates by country, gender, age group, and socioeconomic factors to identify patterns, trends, and correlations with variables like GDP, healthcare spending, and population demographics. 

By leveraging data analysis techniques, this project aims to provide actionable insights that can help policymakers, healthcare professionals, and organizations better understand the factors influencing suicide rates and develop targeted interventions to prevent them.

## Data Sources

Data: The primary dataset used for this analysis is the "master.csv" file. This data was retrieved from the WHO.

## Tools

- Pandas: For data manipulation and handling.

- Matplotlib and Seaborn: For data visualization.

- Tableau: For creating interactive and detailed visualizations

## Methodology
In the initial data preparation phase, the following tasks were performed:

- Data loading and inspection.
- Data cleaning, manipulation, and handling of missing values using Python functions and libraries.
- Performed EDA, to uncover patterns, trends, and relationships, and created visualizations to support these findings.

## Exploratory Data Analysis
EDA involved exploring the data to answer key questions such as:

- What are the global trends in suicide rates over time?
  
- How do suicide rates vary by country, gender, and age group?

- What is the suicide rate in the US, and which generation is most affected?
  
- What is the relationship between suicide rates and socioeconomic factors such as GDP and HDI?
  
- Are there specific regions or demographics that show higher vulnerability to suicide?

## Data Analysis
Here are some examples of the visuals from the analyses:

![](image/High_sui_number_USA.jpg) 


The bar graph displays the highest suicide numbers in the USA over the years. It reveals that the Baby Boomers generation had the highest suicide rate in the US for nearly two decades (1996-2009). From 2010 to 2016, Generation X overtook them as the generation with the highest suicide rate in the country. This can be caused by the unique social, economic, and psychological challenges each generation faces. The Baby Boomers experienced significant life transitions and economic pressures as they aged, contributing to higher suicide rates. In contrast, Generation X faced increasing financial stress, career pressures, and the impact of the 2008 economic recession, which likely influenced the rise in suicide rates among this generation from 2010 to 2016.



![](image/nat_high_sui_num.jpg)

![](image/sui_number_country.jpg)


The graphs above show that the Russian Federation, the United States, and Japan have the highest suicide rates. The high rates in Russia can be attributed to the severe economic instability, unemployment, and social upheaval following the Soviet Union's collapse in 1991, as well as high alcohol consumption. In the USA, the elevated suicide rates between 2008 and 2015 were largely driven by the economic recession, rising financial stress, increased mental health issues, and insufficient access to mental health care. For Japan, the economic fluctuations, intense social and workplace pressures, social isolation, and cultural stigma surrounding mental health, can be the factors. 


![](image/sui_number_sex.jpg)

![](image/sui_rate_gen.jpg)


The charts above indicate that males have a significantly higher suicide rate than females, with 77% of suicides committed by males and 23% by females. This can be due to factors such as higher rates of mental health issues among men, societal expectations and pressures, greater use of more lethal methods, and lower likelihood of seeking help compared to women. 



![](image/sui_rate_age.jpg) 

The line plot shows that the suicide rate is significantly high for both males and females in the 35 to 54 age group, followed by the 55 to 74 age group surprisingly. 

![](image/sui_number_gener.jpg)




![](image/HDI_sui_number_USA.jpg)

![](image/avg_sui_year_USA.jpg)

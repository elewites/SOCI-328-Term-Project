# SOCI-328-Term-Project

## Learning Objectives
1. Acquire skills to compile and cleanse data using Excel
2. Learn to identify and construct independent variables, including nominal and continuous, that could potentially explain differences in dependent variables
3. Master techniques to test research hypotheses using quantitative analysis in Excel, such as the `t-test for independent means`, `ANOVA analysis of variance`, `correlation analysis`, and `regression analysis`
4. Develop the ability to evaluate the validity of statistical results by examining evidence from peer-reviewed articles that conduct similar examinations on the variables chosen for this study.


## Main Unit of Measure (Dependent Variable)

For my research, I selected the [Inequality-Adjusted Human Development Index](https://hdr.undp.org/inequality-adjusted-human-development-index#/indicies/IHDI) (IHDI) as the primary unit of measure. The reason behind this choice is that the IHDI offers a comprehensive and nuanced reflection of a country's socio-economic standing, which goes beyond conventional indicators such as income or education levels. By examining the IHDI, I aimed to gain a deeper understanding of the interplay between various factors that contribute to the overall well-being and quality of life of a population.

Furthermore, the IHDI is particularly relevant in the context of addressing inequality, which is a critical issue in contemporary society. By focusing on this measure, I hoped to identify and analyze the specific factors that influence inequality levels in different countries, and to gain insights into potential strategies for mitigating these disparities.

## Independent Variables

The independent variables that I chose to explain the differences in IHDI across countries were
1. *Annual CO2 per capita*:  Carbon dioxide emissions are often used as a proxy for a country's overall environmental impact, as well as its level of economic development. In many cases, countries with higher CO2 emissions per capita are also those with more industrialized and urbanized economies. By including this variable in the analysis, we can better understand the relationship between a country's environmental impact and its socio-economic status, as well as the potential trade-offs between economic growth and sustainability.

2. *Democracy Index*: Political stability and democracy are widely considered to be important indicators of a country's overall well-being and quality of life. By including the Democracy Index as an independent variable, we can examine how political factors such as civil liberties, electoral processes, and government accountability relate to a country's level of human development. 

3. *Corruption Perception Index Corruption*: is a pervasive issue in many parts of the world, and can have significant impacts on a country's economy, political stability, and social well-being. By including the Corruption Perception Index as an independent variable, we can examine how corruption levels relate to a country's level of human development, and how corruption may exacerbate existing social and economic inequalities.


## The Data

The `co2_vs_ihdi_data_compiled_clean` contains 9 worksheets. 
1. `clean data`
2. `codebook`
3. `independent_sample_t_test` results
4. `anova_test` results
5. `correlation_analysis` results & linear regression analysis
6. `human_development_raw_data`
7. `co2_emmissions_raw_data_2021`
8. `democracy_index_raw_data`
9. `corruption_index_raw_data`


## The Analysis 

### Independent Sample T Tests: IHDI & Annual CO2 per capita
- To investigate whether higher CO2 emissions are associated with lower Inequality-Adjusted Human Development Index (IHDI), I performed an independent t-test to compare the IHDI of countries with above-median CO2 emissions to those with below-median emissions. The research question was whether there is a significant difference in IHDI between the two groups, and the median was chosen as the measure of central tendency due to the positively skewed data.

### Anova Analysis: IHDI & Democracy Index
- To investigate whether the quality of governance affects a country's human development, I used the Democracy Index to divide countries into four categories: Full Democracy, Flawed Democracy, Hybrid Regime, and Authoritarian Regime. I then performed an ANOVA test to determine whether there were significant differences in human development means among the four groups.

### Correlation & Regression Analysis: IHDI & Corruption Perception Index
- To explore the relationship between corruption and human development, I used correlation and regression analyses to examine the association between the Corruption Perception Index (CPI) and the Inequality-Adjusted Human Development Index (IHDI), which measures a country's overall human development on a scale from 0 to 1. The CPI measures perceived levels of public sector corruption on a scale from 0 (highly corrupt) to 100 (very clean). I hypothesized that there would be a positive correlation between these variables, indicating that countries with lower corruption levels (higher CPI scores) would have higher levels of human development (higher IHDI scores).

## Results 

 I have included the written results and analysis in the `Final_Assignment_Soci_328.pdf` file.



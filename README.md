# Centranz - Transform US Census Bureau Data to Star Schema

This project uses **Income, Poverty and Health Insurance Coverage in the United States: 2015** report released by _The U.S. Census Bureau_ on SEPT. 13, 2016. These findings are contained in two reports: 
1. Income and Poverty in the United States: 2015 and 
2. Health Insurance Coverage in the United States: 2015.

The Current Population Survey Annual Social and Economic Supplement was conducted nationwide and collected information about income and health insurance coverage during the 2015 calendar year. The Current Population Survey, sponsored jointly by the U.S. Census Bureau and U.S. Bureau of Labor Statistics, is conducted every month and is the primary source of labor force statistics for the U.S. population; it is used to calculate the monthly unemployment rate estimates. Supplements are added in most months; the Annual Social and Economic Supplement questionnaire is designed to give annual, national estimates of income, poverty and health insurance numbers and rates.

Another Census Bureau report, **The Supplemental Poverty Measure: 2015**, was also released. With support from the Bureau of Labor Statistics, it describes research showing a different way of measuring poverty in the United States and includes estimates for numerous demographic groups, including state-level estimates. The supplemental poverty measure serves as an additional indicator of economic well-being and provides a deeper understanding of economic conditions. The Census Bureau has published poverty estimates using this supplemental measure annually since 2011. Since September 2015, the supplemental poverty measure has been released the same day as the official poverty estimates.

In this project we chose to extract data from poverty reports and load the date into MySQL in a star schema format with below mentioned facts and dimensions:

* Fact - Population
* Dimension - Age Band
* Dimension - Disability Status
* Dimension - Education
* Dimension - Family Status
* Dimension - Gender
* Dimension - Nativity
* Dimension - Race
* Dimension - Region
* Dimension - Residence
* Dimension - Work Experience
* Dimension - Year

## Technical Report

Technical Report for this project can be found @ [link](https://docs.google.com/document/d/1JYI1STIVQ8PdSYUSZ7oX1QTD0g1URceNiDNwFFHrVu0/edit?usp=sharing).
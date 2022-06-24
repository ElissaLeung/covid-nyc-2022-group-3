# Final Project

## Elissa Leung and Christopher Esquivel

## June 23, 2022

**Background**

Replication of Figure 1, Figure 2, Table 1 (April 1st) and Table 2 (April 1st) from the article [*Differential COVID-19 case positivity in New York City neighborhoods: Socieconomic factors and mobility*](https://onlinelibrary.wiley.com/doi/epdf/10.1111/irv.12816).

In their article, Matthew R. Lamb, Sasikiran Kandula and Jeffrey Shaman, discuss that socieconomic factors such as the proportion of 18-to 64-year-old population that is uninsured, median household income, proportion of population that self-identified their race as white, proportion of population living in households with more than three inhabitants, proportion of population using public transportation to commute to work that includes bus travel and proportion of population that is eldery, influenced Covid positivity rate. They also considered the daily change in mobility as a factor for Covid positivity rate. They used data from the US Census (ACS) and Safegraph to make these findings.

**Our Project**

In this project, our goal was to replicate their findings and achieve the figures and tables from the article.
+ File containing all the replications [here](http://htmlpreview.github.io/?https://github.com/msr-ds3/covid-nyc-2022-group-3/blob/main/Group_3_Final_Project.html).
+ File containing the code that produced those replications [here](../main/Group_3_Final_Project.Rmd).
  + To use the ACS data provided by tidycensus, users may need to include their own API key using the commented line 19.

All CSV file raw links are provided in the Rmd file and do not need to be predownloaded in order to run the file, however, we attached the links below as well:
+ [NYC Zip Codes](https://raw.githubusercontent.com/erikgregorywebb/nyc-housing/master/Data/nyc-zip-codes.csv)
+ [April 1](https://raw.githubusercontent.com/nychealth/coronavirus-data/097cbd70aa00eb635b17b177bc4546b2fce21895/tests-by-zcta.csv) (cumulative) NYC Covid-19 information
+ [May 1](https://raw.githubusercontent.com/nychealth/coronavirus-data/9e26adc2c475d3378d7579e48e936f8a807b254b/tests-by-zcta.csv) (cumulative) NYC Covid-19 information

**Extended Question**

We decided to choose two counties, Manhattan and Queens, analyze them, and compare them, using the same variables as in the paper. We were interested in seeing what factors influenced Covid positivity rate the most in these two different counties. We added the same graphs as in our replication and developed the best linear model for Manhattan and Queens.

+ File containing the plots and tables [here](http://htmlpreview.github.io/?https://github.com/msr-ds3/covid-nyc-2022-group-3/blob/main/covid_nyc_counties.html).
+ File containing all the code that produced the file above [here](https://github.com/msr-ds3/covid-nyc-2022-group-3/blob/main/covid_nyc_counties.Rmd)

Our conclusions about this extended question can be found here (insert txt file)

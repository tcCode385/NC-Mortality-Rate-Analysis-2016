# NC-Mortality-Rate-Analysis-2016
## A personal data analysis project looking at mortality rate data for North Carolina in the year 2016.

This project consists of three steps:
1. Data aggregation -  
   Files: 2016Mort_dataAggr.html, 2016Mort_dataAggr.Rmd
2. Exploratory analysis -  
   Files: 2016Mort_explorAna.html, 2016Mort_explorAna.Rmd
3. Regression analyses -  
   files: 2016Mort_models_tests.html, 2016Mort_models_tests.Rmd

Data were collected from the CDC Wonder database, http://wonder.cdc.gov/cmf-icd10.html, and the Robert Wood Johnson Foundation's County Health Rankings & Roadmaps, https://www.countyhealthrankings.org/explore-health-rankings/rankings-data-documentation/national-data-documentation-2010-2019.

In the data aggregation step, I pulled out relevant 2016 data and merged it all into one .csv file using the R programming language. In the exploratory analysis, I used R to perform various checks on the data in order to determine which variables I'd like to include in the regression analyses. And in the regression analyses step, I performed some multiple regression analyses, tested for spatial dependence, and performed spatial regression analyses.

Note: 2016Mort_models_tests.html and 2016Mort_models_tests.Rmd are currently in progress.

The .html files may be openned in a browser window and display R code, code output, and descussions of the output/results. The .Rmd files are the R code files.

# Social-Distancing-By-Occupation

## Overview
This project is the setup and execution of an agent-based simulation of social distancing practices using income and occupation as dependent variables. We received data from a range of government sources to inform contextual characteristics of different occupations and control data to inform our model.

## Organization
This project is organized into two jupyter notebooks. `regression.ipynb` retreives regression data  

## Regression
The regressions.ipynb file can calculate regressions on a number of data fields including social distancing data, county income and county
employment. We regress county income and employment controls on social distancing and then implement the coefficient of income into our SEIRS and income model.

## Data
BEA County Employment: https://www.bea.gov/data/employment/employment-by-state \ 
BEA County Income: https://www.bea.gov/data/income-saving/personal-income-county-metro-and-other-areas \
Google Social Distancing Data: https://www.google.com/covid19/mobility/ \
NYT Susceptiblity Data: https://www.nytimes.com/interactive/2020/03/15/business/economy/coronavirus-worker-risk.html \
Department of Labor ONet Job Characteristics and Information: https://www.onetcenter.org/database.html#individual-files \

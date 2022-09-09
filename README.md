# King County Washington



## Overview
Flatiron School Data Science Phase 2 project.

## Business Problem

Edconsult is working with King County, Wa to improve education through winning local school district elections to increase funding for both new buildings and increased teacher pay.

Edconsult needs to demonstrate to the taxpayers / homeowners that in investment in the schools, is an investment in their property value.

## Data Used
data from the following sources can be found in the 'data' folder.

King County Housing Sales 5/2014 - 5/2015
Zipcode and School District data from [proximityone.com](http://proximityone.com/zip-sd.htm)

## School Districts By Zipcode
![school districts and zipcodes](images/overlay.png)

## Deliverables
* [Non-Technical Presentation](https://github.com/ceflynn/dsc-phase-2-project-v2-3/blob/main/pdf/King%20County%20Washington.pdf)
* [GitHub Repository](https://github.com/ceflynn/dsc-phase-2-project-v2-3)
* [Jupyter Notebook](https://github.com/ceflynn/dsc-phase-2-project-v2-3/blob/main/student.ipynb)

## OESMN Framework
Obtain
Scrub
Explore
Model
Interpret

## Model and Regression Results

OLS Model - Ordinar Least Squares Regression


R-Squarred .757  
P-Values of predictors all below our selected alpha(.005)

Our Model can account for roughly 76% of the variance in housing price.

## Client Questions / Answers
### Best Predictors of Price
Square Footage 3% for each additional 100 sq ft Bathrooms 5% for each additional Bathroom Floors 7% for each additional Floor

Non School District Categoric Predictors Being on the waterfront adds 37%
Having an view_EXCELLENT 16%

### How School District Affects Pricte

Mercer Island 90%
Bellevue 79%
Lake Washington: 63%
Seattle: 62%
Issaquah: 54%
Northshore: 47%
Shoreline: 43%
Snoqualmie Valley: 36%
Riverview: 32%
Vashon Island: 30%
Renton: 25%
Tahoma: 15%
Highline: 13%
Kent 7%
Enumclaw: 0
Tukwila: 0
Federeal Way: 0
Fife: 0
Auburn: 0 baseline district

### Which Districts to Target

Snoqualmie Valley, Vashon Island,Riverview,Shoreline, Renton

These districts were in the middle of both of our coefficient rankings and home value rankings.

 
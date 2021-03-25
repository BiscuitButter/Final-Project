# Final-Project

## BACKGROUND 

The Internal Revenue Service's (IRS) county-to-county migration data are an incredible resource for understanding migration in the United States. 
Data for the United States are based on year-to-year address changes reported on individual income tax returns filed with the IRS. They present migration patterns by State or by county for the entire United States and are available for inflows—the number of new residents who moved to a State or county and where they migrated from, and outflows—the number of residents leaving a State or county and where they went.

Produced annually since 1991 in conjunction with the US Census Bureau, making the IRS migration data one of the largest sources of migration data. 

## HYPOTHESIS

The hypothesis is that there is a correlation between the Cost of Living Index and migration flow.   

## EXPERIMENTAL PLAN
By using different sources (see below), we will try to collect and clean up raw data from the past 5 years from the IRS website. 
The data will then be analyzed with different statistical methods in order to understand the relationship between migration flows, age, wages and taxes.
 
 ### Data Sources

Migration patterns obtained from the U.S. Census Bureau

   -County-level data only available for five-year cumulative periods

Cost parameters derived from IRS data
   -Cumulative data based on tax returns published for each tax year based on zip code
   
   -Consolidation of data for tax years 2014 through 2018 necessary to provide an appropriate basis of comparison to the five-year cumulative migration data
   
Additional public information required to finalize database
   -“unitedstateszipcodes.org” provided county location for each zip code
   -County longitude and latitude available through Wikipedia

Here a schematic rapresentation of our work flow.
![image1](/Resources/1.png?raw=true "Title")

## Data Analysis
Data extraction and transformation performed using Python

   -Migration data contained 573 fields for over 70 thousand records
   
   -IRS data consisted of 153 fields for over 27 thousand records
   
Linear regression model developed to test hypothesis

   -Refinements will be based on outcome of initial model
   
Linear regression metrics will be outlined and reviewed

   -Focus on r-squared for overall fit and slope associated with cost of living as test of hypothesis
   
Color-coded maps showing

   -Net migration into (out of) counties
   
   -Local costs


## Results

The results do not support our hypothesis that the migration was influenced by cost of living commonly. Our analysis was done by taking in consideration  data from the 2014 and 2018.
This analysis should be



## OneDrive Link
https://1drv.ms/u/s!AuIV9T8fNEV0kbJZIkGaITz5rzjD3g?e=T7osNj

### Sources
https://www.census.gov/topics/population/migration/guidance.html

https://www.bls.gov/developers/

https://www.unitedstateszipcodes.org/zip-code-database/

https://public.tableau.com/views/IRSmigration/Sheet1?:language=en&:display_count=y&:origin=viz_share_link

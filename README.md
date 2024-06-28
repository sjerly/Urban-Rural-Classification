# Urban-Rural-Classification

**Description and methodological overview available at https://academic.oup.com/aje/advance-article/doi/10.1093/aje/kwae119/7693598?rss=1**

-The variable "UR_Cat" represents a 3 level categorization of censys tracts (0=Rural, 1=Periurban, 2=Urban).  

-The variable "UR_Scale" represents a continuous scale (0-1) representing rurality (0=more rural, 1=more urban)

-GEOID can be used to link the values to census tracts

-The remaining variables represent the data used to derive these values (as described in the linked manuscript).  The variables with the suffix "_t" are transformed and scaled for factor analysis.



**2020 Census Tract Update**
 2020 Census Tracts Uses the Following Data:
 1.) 2020 American Community Survey
 
 2.) 2021 EPA Walkability Score (https://catalog.data.gov/dataset/walkability-index1)
       -Converted from 2010 Census Block to 2020 Census tract via the weighted (by area) mean of walkability score in overlapping regions
       -A special thanks to Dr Lili Manahan for her help with this
       
 3.) 2016-2020 Census Tract PM2.5 Concentrations (https://data.cdc.gov/browse/select_dataset?tags=pm2.5)

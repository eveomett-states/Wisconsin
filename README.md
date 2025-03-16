# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# Wisconsin

This shapefile was processed by Professor Ellen Veomett and her student Ananya Agarwal using the corresponding jupyter notebook.  As part of the cleaning process, precincts were nested within counties and small rook adjacencies (under 30.5 m) were changed to queen adjacencies.

# **Sources**
@author: eveomett AI for Redistricting, USF All data retrieved 05/29/24:

Obtain the following data from Restricting Data Hub

[Population data](https://redistrictingdatahub.org/dataset/wisconsin-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[Congressional District data](https://redistrictingdatahub.org/dataset/2022-wisconsin-congressional-districts-approved-plan/): 2022 wisconsin Congressional Districts plan enacted on 2/27/23

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-wisconsin-precinct-and-election-results/)**:**  VEST 2020 wisconsin precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-wisconsin-precinct-and-election-results/)**:**  VEST 2018 wisconsin precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-wisconsin-precinct-and-election-results/)**:**  VEST 2016 wisconsin precinct and election results

And these data retrieved March 14, 2025:

[State House District data](https://redistrictingdatahub.org/dataset/2023-wisconsin-assembly-districts-plan-state-legislative-district-lower-sldl/): 2023 Wisconsin Assembly Districts Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2023-wisconsin-senate-districts-plan-state-legislative-district-upper-sldu/): State Senate Districts Plan Approved 2023

[2020 County Data](https://redistrictingdatahub.org/dataset/wisconsin-county-pl-94171-2020/): from 2020 Census Redistricting Data (P.L. 94-171) Shapefiles

## Preprocessing
Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup). 

## Metadata
- `CNTY_FIPS20`
- `CNTY_NAME10`
- `MCD_FIPS20`
- `MCD_NAME20`
- `CTV20`
- `WARDID20`
- `LABEL20`
- `PERSONS20`
- `RV20`
* `STATE`: State
* `STATEFP`: State FIPS code
* `COUNTYFP20`: County FIPS code
* `Precinct`: Precinct (ward)
* `Code`: Precinct code
* `Code-2`: Precinct code (2)
* `GOV18D`: Number of votes for 2018 Democratic gubernatorial candidate
* `GOV18R`: Number of votes for 2018 Republican gubernatorial candidate
* `SOS18D`: Number of votes for 2018 Democratic secretary of state candidate
* `SOS18R`: Number of votes for 2018 Republican secretary of state candidate
* `TRE18D`: Number of votes for 2018 Democratic treasurer candidate
* `TRE18R`: Number of votes for 2018 Republican treasurer candidate
* `USH18D`: Number of votes for 2018 Democratic US house candidate
* `USH18R`: Number of votes for 2018 Republican US house candidate
* `SEN18D`: Number of votes for 2018 Democratic senate candidate
* `SEN18R`: Number of votes for 2018 Republican senate candidate
* `AG18D`: Number of votes for 2018 Democratic attorney general candidate
* `AG18R`: Number of votes for 2018 Republican attorney general candidate
* `SH18D`: Number of votes for 2018 Democratic state house candidate
* `SH18R`: Number of votes for 2018 Republican state house candidate
* `SSEN18D`: Number of votes for 2018 Democratic state senate candidate
* `SSEN18R`: Number of votes for 2018 Republican state senate candidate
* `PRES16D`: Number of votes for 2016 Democratic presidential candidate
* `PRES16R`: Number of votes for 2016 Republican presidential candidate
* `USH16D`: Number of votes for 2016 Democratic US house candidate
* `USH16R`: Number of votes for 2016 Republican US house candidate
* `SEN16D`: Number of votes for 2016 Democratic senate candidate
* `SEN16R`: Number of votes for 2016 Republican senate candidate
* `SH16D`: Number of votes for 2016 Democratic state house candidate
* `SH16R`: Number of votes for 2016 Republican state house candidate
* `SSEN16D`: Number of votes for 2016 Democratic state senate candidate
* `SSEN16R`: Number of votes for 2016 Republican state senate candidate
* `GOV14D`: Number of votes for 2014 Democratic gubernatorial candidate
* `GOV14R`: Number of votes for 2014 Republican gubernatorial candidate
* `SOS14D`: Number of votes for 2014 Democratic secretary of state candidate
* `SOS14R`: Number of votes for 2014 Republican secretary of state candidate
* `TRE14D`: Number of votes for 2014 Democratic treasurer candidate
* `TRE14R`: Number of votes for 2014 Republican treasurer candidate
* `USH14D`: Number of votes for 2014 Democratic US house candidate
* `USH14R`: Number of votes for 2014 Republican US house candidate
* `AG14D`: Number of votes for 2014 Democratic attorney general candidate
* `AG14R`: Number of votes for 2014 Republican attorney general candidate
* `SH14D`: Number of votes for 2014 Democratic state house candidate
* `SH14R`: Number of votes for 2014 Republican state house candidate
* `SSEN14D`: Number of votes for 2014 Democratic state senate candidate
* `SSEN14R`: Number of votes for 2014 Republican state senate candidate
* `GOV12D`: Number of votes for 2012 Democratic gubernatorial candidate
* `GOV12R`: Number of votes for 2012 Republican gubernatorial candidate
* `PRES12D`: Number of votes for 2012 Democratic presidential candidate
* `PRES12R`: Number of votes for 2012 Republican presidential candidate
* `USH12D`: Number of votes for 2012 Democratic US house candidate
* `USH12R`: Number of votes for 2012 Republican US house candidate
* `SEN12D`: Number of votes for 2012 Democratic senate candidate
* `SEN12R`: Number of votes for 2012 Republican senate candidate
* `SH12D`: Number of votes for 2012 Democratic state house candidate
* `SH12R`: Number of votes for 2012 Republican state house candidate
* `SSEN12D`: Number of votes for 2012 Democratic state senate candidate
* `SSEN12R`: Number of votes for 2012 Republican state senate candidate
* `TOTPOP`: Total population from 2010 Decennial Census
* `NH_WHITE`: White, non-hispanic, population from 2010 Decennial Census
* `NH_BLACK`: Black, non-hispanic, population from 2010 Decennial Census
* `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population from 2010 Decennial Census
* `NH_ASIAN`: Asian, non-hispanic, population from 2010 Decennial Census
* `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population from 2010 Decennial Census
* `NH_OTHER`: Other race, non-hispanic, population from 2010 Decennial Census
* `NH_2MORE`: Two or more races, non-hispanic, population from 2010 Decennial Census
* `HISP`: Hispanic population from 2010 Decennial Census
* `H_WHITE`: White, hispanic, population from 2010 Decennial Census
* `H_BLACK`: Black, hispanic, population from 2010 Decennial Census
* `H_AMIN`: American Indian and Alaska Native, hispanic, population from 2010 Decennial Census
* `H_ASIAN`: Asian, hispanic, population from 2010 Decennial Census
* `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population from 2010 Decennial Census
* `H_OTHER`: Other race, hispanic, population from 2010 Decennial Census
* `H_2MORE`: Two or more races, hispanic, population from 2010 Decennial Census
* `VAP`: Total voting age population from 2010 Decennial Census
* `HVAP`: Hispanic voting age population from 2010 Decennial Census
* `WVAP`: White, non-hispanic, voting age population from 2010 Decennial Census
* `BVAP`: Black, non-hispanic, voting age population from 2010 Decennial Census
* `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population from 2010 Decennial Census
* `ASIANVAP`: Asian, non-hispanic, voting age population from 2010 Decennial Census
* `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population from 2010 Decennial Census
* `OTHERVAP`: Other race, non-hispanic, voting age population from 2010 Decennial Census
* `2MOREVAP`: Two or more races, non-hispanic, voting age population from 2010 Decennial Census
* `HDIST`: State House district
* `SEND`: State Senate distict
* `CD`: Congressional district

## Projection
The shapefiles use a NAD83 UTM zone 16 N (or EPSG:26916) projection.

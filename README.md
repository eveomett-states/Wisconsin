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
- `CNTY_FIPS20`: County FIPS code
- `CNTY_NAME20`: County name
- `MCD_FIPS20`: Minor Civil Division FIPS code
- `MCD_NAME20`: Minor Civil Division name
- `CTV20`: City, Town, or Village code
- `WARDID20`: Ward ID
- `LABEL20`: City label, with CTV code, and ID
- `PERSONS20`: Population (from 2020 election data file)
- `RV20`: Registered Voters (from 2020 election data file)
- `CD`: Congressional district ID in 2022 enacted congressional map
- `SEND`: State Senate district for 2023 approved State Senate Plan
- `HDIST`: State House district for 2023 approved State House of Representatives Districts Plan
- `TOTPOP`: Total population in 2020 Census
- `NH_WHITE`: White, non-hispanic, population in 2020 Census
- `NH_BLACK`: Black, non-hispanic, population in 2020 Census
- `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population in 2020 Census
- `NH_ASIAN`: Asian, non-hispanic, population in 2020 Census
- `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population in 2020 Census
- `NH_OTHER`: Other race, non-hispanic, population in 2020 Census
- `NH_2MORE`: Two or more races, non-hispanic, population in 2020 Census
- `HISP`: Hispanic population in 2020 Census
- `H_WHITE`: White, hispanic, population in 2020 Census
- `H_BLACK`: Black, hispanic, population in 2020 Census
- `H_AMIN`: American Indian and Alaska Native, hispanic, population in 2020 Census
- `H_ASIAN`: Asian, hispanic, population in 2020 Census
- `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population in 2020 Census
- `H_OTHER`: Other race, hispanic, population in 2020 Census
- `H_2MORE`: Two or more races, hispanic, population in 2020 Census
- `VAP`: Total voting age population in 2020 Census
- `HVAP`: Hispanic voting age population in 2020 Census
- `WVAP`: White, non-hispanic, voting age population in 2020 Census
- `BVAP`: Black, non-hispanic, voting age population in 2020 Census
- `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population in 2020 Census
- `ASIANVAP`: Asian, non-hispanic, voting age population in 2020 Census
- `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population in 2020 Census
- `OTHERVAP`: Other race, non-hispanic, voting age population in 2020 Census
- `2MOREVAP`: Two or more races, non-hispanic, voting age population in 2020 Census
- `ATG18D`: Number of votes for 2018 Democratic Attorney General candidate
- `ATG18R`: Number of votes for 2018 Republican Attorney General candidate
- `ATG18O`: Number of votes for 2018 other party's Attorney General candidate
- `GOV18D`: Number of votes for 2018 Democratic Gubernatorial candidate
- `GOV18R`: Number of votes for 2018 Republican Gubernatorial candidate
- `GOV18O`: Number of votes for 2018 other party's Gubernatorial candidate
- `PRE16D`: Number of votes for 2016 Democratic Presidential candidate
- `PRE16O`: Number of votes for 2016 other party's Presidential candidate
- `PRE16R`: Number of votes for 2016 Republican Presidential candidate
- `PRE20D`: Number of votes for 2020 Democratic Presidential candidate
- `PRE20R`: Number of votes for 2020 Republican Presidential candidate
- `PRE20O`: Number of votes for 2020 other party's Presidential candidate
- `SOS18D`: Number of votes for 2018 Democratic Secretary of State candidate
- `SOS18R`: Number of votes for 2018 Republican Secretary of State candidate
- `SOS18O`: Number of votes for 2018 other party's Secretary of State candidate
- `TRE18D`: Number of votes for 2018 Democratic Treasurer candidate
- `TRE18R`: Number of votes for 2018 Republican Treasurer candidate
- `TRE18O`: Number of votes for 2018 other party's Treasurer candidate
- `USS16D`: Number of votes for 2016 Democratic senate candidate
- `USS16R`: Number of votes for 2016 Republican senate candidate
- `USS16O`: Number of votes for 2016 other party's senate candidate
- `USS18D`: Number of votes for 2018 Democratic senate candidate
- `USS18R`: Number of votes for 2018 Republican senate candidate
- `USS18O`: Number of votes for 2018 other party's senate candidate

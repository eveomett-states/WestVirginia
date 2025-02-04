# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# West Virginia Json

This shapefile was processed by Professor Ellen Veomett and her student Ananya Agarwal using the corresponding jupyter notebook.

# **Sources**
All data retrieved 05/30/24:

Obtain the following data from Restricting Data Hub

[Population data](https://redistrictingdatahub.org/dataset/west-virginia-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[Congressional District data](https://redistrictingdatahub.org/dataset/2021-west-virginia-congressional-districts-adopted-plan/): 2021 West Virginia Congressional Districts plan enacted on 11/11/21

[State House District data](https://redistrictingdatahub.org/dataset/2021-west-virginia-state-house-adopted-plan/): 2024 State House Approved Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2021-west-virginia-state-senate-adopted-plan/): 2021 State Senate Approved Plan

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-west-virginia-precinct-and-election-results/)**:**  VEST 2020 West Virginia precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-west-virginia-precinct-and-election-results/)**:**  VEST 2018 West Virginia precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-west-virginia-precinct-and-election-results/)**:**  VEST 2016 West Virginia precinct and election results

# **Processing**

Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup).  

# **Metadata**

Below is a brief description of each of the listed variables in the attribute table of the VTD shapefile:

- `STATEFP20`: State FIPS code
- `COUNTYFP20`: County FIPS code
- `VTDST20`: Voting tabulation district FIPS code
- `NAME20`: Voting tabulation district name
- `NAMELSAD`: name and legal/statistical area description (LSAD)
- `CD`: Congressional district ID in 2022 enacted congressional map
- `SEND`: State Senate district for 2021 State Senate Adopted Plan
- `HDIST`: State House district for 2024 State House of Representatives Districts Plan
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
- `AGR16D`: Number of votes for 2016 Democratic commissioner of agriculture candidate
- `AGR16R`: Number of votes for 2016 Republican commissioner of agriculture candidate
- `AGR16O`: Number of votes for 2016 other party's commissioner of agriculture candidate
- `AGR20D`: Number of votes for 2020 Democratic commissioner of agriculture candidate
- `AGR20R`: Number of votes for 2020 Republican commissioner of agriculture candidate
- `ATG16D`: Number of votes for 2016 Democratic attorney general candidate
- `ATG16R`: Number of votes for 2016 Republican attorney general candidate
- `ATG16O`: Number of votes for 2016 other party's attorney general candidate
- `ATG20D`: Number of votes for 2020 Democratic attorney general candidate
- `ATG20R`: Number of votes for 2020 Republican attorney general candidate
- `AUD16D`: Number of votes for 2016 Democratic auditor candidate
- `AUD16R`: Number of votes for 2016 Republican auditor candidate
- `AUD16O`: Number of votes for 2016 other party's auditor candidate
- `AUD20D`: Number of votes for 2020 Democratic auditor candidate
- `AUD20R`: Number of votes for 2020 Republican auditor candidate
- `GOV16D`: Number of votes for 2016 Democratic gubernatorial candidate
- `GOV16R`: Number of votes for 2016 Republican gubernatorial candidate
- `GOV16O`: Number of votes for 2016 other party's gubernatorial candidate
- `GOV20D`: Number of votes for 2020 Democratic gubernatorial candidate
- `GOV20R`: Number of votes for 2020 Republican gubernatorial candidate
- `GOV20O`: Number of votes for 2020 other party's gubernatorial candidate
- `PRE16D`: Number of votes for 2016 Democratic presidential candidate
- `PRE16R`: Number of votes for 2016 Republican presidential candidate
- `PRE16O`: Number of votes for 2016 other party's presidential candidate
- `PRE20D`: Number of votes for 2020 Democratic presidential candidate
- `PRE20R`: Number of votes for 2020 Republican presidential candidate
- `PRE20O`: Number of votes for 2020 other party's presidential candidate
- `SOS16D`: Number of votes for 2016 Democratic Secretary of State
- `SOS16R`: Number of votes for 2016 Republican Secretary of State
- `SOS16O`: Number of votes for 2016 other party's Secretary of State
- `SOS20D`: Number of votes for 2020 Democratic Secretary of State
- `SOS20R`: Number of votes for 2020 Republican Secretary of State
- `TRE16D`: Number of votes for 2016 Democratic Treasurer
- `TRE16R`: Number of votes for 2016 Republican Treasurer
- `TRE16O`: Number of votes for 2016 other party's Treasurer
- `TRE20D`: Number of votes for 2020 Democratic Treasurer
- `TRE20R`: Number of votes for 2020 Republican Treasurer
- `USS18D`: Number of votes for 2018 Democratic senate candidate
- `USS18R`: Number of votes for 2018 Republican senate candidate
- `USS18O`: Number of votes for 2018 other party's senate candidate
- `USS20D`: Number of votes for 2020 Democratic senate candidate
- `USS20R`: Number of votes for 2020 Republican senate candidate
- `USS20O`: Number of votes for 2020 other party's senate candidate

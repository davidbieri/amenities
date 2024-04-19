# Data files for "National Expenditures on Local Amenities"

This repository contains the data files and codebook documentation for the article

Bieri, Kuminoff & Pope (2023) "[National Expenditures on Local Amenities](https://doi.org/10.1016/j.jeem.2022.102717)", Journal of Envir. Econ. & Management, Vol. 117



## Files

- [bkp_appendix_jeem23.pdf](#bkp_appendix_jeem23.pdf)
- [bkp_amenity-codebook.pdf](#bkp_amenity-codebook.pdf)
- [bkp_amenities.dta](#bkp_amenities.dta)
- [bkp_expenditures.dta](#bkp_expenditures.dta)

  
### bkp_appendix_jeem23.pdf

This file contains the online appendix to the main paper, including detailed description of the data and results for auxiliary regressions.

### bkp_amenity-codebook.pdf

This manual documents the data collection and management for the first comprehensive national database of a broad range of county-level amenities (National Amenity Repository for the United States, “NARUS”). The corresponding data is contained in [bkp_amenities.dta](#bkp_amenities.dta)

### bkp_amenities.dta

STATA file with county-level amenities (as summarized in Table 1 of the paper).

### bkp_expenditures.dta

STATA file with implicit amenity expenditure estimates ($, per household). The spatial resolution of theses estimates is given for specific counties, PUMAs, or PUMA-county unions. Because we merged PUMS data with the county-level amenities in [bkp_amenities.dta](#bkp_amenities.dta) at the highest possible spatial resolution,  we aggregating the 3108 
counties in the contiguous U.S. into 950 locations (see Fig. 1 of the paper). Every location is a direct aggregation of U.S. counties: There are 379 individual counties containing multiple PUMAs (60% of the population); 495 individual PUMAs containing multiple counties where we aggregate amenities to the PUMA-level using county population weights; and 76 county clusters containing PUMAs that overlap county borders (cf. Figure 1 in the paper).


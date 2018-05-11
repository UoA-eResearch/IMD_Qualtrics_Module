# IMD_Qualtrics_Module

The IMD deprivation information comes from the New Zealand Index of Multiple Deprivation (IMD), a set of tools for identifying concentrations of deprivation in New Zealand. It measures deprivation at the neighbourhood-level in custom designed data zones that have an average population of 712. The IMD uses routinely collected data from government departments, 2013 census data and methods comparable to current international deprivation indices to measure different forms of disadvantage. It is comprised of 28 indicators grouped into seven domains of deprivation: Employment, Income, Crime, Housing, Health, Education and Access to services. The IMD is the combination of these seven domains, which may be used individually or in combination to explore the geography of deprivation and its association with a given health or social outcome. More information is available at http://www.fmhs.auckland.ac.nz/imd.

This module is based on the IMD Interactive Report Website at https://imdmap.auckland.ac.nz which accepts an address as parameter and returns the data zone ID and deprivation information that are then saved to the main survey output. The backend uses the Google geocoding API which has a query limit of 2500 per day and 50 requests per second.

The [IMD Interactive Report Website](https://imdmap.auckland.ac.nz/) and its Qualtrics module API have been developed by the [Centre for eResearch](http://cer.blogs.auckland.ac.nz/) at the University of Auckland.

## Setup

Download the .zip file by clicking the 'Clone or download' button. Create a new survey from existing in your Qualtrics account using the IMD_AddressToDatazone_ID.qsf file you just downloaded. You can save the block to your Qualtrics library and insert it in any of your existing surveys. Add the embedded data variables as described in the instructions PDF in order to receive additional deprivation information about the participant's data zone.

### Preview:
![Preview](https://github.com/UoA-eResearch/IMD_Qualtrics_Module/blob/master/Preview.PNG)

## Instructions on enabling embedded data: ##
https://github.com/UoA-eResearch/IMD_Qualtrics_Module/blob/master/Instructions%20Qualtrics.pdf

### Results:
![Results](https://github.com/UoA-eResearch/IMD_Qualtrics_Module/blob/master/Results.PNG)

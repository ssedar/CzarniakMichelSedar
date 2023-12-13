# CzarniakMichelSedar

## Summary
This repository contains the data and analysis conducted in R as part of the Czarniak, Michel, and Sedar EDE 872 Final group project. Analysis was conducted over the span of November and December 2023 to explore three key questions regarding the relationship between power plants in North Carolina and the impacts on the surrounding communities:
1. How does income impact power plant characteristics at the county level?
2. Do power plant retirements have a significant impact on unemployment?
3. Is there a relationship between power plant distribution and impacts to human health?

## Investigators
Gaby Czarniak, Duke University - Nicholas School of the Environment, gabriella.czarniak@duke.edu  
Mara Michel, Duke University - Nicholas School of the Environment, margaret.michel@duke.edu  
Sam Sedar, Duke University - Nicholas School of the Environment, sam.sedar@duke.edu

## Keywords
eGrid, Emissions, Capacity, Generation, Income, Power Plant, Social Vulnerability Index (SVI), Unemployment, Environmental Justice Index (EJI), Environmental Burden, Health Vulnerability

## Database Information

Sources for data used in this analysis are outlined below:  

*United States Environmental Protection Agency (EPA). 2023. “Emissions & Generation Resource Integrated Database (eGRID), 2021” Washington, DC: Office of Atmospheric Protection, Clean Air Markets Division. Available from EPA’s eGRID web site: https://www.epa.gov/egrid. Accessed on 11/1/2023.  

*United States Census Bureau. Cartographic Boundary Files - Shapefile. 2018 County. https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html. Accessed on 11/15/2023.  

*United States Department of Agriculture / Economic Research Service. Poverty estimates for the U.S., States, and counties, 2021. https://www.ers.usda.gov/data-products/county-level-data-sets/county-level-data-sets-download-data/. Accessed on 11/1/2023. 

*United States Department of Agriculture / Economic Research Service. Unemployment and median household income for the U.S., States, and counties, 2000–22. https://www.ers.usda.gov/data-products/county-level-data-sets/county-level-data-sets-download-data/. Accessed on 11/1/2023.  

*Centers for Disease Control and Prevention/ Agency for Toxic Substances and Disease Registry/ Geospatial Research, Analysis, and Services Program. CDC/ATSDR Social Vulnerability Index 2020. Database North Carolina. https://www.atsdr.cdc.gov/placeandhealth/svi/data_documentation_download.html. Accessed on 12/6/2023.  

*Centers for Disease Control and Prevention and Agency for Toxic Substances Disease Registry. 2022 Environmental Justice Index. https://www.atsdr.cdc.gov/placeandhealth/eji/index.html. Accessed on 12/5/2023.

## Folder structure and file formats

*Code - Folder containing project working file code. Files in this folder are .rmd format.  

*Data - Folder containing raw, processed and spatial data files as well as metadata. Raw and processed data is in .csv format. Spatial data is in .shp, .xml, .prj, .cbj, .dbf, and .gfs format. Metadata is in .pdf format.

*Output - Folder containing final report in .pdf format.

## Metadata
Metadata for each of the data sets can be found linked below. In the case of eGRID, SVI, and EJI data, the publishers created downloadable PDFs that are included in the 'Metadata' folder. The remaining datasets utilize an online format which must be accessed via web.  

*eGRID - United States Environmental Protection Agency (EPA). 2023. “eGRID 2021 Technical Guide” Washington, DC: Office of Atmospheric Protection, Clean Air Markets Division.https://www.epa.gov/system/files/documents/2023-01/eGRID2021_technical_guide.pdf  

*Income/poverty Data - U.S. Census Bureau. "Small Area Income and Poverty Estimates (SAIPE) Program." https://www.census.gov/programs-surveys/saipe.html

*Unemployment Data - U.S. Bureau of Labor Statistics. "Handbook of Methods." January 09, 2018. https://www.bls.gov/opub/hom/lau/home.htm 

*Social Vulnerability Index (SVI) - https://www.atsdr.cdc.gov/placeandhealth/svi/documentation/SVI_documentation_2020.html  

*Environmental Justice Index (EJI) - 
https://www.atsdr.cdc.gov/placeandhealth/eji/docs/EJI-2022-Documentation-508.pdf 

## Scripts and code

To review the scripts and code associated with the preparation of this report, please refer to the 'Code' folder. Code is notated with comments to describe the purpose and desired outcome of each step.

## Quality assurance/quality control
Our team did not conduct QA/QC on the accuracy of the raw data as our analysis assumes accuracy of our sources. However, the following QA/QC practices were implemented on our analyses. During the wrangling process, we checked for unintuitive values or results, such as NAs or negatives when all values should have been positive. Code was written to include descriptive comments of the purpose of each step. After each team member created their respective analysis code, the other team members would review for accuracy and reproducability. 

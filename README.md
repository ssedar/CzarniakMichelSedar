# CzarniakMichelSedar
<General notes: add as much information as is relevant for your repository. Some overarching guidelines are provided, but feel free to expand on these guidelines.>
<More resources found here: https://www.dataone.org/all-best-practices>
<Delete the text inside the brackets when formatting your file.>

## Summary
<describe the purpose of this repository, the information it contains, and any relevant analysis goals. What, why, where, when, how?>

This repository contains the data and analysis conducted in R as part of the Czarniak, Michel, and Sedar EDE 872 Final group project. Analysis was conducted over the span of November and December 2023 to explore three key questions regarding the relationship between power plants in North Carolina and the impacts on the surrounding communities:
1. 
2. 
3.

## Investigators
Gaby Czarniak, Duke University - Nicholas School of the Environment, gabriella.czarniak@duke.edu  
Mara Michel, Duke University - Nicholas School of the Environment, margaret.michel@duke.edu  
Sam Sedar, Duke University - Nicholas School of the Environment, sam.sedar@duke.edu

## Keywords
eGrid, Emissions, Capacity, Generation, Income, Power Plant, Social Vulnerability Index (SVI), Unemployment

## Database Information

Sources for data used in this analysis are outlined below:  

United States Environmental Protection Agency (EPA). 2023. “Emissions & Generation Resource Integrated Database (eGRID), 2021” Washington, DC: Office of Atmospheric Protection, Clean Air Markets Division. Available from EPA’s eGRID web site: https://www.epa.gov/egrid. Accessed on 11/1/2023.  

United States Census Bureau. Cartographic Boundary Files - Shapefile. 2018 County. https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html. Accessed on 11/15/2023.  

United States Department of Agriculture / Economic Research Service. Poverty estimates for the U.S., States, and counties, 2021. https://www.ers.usda.gov/data-products/county-level-data-sets/county-level-data-sets-download-data/. Accessed on 11/1/2023. 

United States Department of Agriculture / Economic Research Service. Unemployment and median household income for the U.S., States, and counties, 2000–22. https://www.ers.usda.gov/data-products/county-level-data-sets/county-level-data-sets-download-data/. Accessed on 11/1/2023.  

Centers for Disease Control and Prevention/ Agency for Toxic Substances and Disease Registry/ Geospatial Research, Analysis, and Services Program. CDC/ATSDR Social Vulnerability Index 2020. Database North Carolina. https://www.atsdr.cdc.gov/placeandhealth/svi/data_documentation_download.html. Accessed on 12/6/2023.  


## Folder structure, file formats, and naming conventions 

<describe the folders contained in the repository, including what type of files they contain>

<describe the formats of files for the various purposes contained in the repository>

<describe your file naming conventions>

Code - Folder containing project working file code. Files in this folder are .rmd format.  

Data - Folder containing raw, processed and spatial data files as well as metadata. Raw and processed data is in .csv format. Spatial data is in .shp, .xml, .prj, .cbj, .dbf, and .gfs format. Metadata is in .pdf format.  

Output - Folder containing final report in .pdf format.

## Metadata

<For each data file in the repository, describe the data contained in each column. Include the column name, a description of the information, the class of data, and any units associated with the data. Create a list or table for each data file.> 


## Scripts and code

<list any software scripts/code contained in the repository and a description of their purpose.>

## Quality assurance/quality control
Our team did not conduct any QA/QC on the accuracy of the raw data as our analysis assumes accuracy of our sources. However, the following QA/QC practices were implemented on our analyses. During the wrangling process, we checked for unintuitive values or results, such as NAs or negatives when all values should have been positive. After each team member created their respective analysis code, the other team members would review for accuracy and reproducability.

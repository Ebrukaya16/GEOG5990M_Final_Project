# GEOG5990M Final Project

# Final Project- Relationship of Social Grade to Crime Rates in West Yorkshire

This project was developed to examine the relationship between crime rates and social class in the West Yorkshire region.

Based on Nomis Website data for 2021 (https://www.nomisweb.co.uk/datasets/c2021sg002), various social classes will be examined according to different LSOA codes in West Yorkshire. These classes are: AB Higher and Middle Management/Executive/Professional Occupations, C1 Supervised Clerk and Junior Management/Executive/Professional Occupations, C2 Skilled Manual Occupations, and DE Semi-Skilled and Non-Skilled Manual Occupations/Unemployed and Lowest Class Occupations.
At the same time, crime records published by West Yorkshire Police in December 2021 will be reviewed (https://data.police.uk/data/). This data includes the type of crime, reporting agency, LSOA information, and location information.
In this final project, crime data and social grade data will be analyzed in detail and then the correlation between these data will be examined through LSOA codes. Afterwards, visualization will be made on the map with the K-means clustering algorithm using both data sources. These analyzes will be used to understand the relationship between crime and social grade.

The shapefile file must be loaded and made available for use. Since crime data is published on the basis of LSOA (Lower Layer Super Output Area), our shapefile containing geographical data at the LSOA level was downloaded from the Geoportal website and Census 2021 from the website. https://geoportal.statistics.gov.uk/datasets/bb427d36197443959de8a1462c8f1c55_0/explore


##Project
Ebrukaya16/GEOG5990M_Final_Project/Finalproject.ipynb

##Information

This project used crime.csv, social_grade.csv, these two tables.  west_yorkshre_shp.dbf, west_yorkshre_shp.gpkg, west_yorkshre_shp.prj, west_yorkshre_shp.shp, west_yorkshre_shp.shx these files were used for west yorkshire shpfile. Spatial environment.yml, this file was used for computer pyhton package installation.



Lisans
This project is licensed under the GNU GENERAL PUBLIC LICENSE. See the LICENSE file for more information.

Contact
For feedback or questions about the project, you can contact ml22ek2@leeds.ac.uk.

# GEOG5990M Programming for Geographical Information Analysis: Core Skills Final Project

# Project- Relationship of Social Grade to Crime Rates in West Yorkshire

This project was developed as a final project for the MSc GIS GEOG5990M course, with the aim of examining the relationship between crime rates and social grade in the West Yorkshire region. This project was created to provide public insight.

Based on Nomis Website data for 2021 (https://www.nomisweb.co.uk/datasets/c2021sg002), various social grade will be examined according to different LSOA codes in West Yorkshire. These classes are: AB Higher and Middle Management/Executive/Professional Occupations, C1 Supervised Clerk and Junior Management/Executive/Professional Occupations, C2 Skilled Manual Occupations, and DE Semi-Skilled and Non-Skilled Manual Occupations/Unemployed and Lowest Class Occupations.
At the same time, crime records published by West Yorkshire Police in December 2021 will be reviewed (https://data.police.uk/data/). This data includes the type of crime, reporting agency, LSOA information, and location information.
In this final project, crime data and social grade data will be analyzed in detail and then the correlation between these data will be examined through LSOA codes. Afterwards, visualization will be made on the map with the K-means clustering algorithm using both data sources. These analyzes will be used to understand the relationship between crime and social grade.

The shapefile file must be loaded and made available for use. Since crime data is published on the basis of LSOA (Lower Layer Super Output Area), our shapefile containing geographical data at the LSOA level was downloaded from the Geoportal website and Census 2021 from the website. https://geoportal.statistics.gov.uk/datasets/bb427d36197443959de8a1462c8f1c55_0/explore


Project Path
Ebrukaya16/GEOG5990M_Final_Project/Finalproject.ipynb

Required Files 

The data used in this project was provided from crime.csv, Social_grade.csv and these two tables. 

west_yorkshre_shp.dbf, west_yorkshre_shp.gpkg, west_yorkshre_shp.prj, west_yorkshre_shp.shp, west_yorkshre_shp.shx these files were used for west yorkshire shpfile. 

Spatial environment.yml, this file was used for computer pyhton package installation.

In the ipynb file, each step is explained in detail and the results are interpreted.

Lisans
This project is licensed under the GNU GENERAL PUBLIC LICENSE. See the LICENSE file for more information.

Contact
For feedback or questions about the project, you can contact ml22ek2@leeds.ac.uk.

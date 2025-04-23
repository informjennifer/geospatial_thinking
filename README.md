# Geospatial Thinking
This repository supplements the hands-on section of the OER, Geospatial Thinking and Open Source GIS

The gitbook will be broken into modules which increase in complexity.
The software needed to do the exercises is QGIS: https://qgis.org/; I'm using version 3.42.2, but I recommend you download the most recent stable version.
In each module, you will need to go find the datasets needed to do the work.

## Module 1 Getting Data (Part 2, Chapter 6)
### Data we will collect includes:
-	Income (source: US Census/IPUMS)
- Housing characteristics (source: US Census/IPUMS)
- Race (source: US Census/IPUMS)
-	Housing assessments (source: St. Louis County Planning)
-	Zoning information (source: St. Louis County Planning)
-	Business Locations (source: Data Axle)
-	Schools and Libraries (source: MSDIS)
-	School ratings (source: NESI)
-	Contour lines (source: MSDIS)

#### Getting Census Data
We will start with Census.gov to get the data we need. Census.gov provides the Decinial Census (10yr) as well as the American Community Survey (estimates between the decinial census)
If you are unable to get historical data from Census.gov, another useful tool is IPUMS NHGIS https://www.nhgis.org/ 


- The exercises in this book will use Census Tract Level Data for St. Louis City and St. Louis County. Using the *advanced search* in Census.gove, filter for the following.
  - Geographies: 
    - Census Tracts
      - Missouri
       - St. Louis City, All Tracts in St. Louis City
       - St. Louis County, All Tracts in St. Louis County
  - Topics:
    - Housing
       - Financial Characteristics
        - DP04: Selected Housing Characteristics
        -  Download table DP04 for years 2010 and 2020
        -  Data:[Uploading ACSDP5Y2020DP04_Data.csv…]
        -  Metadata:[Uploading ACSDP5Y2020DP04_Column-Metadata.csv…]

  - Remove topic filters (I recommend to gather these topic tables separately)
  - Topics:
    - Income and Povety
      - S1902: Mean Income and Poverty in the Past 12 months
      - Download table S1902 for years 2010 and 2020
  - Remove topic filters (I recommend to gather these topic tables separately)
  - Topics:
    - Race
     - All Available Races
      - B01003: Total Population
      - Download table B01003: for years 2010 and 2021

# SDOHDataLab

Resource platform for collaborative research and analysis on Social Determinants of Health (SDOH) data.

## Repository Structure

This repository is organized into several folders, each containing data and resources relevant to different aspects of SDOH. Below is an overview of the folders and their contents.

### Amenities

This folder contains Shapefiles for transportation infrastructure, facilitating the analysis of access to transport amenities.

- **Source:** LTA Data Mall [LTA Data Mall](https://datamall.lta.gov.sg/content/datamall/en.html)

### Census

The Census folder offers insights into the areal distribution of household income, education, employment status, occupation, religion, and modes of transport to work or school.

- **Data Sources:**
  - 2015 Household Survey
  - 2020 Population Census Data, Department of Statistics Singapore ([SingStat](https://www.singstat.gov.sg/find-data/search-by-theme/population/geographic-distribution/latest-data))
- **Identifier:** Planning area, with 55 unique identifiers.

### Climate

This folder includes data on historical weather and pollutants, aiding in the study of environmental health impacts.

- **Historical Weather Data:**
  - From 13 selected stations. [Historical Daily](http://www.weather.gov.sg/climate-historical-daily/)
- **Pollutant Data:**
  - Sourced from the National Environment Agency (NEA) and stored as a large list in R-data format. [NEA Data](https://beta.data.gov.sg/datasets/d_8a7850dc3993dc45f1620b9972c58d4d/view)
  - Note: Data wrangling is required for usability.

### Maps

Maps provide geospatial context for SDOH research, including planning area boundaries and postal district meta-matching.

- **Master Plan 2019:** [Master Plan 2019](https://beta.data.gov.sg/collections/1646/datasets/d_4618344de58976e296275d93e17ae0ae/view)
- **Master Plan 2014:** Includes planning area boundaries.
- **Meta-matching:** Offers crude matching of 28 postal districts to the 55 planning areas for broader analysis.

### Property

The Property folder contains data on resale pricing, offering insights into housing affordability and its health implications.

- **Source:** [Resale Pricing Data](https://beta.data.gov.sg/collections/189/datasets/d_8b84c4ee58e3cfc0ece0d773c8ca6abc/view)

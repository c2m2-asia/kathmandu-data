
# kathmandu-hub-data 

> This repository aims to consolidate and digitize all data collected by the Cities' Covid Mitigation Mapping Project (C2M2) Kathmandu Hub.

### About C2M2

The Cities Covid Mapping and Mitigation Project is  focused on mitigating and recovering from secondary impacts of COVID-19 in the region. The city projects will add missing maps, data and ICT inventories that shall help revive the livelihoods of those affected by the pandemic. The project is funded by the U.S. Department of State and managed by American Association of Geographers.

### About the C2M2 Kathmandu Hub

The Kathmandu Hub is focued on understanding the second-order impact of Covid-19 on Kathmandu's tourism industry.

## Coding the data

Our data comes from different sources, and is available freely for anyone to use through this repository. To help you navigate this repository, we've attempted to index all of the information using the following scheme:

1. Data will be separated into folders by source, which will be named using the following convention:

    1. Folder names for data gathered through reports will be prefixed by the letter `R` followed by a serial number assigned to the report and a decriptive name which usually includes a) the organizations involved, b) the title of the report, and c) the date if available, e.g., `R01_IIDS_UNDP_RAPID_ASSESSMENT`

    2. Folder names for geospatial data will be prefixed by the the letter `G` followed by a serial number and a descriptive name which includes a) source and b) date if available, e.g., `G01_OSM_TOURISM_FACILITIES_15_DEC_2020`

2. Individuals data files when possible will be profixed by the report code, e.g., `R01_`, `G01`, followed by a prefix for the type of data `CSV`, `SHP`, `IMG` and a code, which is thenn followed by the name, e.g., `R01_CSV01_ALLOCATION_TO_STUDY_SAMPLE BY_DISTRICT.csv`

## Data Index

| Code | Name                                                          | Type                  | Description                                                                   | Organizations | Time period of data | Notes |
|------|---------------------------------------------------------------|-----------------------|-------------------------------------------------------------------------------|---------------|---------------------|-------|
| R01  | Rapid Assessment of Socio Economic Impact of COVID19 in Nepal | Report                | A detailed cross sectoral study on the immediate impacts of Covid-19 to Nepal | IIDS/UNDP     | April 2020          |       |
| G01  | OSM data for tourism amenities in Kathmandu Valley            | Geospatial data (SHP) | An extract of tourism related POIs from OpenStreetMap                         | OSM           | 15 December 2020    |       |
|      |                                                               |                       |                                                                               |               |                     |       |


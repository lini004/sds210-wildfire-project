# SDS210 Wildfire Project in Borneo

## Research question and description
Where are the most intense active fires in Borneo right now, and how is fire activity distributed across the region?


## Data sources
- Requires a free NASA Earthdata API key 
https://firms.modaps.eosdis.nasa.gov/api/ 

- Fire data: NASA FIRMS VIIRS NRT
'https://firms.modaps.eosdis.nasa.gov/mapserver/mapkey_status/?map_key=' + map_key



## Setup
1. Clone this repository
2. Install the required python packages:
   pip install pandas requests folium
3. Add your NASA FIRMS API key (see How to Run)

 ## How to run
1. Register for a free API key
2. Add your NASA FIRMS API key in cell 2 of the notebook
3. Run `notebooks/fire_project1.ipynb` top to bottom

## Outputs
Interactive folium map (might have to open it in browser), always near real time displays, shows live fire detections for the last 24 hours over Borneo

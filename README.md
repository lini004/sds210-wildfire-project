# sds210-wildfire-project in Borneo

## Research question
Where are the most intense active fires in Borneo right now, and how is fire activity distributed across the region?

## Data sources
- Fire data: NASA FIRMS VIIRS NRT API  
  https://firms.modaps.eosdis.nasa.gov/api/ 

 --> Requires a free NASA Earthdata API key

 ## Setup
1. Clone this repository
2. Install dependencies: `conda env create -f environment.yml`
3. Activate environment: `conda activate sds-env`

 ## How to run
1. Add your NASA FIRMS API key in cell 2 of the notebook
2. Run `notebooks/fire_project1.ipynb` top to bottom

## Outputs
Interactive folium map, always near real time displays

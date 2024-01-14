# Sentinel-2 Satellite Image preprocessing

This repository is built to track learnings of preprocessing satellite imagery for machine learning application.
 
 
All the code is included in `notebooks/preprocessing_satellite_imagery.ipynb`

Before running the notebook, do the following steps first:

- run `pip install requirements.txt`
- create a geojson file of the zone you want a satellite imagery of and save it in `data/target_zone.geojson`
- create an account at [Coppernicus Data Space Ecosystem](https://dataspace.copernicus.eu/). 
Write the username and the password in a json file and save it in `secrets/sentinel_api_credentials.json`.
Format: `{"username": "XXXX", "password": "XXXX"}`



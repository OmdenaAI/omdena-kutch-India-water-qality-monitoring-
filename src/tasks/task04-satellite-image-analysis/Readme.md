# Satellite Image Analysis

## Description

Satellite Image Analysis focuses on analyzing the images from the selected sources and apply various standard formulae to get a glimpse of the colours of the water body regions.

## Formulas :

pH = 8.339-0.827*(B1/B8)

Salinity = (B11-B12)/(B11+B12)

Turbidity= (B4-B3)/(B4+B3)

Land Surface Temperature = ST_B10* 0.00341802+149.0 – 273.15

Chlorophyll = (B5-B4)/(B5+B4)

Suspended Matter = Oa08_radiance/Oa06_radiance

Dissolved Organic Matter = Oa08_radiance/Oa04_radiance

Dissolved Oxygen = -0.0167*B8+0.0067*B9+0.0083*B11+9.577


Water Quality Standards : https://docs.google.com/spreadsheets/d/1_uNbSpXKCI0oSsdHCsmXU45I9odqEWaCTs5SUukCA8c/edit#gid=63857209


## Links 

Satellite Imagery Analysis using Python : https://towardsdatascience.com/satellite-imagery-analysis-using-python-9f389569862c

Python Package for Interactive Mapping with Google Earth Engine : https://github.com/giswqs/geemap/blob/master/examples/notebooks/tn_surface_water.ipynb

Water Quality Information : https://medium.com/sentinel-hub/water-quality-information-for-everyone-a81faab8ff5e

Mapping Surface Water Dynamics using Earth Engine : https://colab.research.google.com/github/giswqs/geemap/blob/master/examples/notebooks/surface_water_mapping.ipynb#scrollTo=bsfQYwOnkB72

Enclosure of Parameters for Water Quality :
https://code.earthengine.google.com/?scriptPath=users%2Fsaivilliers%2Fsai%3AOmdena%2FWater_quality / https://code.earthengine.google.com/?accept_repo=users/saivilliers/sai

Enclosure of Converting Js to Python syntax :
https://giswqs.medium.com/15-converting-earth-engine-javascripts-to-python-code-with-just-a-few-mouse-clicks-6aa02b1268e1

Create & Deploy Earth Engine Apps using Python : https://www.youtube.com/watch?v=nsIjfD83ggA&list=PLAxJ4-o7ZoPccOFv1dCwvGI6TYnirRTg3&index=29

Earth Engine Data Catalog : https://developers.google.com/earth-engine/datasets/catalog/

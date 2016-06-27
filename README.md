# Mapping_Instagram_Data

### Methods and Strategies for mapping Instagram Data  

This notebook shows a step-by-step process for filtering & organizing data from the Instagram API to display on web applications.  Uses the following libraries: Pickle, Folium, Fiona, Shapely.

High-Level steps:
> 1. Gather data from API, save to file -> [SEE HERE](https://github.com/jefarrell/Python-Instagram_API_Scripts/blob/master/instagramTagSearch.py)!
> 2. Read that file, remove extra attributes we don't need
> 3. Remove posts without location data
> 4. Remove posts that don't lie within a specific geographic area
> 5. Continually use inline maps to check our work
> 6. Save our cleaned data to geoJSON files for use on the web


## I developed this process to make a visualization of [National Parks Photography](https://github.com/jefarrell/National_Park_Visualization).



# San Francisco Crime Choropleth Map

- **Main Objective:** Create a San Francisco Map of the crimes committed in 2016,
where it is able to visualize the most affected neighborhoods.

  The objective of this project is to create a Choropleth map to visualize 
  crimes registered in San Francisco in 2016 by Neighborhood. This requires
  the Folium Package.

  After loading the dataset, I performed the Data Wrangling to isolate and
  get the data needed for the task. As a result, I got a clean dataframe to
  be used at the map.
 
  Then, I downloaded the San Francisco geojson to the project, where I also
  checked  the file for the Feature Properties as 'DISTRICT'. The last step
  was to create the map  with San Francisco coordinates using Folium Package  
  and then apply the Choropleth Map.
  
  PS: As GitHub is not currently compatible with Folium package, we can see
  the resulting **interactive map** by pasting the notebook link into **https://nbviewer.jupyter.org/**  
  A screenshot is also uploaded of the resulting map.
  
  - **Results:** Interactive Choropleth Map that shows the most affected neighborhoods by color.
  
  - **Libraries:** Folium, Pandas, Numpy

  - **Keywords:** GeoJSON, Data Visualization, Interactive Map

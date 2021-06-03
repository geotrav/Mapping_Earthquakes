# Mapping_Earthquakes

### Purpose
The purpose of this project is to create a map leveraging the Leaflet platform to display plate boundaries and earthquake activity over the past seven days.

### Results
Using Javascript, recent earthquakes (within the past 7 days) JSON files are read and place on the map.  The base map has three options:
1. streets
2. satellite-streets
3. navigation night

On these base layers all eartthquakes are displayed on one layerr with an additional layer to host the major earthquakes of magnitude 4.5 or greater.   The plate boundaries are also provided as a layer with green lines.  One can see the association of the majority of the earthquakes with the mapped plate boundaries.

### Summary
Since this map is pulling the data in real time from the USGS website, any refresh of the page should receive the most up to date earthquake data.  The majority of the earthquakes and major earthquakes are located near or along the plate boundaries.  These maps can be used to assess risk and examine spatially the trends on earthquake activity.
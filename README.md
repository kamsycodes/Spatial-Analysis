# Spatial-Analysis
https://qgiscloud.com/Mapper/Awka_South_Facility_Map/
Please click the link above to access the map 
The data collection for this project was done in two phases, field capture using GPS essential app, and extraction from google map( for the points that have been mapped by other people, and can be easily picked from google as POI), this is for point data(hotel, health facility,tourist sites, and town), note: some of the points captured in the field has videos and pictures attached to their attributes. 

The road, building, stream, and lake were extracted them from open street map using 'Download OSM  data by rectangle selection' plugin in Qgis. Using this plugin, you can get vector data of an area which will include road, building, stream, lake and other vectors. They came in OSM format, which then I converted to shapefile. 

For the boundary, I digitized it using the way Awka south map. 

The bounding LGA are points, which I also created as point layer looking at the communities that bound Awka South.

 For the digital elevation, I downloaded the image from SRTM free image website, after which I used the boundary to clip out Awka South from the general imagery, and then changed the color to depict elevation, as well as reduced the color contrast so that it looks faint the way you saw it. 

Then for the satellite imagery, I used MBTiles extraction plugin in Qgis 3.12 to extract it from google imagery. 

Those styles I used to represent the points are SVG icons in Qgis, which I used to make each point look like the feature it represents. 

I placed the layers on different zoom levels through the qgis layer property settings, to avoid every feature appearing and clustering at the same time when viewed.

 When I was done giving suitable colors to other features and doing all needed adjustment, I uploaded the entire project on Qgis cloud platform, which is a free open source server where you can save your project and get an automatically generated URL you can send to anybody to see what you have done. 

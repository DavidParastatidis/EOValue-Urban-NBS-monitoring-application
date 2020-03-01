# EOValue-Urban-NBS-monitoring-application
The Urban NBS (Nature Based Solutions) application can detect green roofs for the city of London and provide NDVI timeseries for them.
For more information about the application and how to use it please refer to the "Final Report", "User Manual" and "Data Managment Plan" documents. 

This application was implemented in Google Earth Engine. In order to run it and modify in the Google Earth Engine code editor you must to have a free Google Earth Engine account. You can sign up here https://earthengine.google.com/

In order for the application to work properly first upload and include the vector data "buildings.shp" and "Capitals.shp"

If you want to expand the application for more cities you can just add a city's borders shapefile in the Capitals.shp and its building footprints in the buildings.shp with the use of a GIS application like QGIS. The app should work properly for the added cities without the need to modify anything in the source code

# Kibale-Map
Map of KIbale National Park, Uganda with focal data for three primate species (redtails, mangabeys and black and white colobus). Also includes tree mapping data (species, DBH and coordinates for >10,000 trees in the forest) 

For using this data: 
The Kibale Map QGIS project file can be opened on your personal QGIS application as long as all files from this repository are in the same file folder on your computer. Make sure especially that all Focal GPS saptial files and Tree Mapping spatial files are together. 

For adding to or editing data:
If you would like to add data to either FocalGPS or Tree Mapping, you will need to start by editing the .csv file for either. Add your data or edits to the .csv file. Then go to Layer tab in QGIS -> Add Layer -> Add Delimited Text Layer.

This will bring you to the Data Source Manager|Delimited Text. Make sure CSV is selected and choose the file from your desktop using the three dots next to File name. You can then name your layer using Layer name. Open Geometry Definition and use X field drop down menu to select GPS 1. Then use Y field drop down menu to select GPS 2. For Geometry CRS, select Project CRS. Then click Add and your updated spatial data will be added to the map. 

For then saving your new spatial vector as a shapefile, right click on your new layer -> Export -> Save Features As. For Format, from the dropdown menu select ESRI Shapefile. Click the three dots next to file name to save the shapefile to your computer, then press Ok. 

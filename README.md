# Dam-Nation
This information is drawn from 79,777 dams in the U.S. Army Corps of Engineers National Inventory of Dams. 
The purpose of the project, is to map these existing structures, by age and size. The map also identifies the 
the feature's height, depth and capacity amongst the other characteristics.

### Project Data
Data for the project was sourced from the Bureau of Transportation and Statistics website: https://data-usdot.opendata.arcgis.com/datasets/dams/.
This was downloaded using the API option available (geoJSON format). The data was then reviewed in QGIS to and fields not relevant to the project were excluded.
The remaining data was then converted to a JavaScript file for use in the mapping process.
Object keys can be found at this site :https://databasin.org/datasets/7522c53308f942ceb202ab298f801a1a/layers/152c4bd9b38043c4b5581400308830cf/metadata/original

Basemap: sourced from :https://cartodb-basemaps-{s}.global.ssl.fastly.net/rastertiles/dark_all/{z}/{x}/{y}.png

### Symbology
Dams were symbolized using proportionate circles, representing their total capacity.
Construction was divided into five (5) periods:
pre-1900,
1900-1925,
1925-1950,
1950-1975,
1975-2000,
2000-present day.


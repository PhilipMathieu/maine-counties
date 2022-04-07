# Maine Counties

The State of Maine provides a lot of valuable data through the [Maine Office of GIS (MEGIS)](https://www.maine.gov/megis/). One of the most useful for supplementing other geospatial datasets are the various "boundaries" options: https://www.maine.gov/geolib/catalog.html#boundaries

The tricky part is deciding how actually to access that data. In most cases, you will want to start by clicking on the name of the boundaries. Let's use "[Maine County Boundary Polygons Dissolved](https://maine.hub.arcgis.com/datasets/ec1a999644cf4e128c84d207f6b8e2bc)" as an example.

This file is hosted on the arcgis.com website. The website is run by the company ESRI. It makes it very easy to use the data in ESRI software, but sometimes makes it hard to find other data options. In this case, look for the download symbol:
![image](https://user-images.githubusercontent.com/3598004/162337139-229745ed-875c-4e65-8a39-37de94c96ed8.png)
This will bring up a menu of download options. At the very bottom is GeoJSON.

## Side Note: Dissolved Polygons
Sometimes when you have a large dataset it is convenient to combine multiple polygons into a single record. For example, if you want the boundary of Portland, ME, you probably want one boundary including the islands, not one boundary for each island plus the peninsula. That's why we're using the "Dissolved" county boundaries.

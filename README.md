Dispatchmaps
============

Files for mapping hands on that will go an inch deep on a wide variety of geo-topics, from GIS to some simple online mapping.

Outline

- Stories using mapping
- Intro to GIS
	* Census for shapefiles
- Chloropleths
    * Census block groups
- Joins
    * Census blocks
- Making addresses geography
    * Sex offenders
    * Political donors
- Hex bins
- Fusion tables
- Leaflet

<H3>WHY WE CARE ABOUT GIS</h3>
Geographic information systems allow us to do spatial analyses. GIS lets us <a href="http://www.nytimes.com/2013/01/03/us/a-soaring-homicide-rate-a-divide-in-chicago.html?_r=1&">quantify disparities between neighborhoods</a>, 

Maybe the thing that makes it most different, though, is GIS' ability to let us switch together disparate data sources to find correlations. The Seattle Times' <a href="http://seattletimes.com/flatpages/specialreports/methadone/methadonestollhigherinpoorerareas.html">found a connection between poverty and methadone<a>, for example.

<h3>CHLOROPLETHS</h3>


<h3>MAKING ADDRESSES GEOGRAPHY</h3>
Shapefiles are great, but often, geographic data comes in a different format: As a big pile of addresses. Addresses aren't natively geographic, but we can turn them into a shapefile through a process called geocoding.

A QGIS plugin called XYTools can map these results.

<h3>HEX BINS</h3>
A big blob of points is a pretty daunting thing. It doesn't communicate a whole lot, except to say  "Gee there are a lot of points!" or "Gee there are a lot more in this place than this one over here."

Enter geometric binning. The idea is to take points and group them into repeating, equal shapes. We seem to have converged on <a href="http://graphics.latimes.com/how-fast-is-lafd/#11/34.0495/-118.6002">hexagon bins</a>. 

QGIS has a downloadable plugin called "mmqgis" that lets us make them easy peasy. 

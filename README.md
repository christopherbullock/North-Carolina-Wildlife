# North-Carolina-Wildlife
A repository created for MAP671, specifically a map of North Carolina and areas with enough acreage for specific wildlife species.

**Project Title: North Carolina Red Wolf Habitat Map**

Information to be used in the map includes, A basemap used for census information and a basemap of north carolina, 2010 urban coverage shapefiles to represent urban sprawl, and North Carolina natural areas to represent suitable habitat for wildlife species.

**NC Natural Areas:** https://ncnhde.natureserve.org/content/data-download

**2010 Urban Coverage Shapefiles:** https://data-nconemap.opendata.arcgis.com/datasets/2010-census-urban-areas/explore?location=36.053871%2C-76.586937%2C9.60

**NC State Geography:** https://www.census.gov/geographies/mapping-files/time-series/geo/cartographic-boundary.html

Steps to Creation:
1) Take the base map template you want and filter it to the target area.
2) Upload mapping files above to create a raw data set of all information in QGIS.
3) Select target wildlife animal and find a suitable habitat acreage for them, for example my subject is red wolves in North Carolina.  Though I could not find a set in stone allowable acreage, an acceptable range for them was 8-30,000 acres.  As such I used 15,000 as a rounded middle point.
4) To show the difference in areas, I chose styles to represent urban areas, natural areas, and natural areas suited for red wolf habitat.
5) Upload tile data to mapbox and edit styles/zoom distances to show intended data.


I created this map for the interest in applying it to wildlife species currently present and possibly present in the state of North Carolina. I want find a baseline using something such as White Tailed Deer which are widespread throughout the United States and apply this same system later to other species such as endangered birds of prey or bat species that are unique and nessicary for a functional natural ecosystem. Creation of this map is achieved by creating the map files in QGIS and Adding layers that show the original natural landscape and filtering out areas that do not meet the requisite acreage to support different animals.


**Visit the full map! https://christopherbullock.github.io/North-Carolina-Wildlife/**

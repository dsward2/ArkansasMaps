# ArkansasMaps
## A repository of free, open-source Arkansas map data in GeoTIFF format, designed to quickly find the map name for the USGS 7.5 minute topo map at your current location - without wireless data access.

### Arkansas County Maps with USGS 7.5-Minute Topo Quad Index in GeoTIFF format

**Arkansas_Topo_Index_grid_with_highways.tif** is a georeferenced map of Arkansas showing all 75 county boundaries overlaid with the complete index grid for USGS 7.5-minute topographic maps. Each grid cell is labeled with its official quad name — there are 874 of them covering the state. The background is ESRI's World Topo layer showing shaded relief, roads, and contours.

The map is a GeoTIFF (EPSG:3857) built from official data sources: Census TIGER for county boundaries and the USGS National Map Indices geodatabase for the quad grid. It's designed to load in QField on a phone so you can see your GPS location relative to which topo quad you're standing in — handy for hiking, hunting, or any fieldwork where you're cross-referencing paper topo maps.

**Arkansas_Topo_Index_simple_grid.tif** is a similar map, but without the raster map of highways in the background.

This screenshot shows the map displayed in [QField.app](https://github.com/opengisch/QField) on an iPhone.  The user's location is marked on the map, based on the live GPS coordinates of the iPhone's current locaton.  The grid for that location shows that the USGS 7.5 minute topographical map is named "Conway".

![Screenshot of an iPhone running QField.app, showing a map of Arkansas with the user's location marked in Conway.](topo-screenshot.png)

### Hi-Res Maps for QField.app on iPhone or Android

**Arkansas_QField_USGS_Topo_Finder.zip** - This bundle of four maps for the QField mobile app provides a variety of high-resolution raster backgrounds that are helpful for finding topo maps.  The background images are previewed below:

![Background tile options for background map.](Arkansas_tile_options.jpg)

This screenshot shows how QField allows selection of index cells and counties, which are identified in a result table on screen.

![QField-demo-map.](QField-demo.jpg)

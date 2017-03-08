# Terrain Generator And Server (TGS)
TGS is a software that produces terrain data to be served primarily for [CesiumJS](cesiumjs.org) library.

TGS is written in Javascript just like Cesium itself. Cross platform and easy to install and planned to be free of 
Blog about the project [HERE](http://blog.terrainserver.com/).

You can preview live demo [HERE](http://www.terrainserver.com/) 

You can get the source DEM data used for the showcase Heightmap [HERE](http://naturalearth.springercarto.com/ne3_data/dem_large.zip)

You can get the source DEM data used for the showcase Quantized Mesh [HERE](https://lta.cr.usgs.gov/GTOPO30)

Try dataset on newest Cesium Version [HERE] (http://cesiumjs.org/Cesium/Apps/Sandcastle/?src=Hello%20World.html&label=Showcases&gist=35700c25799f93225d0c521a20272d7e)

Comments and inputs are quite welcome. You can follow progress from issues and here

## Latest News (21.02.2017)

Everest and wide around it has been generated using SRTM 30 data. You can check it out from and compare it with the STK Terrain [HERE]  (http://cesiumjs.org/Cesium/Apps/Sandcastle/?src=Hello%20World.html&label=Showcases&gist=35700c25799f93225d0c521a20272d7e)
.

Now there is a blog about this project which will get updates more frequently [HERE](http://blog.terrainserver.com/).

Currently there are 2 datasets in Heightmap and QuantizedMesh format.

Quantized Mesh dataset is derived from GTOPO30 sources. It has 1km resolution approx. for the whole world and i believe this tileset is identical with the Cesium one. They have added more data onto it so might be slight differences.

This dataset is detailed up to LEVEL 9  and consists of nearly 700K tile files. I have added this whole tileset available for download.

You can download [GTOPO30 Quantized Mesh Tileset](https://dl.dropboxusercontent.com/s/mplbvp84qtw6kko/Gtopo30QuantizedMesh.zip)

Here are a few scenes that shows tile details. You can browse live demo from the link up.

![Quantized Mesh Rendered Papua](https://dl.dropboxusercontent.com/s/f9dvgh7nwjpms60/6.png?dl=0)

## Features

CTGAS is usable at the moment as it is and have following features

1. **Heightmap** format terrain tile generation
2. **Quantized Mesh** format terrain tile generation
3. **KML** format terrain tile generation
4. Mesh Simplification Algorithm for tile generation
5. Multicore tile generation support
6. Tile Server in order to serve produced tiles


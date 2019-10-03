# Sandbox

For experimenting with cave survey data

## Fake survex data 

This has a spiral so that the passage crosses over itself.  It is
geolocated so that the entrance is under the track down to Bull Pot
Farm (BPF) ... ha ha!  Also provided is a cropped digital elevation model
(DEM) and a georeferenced cropped aerial image to match. The DEM is
taken from the OS Terrain 50 data set, (c) Crown Copyright and
database rights 2019.

### Files

- `bpf_fake_cave.svx` : survex file for fake cave survey data
- `bpf_fake_cave.3d` : processed cave survey data

- `bpf_fake_cave.gpkg` : cave survey data exported to GeoPackage format (*)
- `bpf_aerial_clipped.tif` : aerial image of BPF as GeoTIFF
- `bpf_dem_clipped.tif` : DEM as GeoTIFF
- `bpf_fake_cave.qgz` : QGIS3 project file containing the above

(*) using the `.3d` to QGIS3 import filter described elsewhere ...

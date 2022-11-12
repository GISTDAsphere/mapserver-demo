Put some data here


Sample commands:

apt update

apt install gdal-bin 

gdalwarp -srcnodata 0 -dstalpha -dstnodata None -of GTiff -co "TFW=YES" -t_srs EPSG:3857 world.topo.bathy.200407.3_21600_108001.tif out-3857.tif

gdal2tiles.py --processes=4 -z 1-8 -s EPSG:900913 out-3857.tif tiles


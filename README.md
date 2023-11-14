# headwall_classification

Files and descriptions


arr_clean_nopca: 3d tif with no geospatial information

bathy_subset: 2d raster with depth in m (datum = NAVD88)

headwall_gb_subset_zmask: 3d geotif with full spectral data masked deeper than 5m NAVD88

headwall_gb_subset_zmask_clean: 3d geotif with removed wavelengths that contain NaN values. Current wavelength range 453 - 728 nm

sacfor_raster_binkelp: 2d raster (no geospatial info) of binary kelp classification. 1 = SACFOR 4 and 5, 0 = SACFOR < 4

sacfor_raster_fewkelp: 2d raster (no geospatial info) of limited SACFOR kelp classification. 2 = SACFOR 4/5, 1 = SACFOR 2/3, 0 = SACFOR 0/1

sacfor_raster_kelp: 2d raster (no geospatial info) of full SACFOR kelp classification

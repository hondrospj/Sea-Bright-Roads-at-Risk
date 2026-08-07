# Sea Bright Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through a municipal 5-foot Sea Bright DEM.

The interface and features match the Seaside Heights Roads at Risk platform: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01407600, Sea Bright
- PETSS / NOAA station: 8531804, Sea Bright
- NAVD88 thresholds: 3.07 ft minor, 4.07 ft moderate, 5.07 ft major
- MLLW thresholds: 5.20 ft minor, 6.20 ft moderate, 7.20 ft major
- MLLW = NAVD88 + 2.13 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Sea Bright boundary and resampled to 1.524 m / 5 ft pixels.

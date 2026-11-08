# Pagosa River & Snow

Live gauge height and flow for the San Juan River at Pagosa Springs, CO (USGS 09342500 / NWS PSPC2),
with NWS flood stages, the NWS forecast, the normal range for the date, Wolf Creek Summit snowpack
(NRCS SNOTEL 874), and an estimated flood-width map built from 2018 USGS LiDAR.

Site: https://elwood67.github.io/san-juan-river/

Unofficial. For flood safety, follow the Town of Pagosa Springs, Archuleta County and the
[NWS gauge page](https://water.noaa.gov/gauges/PSPC2).

- Readings come straight from USGS and NWS in the visitor's browser; if USGS is down, NWS's copy of the same gauge is used.
- The normal range comes from USGS daily statistics, converted to feet with the current USGS rating curve.
- Snowpack (water and depth) comes from NRCS SNOTEL; the depth normal is a median of the station's 1998-2026 daily readings.
- `map/` holds the flood-width layers produced by `river_width.py` (height-above-nearest-drainage model, 4-30 ft).

## Copyright

© 2026 Dave Tuggle. All rights reserved.

The code, design, flood-width map and text in this repository are not licensed for reuse or redistribution
without permission. The river, forecast and snowpack data shown on the site are public-domain US government
data from USGS, NWS and NRCS.

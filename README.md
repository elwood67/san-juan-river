# San Juan at Pagosa

Live gauge height and flow for the San Juan River at Pagosa Springs, CO (USGS 09342500 / NWS PSPC2),
with NWS flood stages, the NWS forecast, and an estimated flood-width map built from 2018 USGS LiDAR.

Unofficial. For flood safety, follow the Town of Pagosa Springs, Archuleta County and the
[NWS gauge page](https://water.noaa.gov/gauges/PSPC2).

- Readings come straight from USGS and NWS in the visitor's browser; if USGS is down, NWS's copy of the same gauge is used.
- `map/` holds the flood-width layers produced by `river_width.py` (height-above-nearest-drainage model, 4-30 ft).

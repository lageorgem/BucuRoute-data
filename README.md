# CityRoute public transit and routing data

Daily generated data consumed by the private CityRoute Android app. `osm-routing-manifest.json` is the authority for each routing artifact's source timestamp, SHA-256 checksum, byte size, and download URL.

Shared walking routing for all CityCatalog cities is published as `all_city_walk.crpg` with its access index `all_city_access_points.json`; `bucharest_rail.crrg` contains Bucharest rail routing.

Transit feeds are `gtfs/brasov.zip` and `gtfs/satumare.zip`, with weekday-specific snapshots in `gtfs/brasov-days/` and `gtfs/satumare-days/` (`monday.zip` through `sunday.zip`).

Map data © OpenStreetMap contributors, available under the [Open Database License](https://www.openstreetmap.org/copyright). GTFS data is sourced from public transport operators; no license is asserted here.

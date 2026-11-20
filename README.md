# Rockford Area Crash Map

An initiative of I Bike Rockford, a volunteer group. A web map of fatal and serious-injury crashes in Rockford and Winnebago County, Illinois, built from Illinois Department of Transportation (IDOT) crash data (Rockford 2006-2025, county 2014-2025), with person-level facts about fatal crashes from the federal FARS database.

This is a static website: open `index.html` through any web server. Nothing here is an official City of Rockford, Region 1 Planning Council or IDOT product.

- `index.html`, `css/`, `js/`: the site
- `data/ka.json`: fatal and serious-injury crashes (loads first)
- `data/other.json`: minor, possible and no-injury crashes (loads on request)
- `data/arterials.json`, `data/hin.json`, `data/boundaries.json`, `data/addresses.json`: roads, high-injury network, area boundaries and address search
- `downloads/`: the crash files, described on the site's Data page
- `vendor/leaflet`: Leaflet 1.9.4 (BSD-2-Clause)

Map tiles: CARTO / OpenStreetMap contributors; Esri World Imagery for the satellite option. Address search uses OpenStreetMap Nominatim.

Questions and corrections: ibikerockford@gmail.com

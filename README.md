# lsc-voting-boundaries

Initial Idea: Let user discover which schools they can run for an LSC or vote for an LSC.

Process Ideas:
1. Make all boundary data geoJSON (dedupe attendance boundary data?)
2. Leaflet + Turf.js + Google Maps
3. User enters address (or geolocate). Google geocoder geocodes address & shows on map
4. Turf.js determines which polygons the point is in
5. Page displays school names ++ (links, type of school, other stuff?)

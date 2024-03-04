# Spain Postal Codes
This repo contains a dataset of Spanish postal codes with coordinates (latitud/longitude). 

You can query the post codes list with centroid (lat, lng) directly from https://raw.githubusercontent.com/kodens-dev/Spain-Postal-Codes/main/postcodes-centroid.csv 

You can also download a zip file from the Releases tab with:

* postcodes-centroid.csv: A list of postal codes with centroid (lat, lng)
* postcodes-geometry.csv: A list of postal codes with full polygon geometry in CSV format
* postcodes-geometry.geojson: A list of postal codes with full polygon geometry in [Geoson format](https://geojson.org/)
* postcodes-geometry-simplified-t*.geojson: As above but simplified using the [Ramer-Douglas-Peucker algorithm](https://en.wikipedia.org/wiki/Ramer%E2%80%93Douglas%E2%80%93Peucker_algorithm) for different tolerance in meters.

## Contributing
Please feel free to send your comments in the issues section.

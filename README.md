# json-geocoding-lookup

Produces a JSON static geocoding lookup

## Example

1. Download the "Statistical Area Level 1 (SA1) ASGS Ed 2016 Digital Boundaries in ESRI Shapefile Format" from http://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/1270.0.55.001July%202016?OpenDocument.
2. Unzip
3. `json-geocoding-lookup -i SA1_2016_AUST.shp -o SA1_2016_AUST.json -k SA1_7DIG16 -p 4`
4. Minify `json_reformat -m < SA1_2016_AUST.json > SA1_2016_AUST.min.json`


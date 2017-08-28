# pyaml: Place YAML (in concept phase)
## motto
You can be geospatial without longitude and latitude.

## eample
```yaml
jpn: 
  name: Japan
  area: 377972
```

## structure
```
ideentifiler:
  key1: value1
  key2: value2
```

## use case
- This pyaml file is loaded on a web map, especially one based on binary vector tiles. On tile loading, identifiers in pyaml are matched with the identifiers in the vector tile, and the k-v pair are appended to the internal expression of the geospatial data.
- More conventional use can be possible e.g. table-joined with geospatial data offline.

## aim
To liberate people from struggling with longitude and latitude.

# RawGeo

[![Build Status](https://travis-ci.org/tsileo/rawgeo.svg?branch=master)](https://travis-ci.org/tsileo/rawgeo)
&nbsp; &nbsp;[![Godoc Reference](https://godoc.org/a4.io/rawgeo?status.svg)](https://godoc.org/a4.io/rawgeo)

Building block for building geospatial indexes using geohashes.

## Features

- Use the Geohash algorithm to index and search data.
- Index (`lat`, `lng`, `ID`) data in a [kv](https://github.com/cznic/kv) file.
- Find nearest neighbors from `lag`, `lng` within a given `radius` sorted by distance.
- Don't designed to store data (should be handled by another component).


# tgn-geojson

The Getty Thesaurus of Geographic Names (TGN). As GeoJSON.

## This is a work in progress

Currently it consists of the simplest possible GeoJSON file containing

* A centroid
* An `id` property
* Zero or more `name:2-LETTER-LANGUAGE-CODE` properties
* A `hierarchy` property containing pointers to other TGN records
* A `placetype` property containing pointers to [AAT](http://www.getty.edu/research/tools/vocabularies/aat/) records

Complex geometries, concordances and other relevant data will be added as time and circumstance permit.

Patches and other contributions are welcome and encouraged.

## Known-knowns

* The files are plain-vanilla `Features` and not `FeatureCollections`
* There are a handful of records which were corrupted during one or more updates. They will be corrected in time.
* This is a freakishly large Git repository. Like too large to work with, really. Something will have to be done about that.

## License

This dataset contains information from the [Getty Thesaurus of Geographic Names (TGN)®](http://vocab.getty.edu/) which is made available under the [ODC Attribution License](http://opendatacommons.org/licenses/by/1.0/).

## See also

* http://vocab.getty.edu/
* http://blogs.getty.edu/iris/getty-thesaurus-of-geographic-names-released-as-linked-open-data/
* http://geojson.org/
* https://github.com/straup/tgn-tools

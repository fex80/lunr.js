# Lunr.js

> "A bit like Solr, but much smaller and not as bright."

Adapted from [olivernn/lunr.js](https://github.com/olivernn/lunr.js)

Probably, is not the package you are looking for. Please consider using the [upstream package](https://github.com/olivernn/lunr.js).


## Description

Lunr.js is a small, full-text search library.  It indexes JSON documents and provides a simple search interface for retrieving documents that best match text queries.


* [API documentation](https://lunrjs.com/docs/index.html) 
* [Working example](https://olivernn.github.io/moonwalkers/)


## Contributing

Please consider contributing to the upstream project.

## Releasing

* update types in `index.d.ts` as needed
* update version in file `/VERSION`
* update changelog in `/CHANGELOG`
* `make clean all release`
    * Note: Vulnerabilities usually don't matter as we only have dev dependencies
* `./build/release.sh`

# npmdoc-aerospike

#### api documentation for  [aerospike (v2.5.2)](https://github.com/aerospike/aerospike-client-nodejs)  [![npm package](https://img.shields.io/npm/v/npmdoc-aerospike.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-aerospike) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-aerospike.svg)](https://travis-ci.org/npmdoc/node-npmdoc-aerospike)

#### Aerospike Client Library

[![NPM](https://nodei.co/npm/aerospike.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/aerospike)

- [https://npmdoc.github.io/node-npmdoc-aerospike/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-aerospike/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-aerospike/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-aerospike/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-aerospike/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-aerospike/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/aerospike/aerospike-client-nodejs/issues"
    },
    "cpu": [
        "x64"
    ],
    "dependencies": {
        "nan": "~2.3.0",
        "webworker-threads": "^0.7"
    },
    "description": "Aerospike Client Library",
    "devDependencies": {
        "deasync": "^0.1.4",
        "expect.js": "^0.3",
        "ink-docstrap": "^1.1.0",
        "jsdoc": "^3.4.0",
        "mocha": "^3.0",
        "standard": "^9.0",
        "yargs": "1.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "fe48e37915972681a25667143e9029c0b0b7235b",
        "tarball": "https://registry.npmjs.org/aerospike/-/aerospike-2.5.2.tgz"
    },
    "engines": {
        "node": ">=0.12"
    },
    "gypfile": true,
    "homepage": "https://github.com/aerospike/aerospike-client-nodejs",
    "license": "Apache-2.0",
    "main": "lib/aerospike",
    "maintainers": [
        {
            "name": "aerospike"
        },
        {
            "name": "chris-aerospike.com"
        },
        {
            "name": "jhecking-aerospike"
        }
    ],
    "name": "aerospike",
    "optionalDependencies": {
        "webworker-threads": "^0.7"
    },
    "os": [
        "linux",
        "darwin"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/aerospike/aerospike-client-nodejs.git"
    },
    "scripts": {
        "apidocs": "jsdoc -c jsdoc.json",
        "install": "node-gyp rebuild",
        "preversion": "npm test",
        "test": "standard && ./scripts/shuffle_tests"
    },
    "standard": {
        "ignore": [
            "apidocs"
        ]
    },
    "tags": [
        "aerospike",
        "database",
        "nosql"
    ],
    "version": "2.5.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

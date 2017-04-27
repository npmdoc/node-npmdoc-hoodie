# npmdoc-hoodie

#### basic api documentation for  [hoodie (v28.1.0)](https://github.com/hoodiehq/hoodie#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-hoodie.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-hoodie) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-hoodie.svg)](https://travis-ci.org/npmdoc/node-npmdoc-hoodie)

#### A generic backend with a client API for Offline First applications

[![NPM](https://nodei.co/npm/hoodie.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hoodie)

- [https://npmdoc.github.io/node-npmdoc-hoodie/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hoodie/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hoodie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hoodie/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-hoodie/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-hoodie/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "The Hoodie Community"
    },
    "bin": {
        "hoodie": "./bin/start.js"
    },
    "bugs": {
        "url": "https://github.com/hoodiehq/hoodie/issues"
    },
    "dependencies": {
        "@hoodie/admin": "^1.0.1",
        "@hoodie/client": "^10.0.0",
        "@hoodie/server": "^23.0.0",
        "async": "^2.0.0",
        "browserify": "^14.0.0",
        "good": "^7.0.2",
        "good-squeeze": "^5.0.0",
        "h2o2": "^5.1.0",
        "hapi": "^16.0.0",
        "hapi-cors-headers": "^1.0.0",
        "inert": "^4.0.0",
        "lodash": "^4.11.2",
        "mkdirp": "^0.5.1",
        "node-emoji": "^1.3.0",
        "npmlog": "^4.0.0",
        "pouchdb-adapter-fs": "^2.0.5",
        "pouchdb-adapter-http": "^6.0.4",
        "pouchdb-adapter-memory": "^6.0.4",
        "pouchdb-browser": "^6.0.7",
        "pouchdb-core": "^6.0.4",
        "pouchdb-mapreduce": "^6.0.6",
        "rc": "^1.1.6",
        "semver": "^5.1.0",
        "yargs": "^6.0.0"
    },
    "description": "A generic backend with a client API for Offline First applications",
    "devDependencies": {
        "coveralls": "^2.11.9",
        "nock": "^9.0.0",
        "nyc": "^10.1.0",
        "proxyquire": "^1.7.4",
        "request": "^2.72.0",
        "semantic-release": "^6.3.1",
        "simple-mock": "^0.7.0",
        "standard": "^9.0.0",
        "tap": "^10.0.0",
        "textlint": "^6.8.0",
        "textlint-rule-common-misspellings": "^1.0.1",
        "textlint-rule-no-dead-link": "^3.1.1",
        "textlint-rule-rousseau": "^1.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "04e828950cde0b75be4c06d6dae654c27b795faf",
        "tarball": "https://registry.npmjs.org/hoodie/-/hoodie-28.1.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "b848323599b512a0ef9297948c6df6a3147bf395",
    "homepage": "https://github.com/hoodiehq/hoodie#readme",
    "keywords": [
        "nobackend",
        "offlinefirst"
    ],
    "license": "Apache-2.0",
    "main": "server/index.js",
    "maintainers": [
        {
            "name": "boennemann"
        },
        {
            "name": "caolan"
        },
        {
            "name": "gr2m"
        },
        {
            "name": "hoodie"
        },
        {
            "name": "jan"
        },
        {
            "name": "svnlto"
        }
    ],
    "name": "hoodie",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hoodiehq/hoodie.git"
    },
    "scripts": {
        "coverage": "nyc report --reporter=text-lcov | coveralls",
        "postinstall": "node ./bin/setup.js",
        "pretest": "standard",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "start": "./bin/start.js",
        "test": "nyc tap --no-cov ./test/{unit,integration}/**/*-test.js",
        "textlint": "textlint docs/**/*.md README.md"
    },
    "version": "28.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

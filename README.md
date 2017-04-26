# npmdoc-pg-pubsub

#### basic api documentation for  [pg-pubsub (v0.3.0)](http://github.com/voxpelli/node-pg-pubsub)  [![npm package](https://img.shields.io/npm/v/npmdoc-pg-pubsub.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pg-pubsub) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pg-pubsub.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pg-pubsub)

#### A Publish/Subscribe implementation on top of PostgreSQL NOTIFY/LISTEN

[![NPM](https://nodei.co/npm/pg-pubsub.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pg-pubsub)

- [https://npmdoc.github.io/node-npmdoc-pg-pubsub/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pg-pubsub/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pg-pubsub/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pg-pubsub/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pg-pubsub/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pg-pubsub/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Pelle Wessman",
        "url": "http://kodfabrik.se/"
    },
    "bugs": {
        "url": "https://github.com/voxpelli/node-pg-pubsub/issues"
    },
    "dependencies": {
        "pg": "^4.4.1",
        "pg-format": "^1.0.2",
        "promised-retry": "^0.2.1"
    },
    "description": "A Publish/Subscribe implementation on top of PostgreSQL NOTIFY/LISTEN",
    "devDependencies": {
        "chai": "^3.2.0",
        "chai-as-promised": "^5.3.0",
        "coveralls": "^2.11.3",
        "dotenv": "^1.2.0",
        "grunt": "^0.4.5",
        "husky": ">=0.7.0 <0.10.0-0",
        "istanbul": "^0.3.4",
        "lintlovin": "github:voxpelli/lintlovin#1.x",
        "mocha": "^2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "aed719c002fc92a7383fa1bbc4442ca5180ec5bf",
        "tarball": "https://registry.npmjs.org/pg-pubsub/-/pg-pubsub-0.3.0.tgz"
    },
    "engines": {
        "iojs": "*",
        "node": ">=0.12.0"
    },
    "gitHead": "cea31df1f221280d2373115f4fe4576df585fd2a",
    "homepage": "http://github.com/voxpelli/node-pg-pubsub",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "voxpelli"
        }
    ],
    "name": "pg-pubsub",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/voxpelli/node-pg-pubsub.git"
    },
    "scripts": {
        "prepush": "npm test",
        "test": "node -e \"require('grunt').tasks(['test-all']);\"",
        "test-all": "node -e \"require('grunt').tasks(['test-all']);\""
    },
    "version": "0.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

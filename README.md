# npmdoc-winston-mongodb

#### basic api documentation for  [winston-mongodb (v2.0.9)](https://github.com/indexzero/winston-mongodb#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-winston-mongodb.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-winston-mongodb) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-winston-mongodb.svg)](https://travis-ci.org/npmdoc/node-npmdoc-winston-mongodb)

#### A MongoDB transport for winston

[![NPM](https://nodei.co/npm/winston-mongodb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/winston-mongodb)

- [https://npmdoc.github.io/node-npmdoc-winston-mongodb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-winston-mongodb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-winston-mongodb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-winston-mongodb/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-winston-mongodb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-winston-mongodb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Charlie Robbins"
    },
    "bugs": {
        "url": "https://github.com/indexzero/winston-mongodb/issues"
    },
    "contributors": [
        {
            "name": "Yurij Mikhalevich",
            "url": "https://39.yt/"
        },
        {
            "name": "Kendrick Taylor"
        },
        {
            "name": "Steve Dalby"
        }
    ],
    "dependencies": {
        "mongodb": "^2.2.19"
    },
    "description": "A MongoDB transport for winston",
    "devDependencies": {
        "vows": "~0.8.1",
        "winston": ">=1.1.1 <3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5392315a33454087e5eaa8f0f5d85f2e82c75e0c",
        "tarball": "https://registry.npmjs.org/winston-mongodb/-/winston-mongodb-2.0.9.tgz"
    },
    "engines": {
        "node": ">=6.8.1"
    },
    "gitHead": "81ace5eae3ad27b9153e7d9227f44953aff8a7e2",
    "homepage": "https://github.com/indexzero/winston-mongodb#readme",
    "keywords": [
        "logging",
        "sysadmin",
        "tools",
        "winston",
        "mongodb",
        "log",
        "logger"
    ],
    "license": "MIT",
    "main": "./lib/winston-mongodb",
    "maintainers": [
        {
            "name": "indexzero"
        },
        {
            "name": "chjj"
        },
        {
            "name": "39dotyt"
        }
    ],
    "name": "winston-mongodb",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/indexzero/winston-mongodb.git"
    },
    "scripts": {
        "test": "vows test/*-test.js --spec",
        "test-rs": "WINSTON_MONGODB_URL='mongodb://localhost:27017,localhost:27018/winston?replicaSet=rs0' vows test/*-test.js --spec"
    },
    "typings": "./lib/winston-mongodb.d.ts",
    "version": "2.0.9",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

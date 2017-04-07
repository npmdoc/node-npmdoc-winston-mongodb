# api documentation for  [winston-mongodb (v2.0.8)](https://github.com/indexzero/winston-mongodb#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-winston-mongodb.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-winston-mongodb) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-winston-mongodb.svg)](https://travis-ci.org/npmdoc/node-npmdoc-winston-mongodb)
#### A MongoDB transport for winston

[![NPM](https://nodei.co/npm/winston-mongodb.png?downloads=true)](https://www.npmjs.com/package/winston-mongodb)

[![apidoc](https://npmdoc.github.io/node-npmdoc-winston-mongodb/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-winston-mongodb_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-winston-mongodb/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-winston-mongodb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-winston-mongodb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Charlie Robbins",
        "email": "charlie.robbins@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/indexzero/winston-mongodb/issues"
    },
    "contributors": [
        {
            "name": "Yurij Mikhalevich",
            "email": "0@39.yt",
            "url": "https://39.yt/"
        },
        {
            "name": "Kendrick Taylor",
            "email": "sktayloriii@gmail.com"
        },
        {
            "name": "Steve Dalby",
            "email": "steve@stevedalby.co.uk"
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
        "shasum": "79c8e98bb2b09eb222ffe31361967bf912cbf9b9",
        "tarball": "https://registry.npmjs.org/winston-mongodb/-/winston-mongodb-2.0.8.tgz"
    },
    "engines": {
        "node": ">=6.8.1"
    },
    "gitHead": "74fd60260aca1caf0810bfb3845a0571511d8ede",
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
            "name": "indexzero",
            "email": "charlie.robbins@gmail.com"
        },
        {
            "name": "chjj",
            "email": "chjjeffrey@gmail.com"
        },
        {
            "name": "39dotyt",
            "email": "0@39.yt"
        }
    ],
    "name": "winston-mongodb",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/indexzero/winston-mongodb.git"
    },
    "scripts": {
        "test": "vows test/*-test.js --spec",
        "test-rs": "WINSTON_MONGODB_URL='mongodb://localhost:27017,localhost:27018/winston?replicaSet=rs0' vows test/*-test.js --spec"
    },
    "typings": "./lib/winston-mongodb.d.ts",
    "version": "2.0.8"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module winston-mongodb](#apidoc.module.winston-mongodb)



# <a name="apidoc.module.winston-mongodb"></a>[module winston-mongodb](#apidoc.module.winston-mongodb)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

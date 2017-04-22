# npmdoc-minecraft-protocol

#### api documentation for  [minecraft-protocol (v1.1.3)](https://github.com/PrismarineJS/node-minecraft-protocol#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-minecraft-protocol.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-minecraft-protocol) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-minecraft-protocol.svg)](https://travis-ci.org/npmdoc/node-npmdoc-minecraft-protocol)

#### Parse and serialize minecraft packets, plus authentication and encryption.

[![NPM](https://nodei.co/npm/minecraft-protocol.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/minecraft-protocol)

- [https://npmdoc.github.io/node-npmdoc-minecraft-protocol/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-minecraft-protocol/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-minecraft-protocol/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-minecraft-protocol/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-minecraft-protocol/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-minecraft-protocol/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrew Kelley"
    },
    "browser": "src/browser.js",
    "bugs": {
        "url": "https://github.com/PrismarineJS/node-minecraft-protocol/issues"
    },
    "dependencies": {
        "buffer-equal": "^1.0.0",
        "debug": "^2.2.0",
        "endian-toggle": "^0.0.0",
        "lodash.get": "^4.1.2",
        "lodash.merge": "^4.3.0",
        "minecraft-data": "^2.11.0",
        "prismarine-nbt": "^1.0.0",
        "protodef": "^1.3.0",
        "readable-stream": "^2.0.5",
        "ursa": "^0.9.1",
        "ursa-purejs": "^0.0.3",
        "uuid-1345": "^0.99.6",
        "yggdrasil": "^0.2.0"
    },
    "description": "Parse and serialize minecraft packets, plus authentication and encryption.",
    "devDependencies": {
        "espower-loader": "^1.0.0",
        "intelli-espower-loader": "^1.0.0",
        "minecraft-wrap": "^1.0.0",
        "mocha": "^3.0.2",
        "power-assert": "^1.0.0",
        "require-self": "^0.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b5ab06f03f81793082df4c83118bd91a7667448f",
        "tarball": "https://registry.npmjs.org/minecraft-protocol/-/minecraft-protocol-1.1.3.tgz"
    },
    "engines": {
        "node": ">=6"
    },
    "gitHead": "1683d212147f6dba1123e51e3e62e57c719df8c9",
    "homepage": "https://github.com/PrismarineJS/node-minecraft-protocol#readme",
    "keywords": [
        "minecraft",
        "protocol",
        "parse",
        "serialize",
        "packet",
        "authentication",
        "encrypton",
        "bot"
    ],
    "license": "BSD-3-Clause",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "dcbartlett"
        },
        {
            "name": "mappum"
        },
        {
            "name": "roblabla"
        },
        {
            "name": "rom1504"
        },
        {
            "name": "superjoe"
        },
        {
            "name": "wtfaremyinitials"
        },
        {
            "name": "zuazo"
        }
    ],
    "name": "minecraft-protocol",
    "optionalDependencies": {
        "ursa": "^0.9.1"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/PrismarineJS/node-minecraft-protocol.git"
    },
    "scripts": {
        "prepublish": "require-self",
        "test": "mocha --recursive --reporter spec"
    },
    "version": "1.1.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

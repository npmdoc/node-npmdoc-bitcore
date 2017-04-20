# npmdoc-bitcore

#### api documentation for  bitcore (v4.1.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-bitcore.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bitcore) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bitcore.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bitcore)

#### A platform to build bitcoin and blockchain-based applications.

[![NPM](https://nodei.co/npm/bitcore.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bitcore)

- [https://npmdoc.github.io/node-npmdoc-bitcore/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bitcore/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bitcore/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bitcore/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-bitcore/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-bitcore/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "bitcore",
    "version": "4.1.0",
    "description": "A platform to build bitcoin and blockchain-based applications.",
    "author": "BitPay <dev@bitpay.com>",
    "main": "index.js",
    "scripts": {
        "test": "./node_modules/.bin/mocha test/** --recursive",
        "build-deb": "./scripts/build-deb"
    },
    "bin": {
        "bitcore": "./bin/bitcore",
        "bitcored": "./bin/bitcored"
    },
    "contributors": [
        {
            "name": "Daniel Cousens"
        },
        {
            "name": "Esteban Ordano"
        },
        {
            "name": "Gordon Hall"
        },
        {
            "name": "Jeff Garzik"
        },
        {
            "name": "Kyle Drake"
        },
        {
            "name": "Manuel Araoz"
        },
        {
            "name": "Matias Alejo Garcia"
        },
        {
            "name": "Ryan X. Charles"
        },
        {
            "name": "Stefan Thomas"
        },
        {
            "name": "Stephen Pair"
        },
        {
            "name": "Wei Lu"
        }
    ],
    "keywords": [
        "bitcoin",
        "transaction",
        "address",
        "p2p",
        "ecies",
        "cryptocurrency",
        "blockchain",
        "payment",
        "bip21",
        "bip32",
        "bip37",
        "bip69",
        "bip70",
        "multisig"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/bitpay/bitcore.git"
    },
    "browser": {
        "request": "browser-request"
    },
    "dependencies": {
        "bitcore-lib": "^0.13.14",
        "bitcore-node": "~3.1.0",
        "insight-api": "^0.4.0",
        "insight-ui": "^0.4.0"
    },
    "license": "MIT",
    "devDependencies": {
        "chai": "^3.3.0",
        "mocha": "^2.3.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

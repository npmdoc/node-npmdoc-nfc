# npmdoc-nfc

#### api documentation for  nfc (v0.3.3)  [![npm package](https://img.shields.io/npm/v/npmdoc-nfc.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nfc) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nfc.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nfc)

#### Node NFC functionallity through libnfc

[![NPM](https://nodei.co/npm/nfc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nfc)

- [https://npmdoc.github.io/node-npmdoc-nfc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nfc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nfc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nfc/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nfc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nfc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nfc",
    "version": "0.3.3",
    "description": "Node NFC functionallity through libnfc",
    "main": "index.js",
    "scripts": {
        "test": "node test.js",
        "install": "node-gyp clean configure rebuild"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/Camme/node-nfc.git"
    },
    "keywords": [
        "nfc"
    ],
    "dependencies": {
        "ndef": "0.1.2",
        "bindings": "1.2.1",
        "nan": "2.3.5",
        "node-gyp": "3.0.3"
    },
    "author": "Camilo Tapia <camilo.tapia@gmail.com>",
    "maintainers": [
        {
            "name": "Jeroen Vollenbrock",
            "url": "http://athom.nl"
        }
    ],
    "license": "MIT",
    "gypfile": true
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

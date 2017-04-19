# npmdoc-mout

#### api documentation for  [mout (v1.0.0)](http://moutjs.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-mout.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mout) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mout.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mout)

#### Modular Utilities

[![NPM](https://nodei.co/npm/mout.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mout)

- [https://npmdoc.github.io/node-npmdoc-mout/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mout/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mout/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mout/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mout/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Miller Medeiros",
        "url": "http://blog.millermedeiros.com"
    },
    "bugs": {
        "url": "https://github.com/mout/mout/issues/"
    },
    "contributors": [
        {
            "name": "Adam Nowotny"
        },
        {
            "name": "André Cruz"
        },
        {
            "name": "Conrad Zimmerman",
            "url": "http://www.conradz.com"
        },
        {
            "name": "Friedemann Altrock"
        },
        {
            "name": "Igor Almeida"
        },
        {
            "name": "Jarrod Overson",
            "url": "http://jarrodoverson.com"
        },
        {
            "name": "Mathias Paumgarten"
        },
        {
            "name": "Zach Shipley"
        }
    ],
    "dependencies": {},
    "description": "Modular Utilities",
    "devDependencies": {
        "commander": "~1.0.5",
        "handlebars": "~1.0.6",
        "istanbul": "~0.1.27",
        "jasmine-node": "~1.14.5",
        "jshint": "~2.9.1",
        "mdoc": "~0.3.2",
        "nodefy": "*",
        "regenerate": "~0.5.4",
        "requirejs": "~2.2.0",
        "rimraf": "~2.5.2",
        "rocambole": "~0.2.3"
    },
    "directories": {
        "doc": "./doc"
    },
    "dist": {
        "shasum": "9bdf1d4af57d66d47cb353a6335a3281098e1501",
        "tarball": "https://registry.npmjs.org/mout/-/mout-1.0.0.tgz"
    },
    "gitHead": "2ff20539568bfe53b8c1da521cd743cf0ba79c2a",
    "homepage": "http://moutjs.com/",
    "keywords": [
        "utilities",
        "functional",
        "amd-utils",
        "stdlib"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "millermedeiros"
        },
        {
            "name": "satazor"
        },
        {
            "name": "conradz"
        },
        {
            "name": "mathias.paumgarten"
        }
    ],
    "name": "mout",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mout/mout.git"
    },
    "scripts": {
        "pretest": "node build pkg",
        "test": "istanbul test tests/runner.js --hook-run-in-context"
    },
    "testling": {
        "preprocess": "node build testling",
        "browsers": {
            "ie": [
                7,
                8,
                9,
                10
            ],
            "firefox": [
                17,
                "nightly"
            ],
            "chrome": [
                23,
                "canary"
            ],
            "opera": [
                12,
                "next"
            ],
            "safari": [
                5.1,
                6
            ],
            "iphone": [
                6
            ],
            "ipad": [
                6
            ]
        },
        "scripts": [
            "tests/lib/jasmine/jasmine.js",
            "tests/lib/jasmine/jasmine.async.js",
            "tests/lib/jasmine/jasmine-tap.js",
            "tests/lib/requirejs/require.js",
            "tests/testling/src.js",
            "tests/testling/specs.js",
            "tests/runner.js"
        ]
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

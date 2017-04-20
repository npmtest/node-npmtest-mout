# npmtest-mout

#### basic test coverage for  [mout (v1.0.0)](http://moutjs.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-mout.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mout) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mout.svg)](https://travis-ci.org/npmtest/node-npmtest-mout)

#### Modular Utilities

[![NPM](https://nodei.co/npm/mout.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mout)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mout/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mout/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mout/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mout/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mout/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mout/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mout/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mout/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mout/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mout/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mout/build/test-report.html](https://npmtest.github.io/node-npmtest-mout/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mout/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mout/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mout/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mout/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mout/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mout/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "mout",
    "description": "Modular Utilities",
    "version": "1.0.0",
    "homepage": "http://moutjs.com/",
    "author": "Miller Medeiros <contact@millermedeiros.com> (http://blog.millermedeiros.com)",
    "contributors": [
        "Adam Nowotny",
        "André Cruz <amdfcruz@gmail.com>",
        "Conrad Zimmerman (http://www.conradz.com)",
        "Friedemann Altrock <frodenius@gmail.com>",
        "Igor Almeida <igor.p.almeida@gmail.com>",
        "Jarrod Overson (http://jarrodoverson.com)",
        "Mathias Paumgarten <mail@mathias-paumgarten.com>",
        "Zach Shipley"
    ],
    "keywords": [
        "utilities",
        "functional",
        "amd-utils",
        "stdlib"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/mout/mout.git"
    },
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/mout/mout/issues/"
    },
    "main": "./index.js",
    "scripts": {
        "pretest": "node build pkg",
        "test": "istanbul test tests/runner.js --hook-run-in-context"
    },
    "directories": {
        "doc": "./doc"
    },
    "devDependencies": {
        "istanbul": "~0.1.27",
        "jasmine-node": "~1.14.5",
        "requirejs": "~2.2.0",
        "nodefy": "*",
        "mdoc": "~0.3.2",
        "handlebars": "~1.0.6",
        "commander": "~1.0.5",
        "rocambole": "~0.2.3",
        "jshint": "~2.9.1",
        "rimraf": "~2.5.2",
        "regenerate": "~0.5.4"
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
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

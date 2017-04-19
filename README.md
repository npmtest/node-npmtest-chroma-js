# npmtest-chroma-js

#### test coverage for  [chroma-js (v1.3.3)](https://github.com/gka/chroma.js)  [![npm package](https://img.shields.io/npm/v/npmtest-chroma-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-chroma-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-chroma-js.svg)](https://travis-ci.org/npmtest/node-npmtest-chroma-js)

#### JavaScript library for color conversions

[![NPM](https://nodei.co/npm/chroma-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/chroma-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-chroma-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-chroma-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-chroma-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-chroma-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-chroma-js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-chroma-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-chroma-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-chroma-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-chroma-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-chroma-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-chroma-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-chroma-js/build/test-report.html](https://npmtest.github.io/node-npmtest-chroma-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-chroma-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-chroma-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-chroma-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-chroma-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-chroma-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-chroma-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-chroma-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-chroma-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gregor Aisch"
    },
    "bugs": {
        "url": "https://github.com/gka/chroma.js/issues"
    },
    "dependencies": {},
    "description": "JavaScript library for color conversions",
    "devDependencies": {
        "catty": "github:gka/catty#coffeescript",
        "coffee-script": "1.9.2",
        "es6-shim": "^0.18.0",
        "grunt": "^0.4.5",
        "grunt-contrib-clean": "^0.6.0",
        "grunt-contrib-coffee": "^0.13.0",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-uglify": "^0.9.1",
        "grunt-replace": "^0.9.2",
        "minimatch": "^3.0.2",
        "uglify-js": "2.x",
        "vows": "0.8.x"
    },
    "directories": {},
    "dist": {
        "shasum": "91b3a2b3856c18443ebd8c9719faea108b56263b",
        "tarball": "https://registry.npmjs.org/chroma-js/-/chroma-js-1.3.3.tgz"
    },
    "gitHead": "7b47b1deccd95a7c97bee44efbf3a06a32443459",
    "homepage": "https://github.com/gka/chroma.js",
    "keywords": [
        "color"
    ],
    "main": "chroma.js",
    "maintainers": [
        {
            "name": "celtra"
        },
        {
            "name": "gka"
        }
    ],
    "name": "chroma-js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/gka/chroma.js.git"
    },
    "scripts": {
        "build": "grunt",
        "test": "./node_modules/vows/bin/vows --dot-matrix"
    },
    "spm": {
        "main": "chroma.js",
        "ignore": [
            "src",
            "doc",
            "test"
        ]
    },
    "version": "1.3.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

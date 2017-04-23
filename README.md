# npmtest-jpegtran-bin

#### basic test coverage for  [jpegtran-bin (v3.2.0)](https://github.com/imagemin/jpegtran-bin#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-jpegtran-bin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jpegtran-bin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jpegtran-bin.svg)](https://travis-ci.org/npmtest/node-npmtest-jpegtran-bin)

#### jpegtran (part of libjpeg-turbo) bin-wrapper that makes it seamlessly available as a local dependency

[![NPM](https://nodei.co/npm/jpegtran-bin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jpegtran-bin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jpegtran-bin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jpegtran-bin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jpegtran-bin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jpegtran-bin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jpegtran-bin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jpegtran-bin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jpegtran-bin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jpegtran-bin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jpegtran-bin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jpegtran-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jpegtran-bin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jpegtran-bin/build/test-report.html](https://npmtest.github.io/node-npmtest-jpegtran-bin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jpegtran-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jpegtran-bin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jpegtran-bin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jpegtran-bin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jpegtran-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jpegtran-bin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jpegtran-bin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jpegtran-bin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "bin": {
        "jpegtran": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/imagemin/jpegtran-bin/issues"
    },
    "dependencies": {
        "bin-build": "^2.0.0",
        "bin-wrapper": "^3.0.0",
        "logalot": "^2.0.0"
    },
    "description": "jpegtran (part of libjpeg-turbo) bin-wrapper that makes it seamlessly available as a local dependency",
    "devDependencies": {
        "bin-check": "^3.0.0",
        "compare-size": "^1.0.1",
        "mkdirp": "^0.5.0",
        "mocha": "^2.2.4",
        "rimraf": "^2.3.2",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "f60ecf4ae999c0bdad2e9fbcdf2b6f0981e7a29b",
        "tarball": "https://registry.npmjs.org/jpegtran-bin/-/jpegtran-bin-3.2.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "cli.js",
        "lib",
        "test"
    ],
    "gitHead": "8f7752a5f77d1b7a3c7112bf048a8c65e3dcbc4c",
    "homepage": "https://github.com/imagemin/jpegtran-bin#readme",
    "keywords": [
        "compress",
        "image",
        "img",
        "jpeg",
        "jpg",
        "minify",
        "optimize"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "sindresorhus"
        },
        {
            "name": "kevva"
        },
        {
            "name": "shinnn"
        }
    ],
    "name": "jpegtran-bin",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/imagemin/jpegtran-bin.git"
    },
    "scripts": {
        "postinstall": "node lib/install.js",
        "test": "xo && mocha --timeout 100000"
    },
    "version": "3.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

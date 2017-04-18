# npmtest-gulp-util

#### test coverage for  [gulp-util (v3.0.8)](https://github.com/gulpjs/gulp-util#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-util.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-util) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-util.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-util)

#### Utility functions for gulp plugins

[![NPM](https://nodei.co/npm/gulp-util.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-util)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-util/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-util/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-util/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-util/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-util/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-util/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-util/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-util/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-util/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-util/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-util/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-util/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-util/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-util/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-util/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-util/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-util/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-util/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-util/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-util/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-util/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Fractal",
        "url": "http://wearefractal.com/"
    },
    "bugs": {
        "url": "https://github.com/gulpjs/gulp-util/issues"
    },
    "dependencies": {
        "array-differ": "^1.0.0",
        "array-uniq": "^1.0.2",
        "beeper": "^1.0.0",
        "chalk": "^1.0.0",
        "dateformat": "^2.0.0",
        "fancy-log": "^1.1.0",
        "gulplog": "^1.0.0",
        "has-gulplog": "^0.1.0",
        "lodash._reescape": "^3.0.0",
        "lodash._reevaluate": "^3.0.0",
        "lodash._reinterpolate": "^3.0.0",
        "lodash.template": "^3.0.0",
        "minimist": "^1.1.0",
        "multipipe": "^0.1.2",
        "object-assign": "^3.0.0",
        "replace-ext": "0.0.1",
        "through2": "^2.0.0",
        "vinyl": "^0.5.0"
    },
    "description": "Utility functions for gulp plugins",
    "devDependencies": {
        "buffer-equal": "^0.0.1",
        "coveralls": "^2.11.2",
        "event-stream": "^3.1.7",
        "istanbul": "^0.3.5",
        "istanbul-coveralls": "^1.0.1",
        "jshint": "^2.5.11",
        "lodash.templatesettings": "^3.0.0",
        "mocha": "^2.0.1",
        "rimraf": "^2.2.8",
        "should": "^7.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "0054e1e744502e27c04c187c3ecc505dd54bbb4f",
        "tarball": "https://registry.npmjs.org/gulp-util/-/gulp-util-3.0.8.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "28c2aa2a3f8782a995b47ed051ab52885c705024",
    "homepage": "https://github.com/gulpjs/gulp-util#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "contra"
        },
        {
            "name": "fractal"
        },
        {
            "name": "phated"
        }
    ],
    "name": "gulp-util",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gulpjs/gulp-util.git"
    },
    "scripts": {
        "coveralls": "istanbul cover _mocha --report lcovonly && istanbul-coveralls",
        "test": "jshint *.js lib/*.js test/*.js && mocha"
    },
    "version": "3.0.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

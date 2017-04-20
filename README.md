# npmtest-es6-promise

#### basic test coverage for  es6-promise (v4.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-es6-promise.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-es6-promise) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-es6-promise.svg)](https://travis-ci.org/npmtest/node-npmtest-es6-promise)

#### A lightweight library that provides tools for organizing asynchronous code

[![NPM](https://nodei.co/npm/es6-promise.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/es6-promise)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-es6-promise/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-es6-promise/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-es6-promise/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-es6-promise/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-es6-promise/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-es6-promise/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-es6-promise/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-es6-promise/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-es6-promise/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-es6-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-es6-promise/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-es6-promise/build/test-report.html](https://npmtest.github.io/node-npmtest-es6-promise/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-es6-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-es6-promise/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-es6-promise/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-es6-promise/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-es6-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-es6-promise/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-es6-promise/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-es6-promise/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "es6-promise",
    "namespace": "es6-promise",
    "version": "4.1.0",
    "description": "A lightweight library that provides tools for organizing asynchronous code",
    "main": "dist/es6-promise.js",
    "typings": "es6-promise.d.ts",
    "directories": {
        "lib": "lib"
    },
    "files": [
        "dist",
        "lib",
        "es6-promise.d.ts",
        "auto.js",
        "!dist/test"
    ],
    "devDependencies": {
        "broccoli-babel-transpiler": "^5.6.1",
        "broccoli-concat": "^3.1.0",
        "broccoli-merge-trees": "^1.2.3",
        "broccoli-rollup": "^1.0.2",
        "broccoli-stew": "^1.2.0",
        "broccoli-uglify-js": "^0.2.0",
        "broccoli-watchify": "^1.0.1",
        "ember-cli": "2.12.0-beta.1",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-publisher": "0.0.7",
        "git-repo-version": "0.4.1",
        "json3": "^3.3.2",
        "mocha": "^3.1.0",
        "promises-aplus-tests-phantom": "^2.1.0-revise",
        "release-it": "2.6.0"
    },
    "scripts": {
        "build": "ember build --environment production",
        "build:production": "ember build --env production",
        "start": "ember s",
        "test": "ember test",
        "test:server": "ember test --server",
        "test:node": "ember build && mocha ./dist/test/browserify",
        "prepublish": "ember build --environment production",
        "lint": "jshint lib",
        "dry-run-release": "ember build --environment production && release-it --dry-run --non-interactive"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/stefanpenner/es6-promise.git"
    },
    "bugs": {
        "url": "https://github.com/stefanpenner/es6-promise/issues"
    },
    "browser": {
        "vertx": false
    },
    "keywords": [
        "promises",
        "futures"
    ],
    "author": "Yehuda Katz, Tom Dale, Stefan Penner and contributors (Conversion to ES6 API by Jake Archibald)",
    "license": "MIT",
    "spm": {
        "main": "dist/es6-promise.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

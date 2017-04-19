# npmtest-css-loader

#### test coverage for  [css-loader (v0.28.0)](https://github.com/webpack/css-loader#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-css-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-css-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-css-loader.svg)](https://travis-ci.org/npmtest/node-npmtest-css-loader)

#### css loader module for webpack

[![NPM](https://nodei.co/npm/css-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/css-loader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-css-loader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-css-loader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-css-loader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-css-loader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-css-loader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-css-loader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-css-loader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-css-loader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-css-loader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-css-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-css-loader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-css-loader/build/test-report.html](https://npmtest.github.io/node-npmtest-css-loader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-css-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-css-loader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-css-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-css-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-css-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-css-loader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-css-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-css-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tobias Koppers @sokra"
    },
    "bugs": {
        "url": "https://github.com/webpack/css-loader/issues"
    },
    "dependencies": {
        "babel-code-frame": "^6.11.0",
        "css-selector-tokenizer": "^0.7.0",
        "cssnano": ">=2.6.1 <4",
        "loader-utils": "^1.0.2",
        "lodash.camelcase": "^4.3.0",
        "object-assign": "^4.0.1",
        "postcss": "^5.0.6",
        "postcss-modules-extract-imports": "^1.0.0",
        "postcss-modules-local-by-default": "^1.0.1",
        "postcss-modules-scope": "^1.0.0",
        "postcss-modules-values": "^1.1.0",
        "source-list-map": "^0.1.7"
    },
    "description": "css loader module for webpack",
    "devDependencies": {
        "codecov": "^1.0.1",
        "eslint": "3.14.0",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "should": "^11.1.2",
        "standard-version": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "417cfa9789f8cde59a30ccbf3e4da7a806889bad",
        "tarball": "https://registry.npmjs.org/css-loader/-/css-loader-0.28.0.tgz"
    },
    "engines": {
        "node": ">=0.12.0 || >=4.3.0 <5.0.0 || >=5.10"
    },
    "files": [
        "index.js",
        "locals.js",
        "lib"
    ],
    "gitHead": "2f562f8c3a8a222dd3a5d66b44e219e5b2e8fd2f",
    "homepage": "https://github.com/webpack/css-loader#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "bebraw"
        },
        {
            "name": "d3viant0ne"
        },
        {
            "name": "ericclemmons"
        },
        {
            "name": "jhnns"
        },
        {
            "name": "markdalgleish"
        },
        {
            "name": "sokra"
        },
        {
            "name": "spacek33z"
        },
        {
            "name": "thelarkinn"
        }
    ],
    "name": "css-loader",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/webpack/css-loader.git"
    },
    "scripts": {
        "cover": "istanbul cover node_modules/mocha/bin/_mocha",
        "lint": "eslint lib test",
        "release": "yarn run standard-version",
        "test": "mocha",
        "test:cover": "npm run cover -- --report lcovonly",
        "travis:lint": "npm run lint",
        "travis:test": "npm run cover"
    },
    "version": "0.28.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

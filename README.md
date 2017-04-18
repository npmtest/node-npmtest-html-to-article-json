# npmtest-html-to-article-json

#### test coverage for  [html-to-article-json (v1.20.1)](https://github.com/micnews/html-to-article-json#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-html-to-article-json.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-html-to-article-json) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-html-to-article-json.svg)](https://travis-ci.org/npmtest/node-npmtest-html-to-article-json)

#### Converting HTML to article-json

[![NPM](https://nodei.co/npm/html-to-article-json.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/html-to-article-json)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-html-to-article-json/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-to-article-json/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-html-to-article-json/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-html-to-article-json/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-html-to-article-json/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-html-to-article-json/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-html-to-article-json/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-html-to-article-json/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-html-to-article-json/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-to-article-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-html-to-article-json/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-html-to-article-json/build/test-report.html](https://npmtest.github.io/node-npmtest-html-to-article-json/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-html-to-article-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-html-to-article-json/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-html-to-article-json/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-html-to-article-json/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-html-to-article-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-html-to-article-json/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-html-to-article-json/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-html-to-article-json/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "mic.com"
    },
    "bugs": {
        "url": "https://github.com/micnews/html-to-article-json/issues"
    },
    "dependencies": {
        "block-elements": "^1.1.0",
        "embedly-url": "^1.0.0",
        "embeds": "^2.6.0",
        "es6-set": "^0.1.2",
        "generate-function": "^2.0.0",
        "get-youtube-id": "^1.0.0",
        "lodash.find": "^4.2.0",
        "lodash.last": "^3.0.0",
        "lodash.map": "^4.2.0",
        "lodash.startswith": "^4.0.0",
        "lodash.values": "^4.1.0",
        "query-dom": "^3.0.0"
    },
    "description": "Converting HTML to article-json",
    "devDependencies": {
        "babel-cli": "^6.4.5",
        "babel-plugin-static-fs": "^1.1.0",
        "babel-preset-es2015": "^6.3.13",
        "babel-tape-runner": "^2.0.0",
        "babelify": "^7.2.0",
        "beefy": "^2.1.5",
        "browserify": "^13.0.0",
        "faucet": "0.0.1",
        "nyc": "^8.1.0",
        "pre-commit": "^1.1.1",
        "semistandard": "^9.0.0",
        "snazzy": "^5.0.0",
        "tape": "^4.4.0",
        "tape-catch": "^1.0.4",
        "tape-run": "^2.1.4",
        "testron": "^1.2.0",
        "tsml": "^1.0.1",
        "watchify": "^3.4.0"
    },
    "directories": {
        "example": "example",
        "test": "test"
    },
    "dist": {
        "shasum": "948a2ebdf8f254347265d640bb6bfe905ff9dbf0",
        "tarball": "https://registry.npmjs.org/html-to-article-json/-/html-to-article-json-1.20.1.tgz"
    },
    "gitHead": "f79e2cff55c1649e35ab444be443e41988ee54b4",
    "homepage": "https://github.com/micnews/html-to-article-json#readme",
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "ellell"
        },
        {
            "name": "iefserge"
        },
        {
            "name": "kesla"
        },
        {
            "name": "ryanscottaudio"
        }
    ],
    "name": "html-to-article-json",
    "optionalDependencies": {},
    "pre-commit": [
        "test:coverage"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/micnews/html-to-article-json.git"
    },
    "scripts": {
        "benchmark": "babel-node benchmark/node.js",
        "build": "rm -rf dist && babel lib --out-dir dist",
        "example": "beefy example/client.js --index example/index.html --open -- --transform babelify",
        "lint": "semistandard | snazzy",
        "open-coverage": "npm run test:coverage && nyc report --reporter=lcov && open coverage/lcov-report/index.html",
        "postpublish": "rm -rf dist",
        "prepublish": "npm run build",
        "test": "npm run lint && npm run test:node && npm run test:coverage && npm run test:check-coverage && npm run test:browser",
        "test:browser": "browserify -t [babelify --presets [es2015] --plugins [static-fs] ] -d test/*-test.js | tape-run | faucet",
        "test:check-coverage": "nyc check-coverage --lines 100 --functions 100 --branches 100",
        "test:coverage": "nyc babel-tape-runner test/*-test.js",
        "test:node": "babel-tape-runner test/*-test.js"
    },
    "version": "1.20.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

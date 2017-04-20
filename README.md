# npmtest-apac

#### basic test coverage for  [apac (v3.0.2)](https://github.com/dmcquay/node-apac#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-apac.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-apac) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-apac.svg)](https://travis-ci.org/npmtest/node-npmtest-apac)

#### Amazon Product Advertising API Client for Node

[![NPM](https://nodei.co/npm/apac.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/apac)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-apac/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-apac/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-apac/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-apac/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-apac/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-apac/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-apac/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-apac/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-apac/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-apac/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-apac/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-apac/build/test-report.html](https://npmtest.github.io/node-npmtest-apac/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-apac/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-apac/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-apac/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-apac/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-apac/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-apac/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-apac/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-apac/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dustin McQuay"
    },
    "bugs": {
        "url": "http://github.com/dmcquay/node-apac/issues"
    },
    "dependencies": {
        "xml2js": "^0.4.17"
    },
    "description": "Amazon Product Advertising API Client for Node",
    "devDependencies": {
        "chai": "3.5.0",
        "dotenv": "4.0.0",
        "mocha": "3.2.0",
        "proxyquire": "1.7.10",
        "sinon": "1.17.7"
    },
    "directories": {
        "lib": "./lib/"
    },
    "dist": {
        "shasum": "1a0d6fddc0183ba4c66b6119082485d8c24f474f",
        "tarball": "https://registry.npmjs.org/apac/-/apac-3.0.2.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "32e520ac91b1e94706a59bdfe58584f806c0c852",
    "homepage": "https://github.com/dmcquay/node-apac#readme",
    "keywords": [
        "Amazon Product Advertising API",
        "AWS"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/dmcquay/node-apac/raw/master/LICENSE"
        }
    ],
    "main": "./lib/apac",
    "maintainers": [
        {
            "name": "dmcquay"
        },
        {
            "name": "wesleyyue"
        }
    ],
    "name": "apac",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dmcquay/node-apac.git"
    },
    "scripts": {
        "test": "mocha lib/*.specs.js",
        "test:acceptance": "mocha test/acceptance/*.specs.js || true"
    },
    "version": "3.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

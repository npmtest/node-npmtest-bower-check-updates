# npmtest-bower-check-updates

#### basic test coverage for  [bower-check-updates (v2.2.3-1)](https://github.com/se-panfilov/bower-check-updates)  [![npm package](https://img.shields.io/npm/v/npmtest-bower-check-updates.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bower-check-updates) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bower-check-updates.svg)](https://travis-ci.org/npmtest/node-npmtest-bower-check-updates)

#### Find newer versions of dependencies than what your bower.json allows

[![NPM](https://nodei.co/npm/bower-check-updates.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bower-check-updates)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bower-check-updates/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bower-check-updates/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bower-check-updates/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bower-check-updates/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bower-check-updates/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bower-check-updates/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bower-check-updates/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bower-check-updates/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bower-check-updates/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bower-check-updates/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bower-check-updates/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bower-check-updates/build/test-report.html](https://npmtest.github.io/node-npmtest-bower-check-updates/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bower-check-updates/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bower-check-updates/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bower-check-updates/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bower-check-updates/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bower-check-updates/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bower-check-updates/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bower-check-updates/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bower-check-updates/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "bower-check-updates",
    "version": "2.2.3-1",
    "authors": [
        "Tomas Junnonen <tomas1@gmail.com>",
        "Sergey Panfilov <se-panfilov@ya.ru> (https://se-panfilov.github.io)"
    ],
    "license": "MIT",
    "contributors": [
        "Raine Lourie (http://github.com/metaraine)"
    ],
    "description": "Find newer versions of dependencies than what your bower.json allows",
    "keywords": [
        "bower",
        "check",
        "find",
        "discover",
        "updates",
        "upgrades",
        "dependencies",
        "bower.json",
        "updater",
        "version",
        "management"
    ],
    "preferGlobal": true,
    "main": "./lib/bower-check-updates",
    "scripts": {
        "test": "mocha"
    },
    "bin": {
        "bower-check-updates": "./bin/old-alias",
        "bcu": "./bin/bower-check-updates"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/se-panfilov/bower-check-updates.git"
    },
    "homepage": "https://github.com/se-panfilov/bower-check-updates",
    "dependencies": {
        "async": "^1.4.0",
        "bluebird": "^2.9.34",
        "chalk": "^1.1.0",
        "cint": "^8.2.1",
        "cli-table": "^0.3.1",
        "closest-bower": "^1.1.4",
        "commander": "^2.8.1",
        "fast-diff": "^1.0.1",
        "get-stdin-promise": "^0.1.1",
        "lodash": "^3.10.0",
        "npm": "^2.13.1",
        "semver": "^5.0.1",
        "semver-utils": "metaraine/semver-utils.git#86ea225"
    },
    "devDependencies": {
        "chai": "^3.2.0",
        "chai-as-promised": "^5.1.0",
        "mocha": "^2.2.5",
        "should": "^7.0.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

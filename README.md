# npmtest-node-uglifier

#### basic test coverage for  [node-uglifier (v0.5.41)](https://github.com/zsoltszabo/node-uglifier)  [![npm package](https://img.shields.io/npm/v/npmtest-node-uglifier.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-uglifier) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-uglifier.svg)](https://travis-ci.org/npmtest/node-npmtest-node-uglifier)

#### Fully auto merging and uglifying a whole NodeJs project into one file with external files option. Thieves lose the module name and structure information, code runs faster. Makes deployement super easy!
Also now you can separate your dependencies!

[![NPM](https://nodei.co/npm/node-uglifier.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-uglifier)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-uglifier/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-uglifier/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-uglifier/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-uglifier/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-uglifier/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-node-uglifier/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-node-uglifier/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-uglifier/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-uglifier/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-uglifier/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-uglifier/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-uglifier/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-uglifier/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-uglifier/build/test-report.html](https://npmtest.github.io/node-npmtest-node-uglifier/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-uglifier/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-uglifier/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-uglifier/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-uglifier/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-uglifier/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-uglifier/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-uglifier/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-uglifier/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Zsolt Istvan Szabo"
    },
    "bugs": {
        "url": "https://github.com/zsoltszabo/node-uglifier/issues"
    },
    "contributors": [],
    "dependencies": {
        "fs-extra": "=2.0",
        "optparse": ">=0.x",
        "seedrandom": ">=0.x",
        "sugar": "=2.0.4",
        "uglify-js-harmony": "=2.6.2",
        "underscore": ">=1.5.2"
    },
    "description": "Fully auto merging and uglifying a whole NodeJs project into one file with external files option. Thieves lose the module name and structure information, code runs faster. Makes deployement super easy!\nAlso now you can separate your dependencies!",
    "devDependencies": {
        "express": "4.14.0",
        "nodeunit": "=0.10.2"
    },
    "directories": {},
    "dist": {
        "shasum": "2bdd0699eddcc417689f042439ce6dd614317b8f",
        "tarball": "https://registry.npmjs.org/node-uglifier/-/node-uglifier-0.5.41.tgz"
    },
    "engines": {
        "node": "> 0.6.0"
    },
    "gitHead": "f60dabe36ca86257b9b13ac5cf3d281d57cdce2f",
    "homepage": "https://github.com/zsoltszabo/node-uglifier",
    "keywords": [
        "obfuscate",
        "total",
        "whole",
        "project",
        "protect",
        "minify",
        "code protect",
        "uglify",
        "mangle",
        "compress",
        "automatic",
        "code separation",
        "separate dependencies",
        "sub project extraction"
    ],
    "main": "./index.js",
    "maintainers": [
        {
            "name": "arbitrager"
        }
    ],
    "name": "node-uglifier",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/zsoltszabo/node-uglifier.git"
    },
    "scripts": {
        "test": "node nodeunit.js ./lib_compiled/test/unitTest.js"
    },
    "url": "https://github.com/zsoltszabo/node-uglifier",
    "version": "0.5.41",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

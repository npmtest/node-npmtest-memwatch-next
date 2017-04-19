# npmtest-memwatch-next

#### basic test coverage for  [memwatch-next (v0.3.0)](https://github.com/marcominetti/node-memwatch#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-memwatch-next.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-memwatch-next) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-memwatch-next.svg)](https://travis-ci.org/npmtest/node-npmtest-memwatch-next)

#### Keep an eye on your memory usage, and discover and isolate leaks.

[![NPM](https://nodei.co/npm/memwatch-next.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/memwatch-next)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-memwatch-next/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-memwatch-next/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-memwatch-next/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-memwatch-next/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-memwatch-next/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-memwatch-next/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-memwatch-next/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-memwatch-next/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-memwatch-next/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-memwatch-next/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-memwatch-next/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-memwatch-next/build/test-report.html](https://npmtest.github.io/node-npmtest-memwatch-next/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-memwatch-next/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-memwatch-next/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-memwatch-next/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-memwatch-next/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-memwatch-next/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-memwatch-next/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-memwatch-next/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-memwatch-next/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lloyd Hilaiel",
        "url": "http://lloyd.io"
    },
    "bugs": {
        "url": "https://github.com/marcominetti/node-memwatch/issues"
    },
    "contributors": [
        {
            "name": "Jed Parsons",
            "url": "@jedp"
        },
        {
            "name": "Jeff Haynie",
            "url": "@jhaynie"
        },
        {
            "name": "Justin Matthews",
            "url": "@jmatthewsr-ms"
        }
    ],
    "dependencies": {
        "bindings": "^1.2.1",
        "nan": "^2.3.2"
    },
    "description": "Keep an eye on your memory usage, and discover and isolate leaks.",
    "devDependencies": {
        "mocha": "^2.4.5",
        "should": "^8.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "2111050f9a906e0aa2d72a4ec0f0089c78726f8f",
        "tarball": "https://registry.npmjs.org/memwatch-next/-/memwatch-next-0.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "23b2da5b986b9f6db776e4a236437500a6ddbf68",
    "gypfile": true,
    "homepage": "https://github.com/marcominetti/node-memwatch#readme",
    "licenses": [
        {
            "type": "wtfpl"
        }
    ],
    "main": "include.js",
    "maintainers": [
        {
            "name": "marcominetti"
        }
    ],
    "name": "memwatch-next",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/marcominetti/node-memwatch.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "mocha tests --reporter spec"
    },
    "version": "0.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

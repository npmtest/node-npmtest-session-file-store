# npmtest-session-file-store

#### test coverage for  [session-file-store (v1.0.0)](https://github.com/valery-barysok/session-file-store)  [![npm package](https://img.shields.io/npm/v/npmtest-session-file-store.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-session-file-store) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-session-file-store.svg)](https://travis-ci.org/npmtest/node-npmtest-session-file-store)

#### Session file store is a provision for storing session data in the session file

[![NPM](https://nodei.co/npm/session-file-store.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/session-file-store)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-session-file-store/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-session-file-store/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-session-file-store/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-session-file-store/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-session-file-store/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-session-file-store/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-session-file-store/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-session-file-store/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-session-file-store/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-session-file-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-session-file-store/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-session-file-store/build/test-report.html](https://npmtest.github.io/node-npmtest-session-file-store/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-session-file-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-session-file-store/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-session-file-store/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-session-file-store/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-session-file-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-session-file-store/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-session-file-store/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-session-file-store/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Valery Barysok"
    },
    "bugs": {
        "url": "https://github.com/valery-barysok/session-file-store/issues"
    },
    "contributors": [
        {
            "name": "Igor Svehla",
            "url": "wespen"
        },
        {
            "name": "Bill Christo",
            "url": "bchr02"
        },
        {
            "name": "Ryan Murphy",
            "url": "r-murphy"
        },
        {
            "name": "Norberth Danson",
            "url": "ndanson"
        },
        {
            "name": "Arnaud Bétrémieux",
            "url": "arnoo"
        },
        {
            "name": "Guson",
            "url": "gusonyang"
        },
        {
            "name": "Philipp Sporrer",
            "url": "PhilippSpo"
        },
        {
            "name": "Tyler Young",
            "url": "tyoung86"
        }
    ],
    "dependencies": {
        "bagpipe": "^0.3.5",
        "fs-extra": "^1.0.0",
        "retry": "^0.10.0",
        "write-file-atomic": "^1.1.4"
    },
    "description": "Session file store is a provision for storing session data in the session file",
    "devDependencies": {
        "cbor-sync": "^1.0.2",
        "chai": "^2.3.0",
        "coveralls": "^2.11.8",
        "istanbul": "^0.4.2",
        "lodash.clone": "^4.3.1",
        "mocha": "^2.3.3"
    },
    "directories": {},
    "dist": {
        "shasum": "17d6a1f4b548c4ce8a5b808d268637abeb46dcf4",
        "tarball": "https://registry.npmjs.org/session-file-store/-/session-file-store-1.0.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "files": [
        "lib/",
        "LICENSE",
        "README.md",
        "index.js"
    ],
    "gitHead": "8c7331997ba7c0f3884e6f8b77169c86b16aca9d",
    "homepage": "https://github.com/valery-barysok/session-file-store",
    "keywords": [
        "session",
        "file",
        "store",
        "express",
        "connect"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "valery-barysok"
        }
    ],
    "name": "session-file-store",
    "optionalDependencies": {},
    "private": false,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/valery-barysok/session-file-store.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-ci": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/",
        "test-cov": "istanbul cover ./node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-tap": "mocha --reporter tap --check-leaks test/"
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

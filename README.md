# test coverage for  [connect-mongodb-session (v1.3.0)](https://github.com/mongodb-js/connect-mongodb-session#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-connect-mongodb-session.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-connect-mongodb-session) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-connect-mongodb-session.svg)](https://travis-ci.org/npmtest/node-npmtest-connect-mongodb-session)
#### MongoDB session store for connect/express built by MongoDB

[![NPM](https://nodei.co/npm/connect-mongodb-session.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/connect-mongodb-session)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-connect-mongodb-session/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-connect-mongodb-session/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-connect-mongodb-session/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-connect-mongodb-session/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-connect-mongodb-session/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-connect-mongodb-session/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-connect-mongodb-session/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-connect-mongodb-session/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-connect-mongodb-session/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-connect-mongodb-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-connect-mongodb-session/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-connect-mongodb-session/build/test-report.html](https://npmtest.github.io/node-npmtest-connect-mongodb-session/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-connect-mongodb-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-connect-mongodb-session/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-connect-mongodb-session/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-connect-mongodb-session/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-connect-mongodb-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-connect-mongodb-session/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-connect-mongodb-session/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-connect-mongodb-session/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Valeri Karpov"
    },
    "bugs": {
        "url": "https://github.com/mongodb-js/connect-mongodb-session/issues"
    },
    "dependencies": {
        "mongodb": "~2.2.0"
    },
    "description": "MongoDB session store for connect/express built by MongoDB",
    "devDependencies": {
        "acquit": "0.1.0",
        "cookie": "0.1.2",
        "express": "4.10.4",
        "express-session": "1.9.2",
        "gulp": "3.8.10",
        "gulp-jscs": "1.4.0",
        "gulp-mocha": "2.0.0",
        "istanbul": "0.3.2",
        "jscs": "1.9.0",
        "mocha": "2.2.5",
        "request": "2.48.0",
        "strawman": "0.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "34e4e0b4157fda81b8d42f2a741ac4d7ef4ee4fa",
        "tarball": "https://registry.npmjs.org/connect-mongodb-session/-/connect-mongodb-session-1.3.0.tgz"
    },
    "engines": "node >= 0.10.0",
    "gitHead": "f48eeee491e0be41f86766888b31e92099f1a92e",
    "homepage": "https://github.com/mongodb-js/connect-mongodb-session#readme",
    "jscsConfig": {
        "preset": "airbnb",
        "requireMultipleVarDecl": null,
        "disallowMultipleVarDecl": true
    },
    "keywords": [
        "connect",
        "mongo",
        "mongodb",
        "session",
        "express"
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "vkarpov15"
        }
    ],
    "name": "connect-mongodb-session",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mongodb-js/connect-mongodb-session.git"
    },
    "scripts": {
        "test": "env NODE_PATH=../ ./node_modules/mocha/bin/mocha ./test/*.test.js",
        "test-travis": "env NODE_PATH=../ ./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha -- -R spec ./test/*.test.js",
        "unit-coverage": "env NODE_PATH=../ ./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha -- -R spec ./test/unit.test.js"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

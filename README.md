# npmtest-express-error-handler

#### basic test coverage for  [express-error-handler (v1.1.0)](https://github.com/dilvie/express-error-handler#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-express-error-handler.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-error-handler) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-error-handler.svg)](https://travis-ci.org/npmtest/node-npmtest-express-error-handler)

#### A graceful error handler for Express applications.

[![NPM](https://nodei.co/npm/express-error-handler.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-error-handler)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-error-handler/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-error-handler/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-error-handler/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-error-handler/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-error-handler/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-express-error-handler/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-express-error-handler/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-error-handler/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-error-handler/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-error-handler/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-error-handler/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-error-handler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-error-handler/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-error-handler/build/test-report.html](https://npmtest.github.io/node-npmtest-express-error-handler/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-error-handler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-error-handler/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-error-handler/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-error-handler/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-error-handler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-error-handler/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-error-handler/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-error-handler/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eric Elliott"
    },
    "bugs": {
        "url": "https://github.com/dilvie/express-error-handler/issues"
    },
    "dependencies": {
        "mout": "0.12.0"
    },
    "description": "A graceful error handler for Express applications.",
    "devDependencies": {
        "bunyan-request-logger": "1.0.2",
        "connect-cache-control": "1.0.0",
        "express": "^4.9.8",
        "grunt": "~0.4.1",
        "grunt-contrib-jshint": "1.0.0",
        "restify": "4.0.4",
        "supertest": "1.2.0",
        "tape": "4.5.1",
        "through": "~2.3.4",
        "updtr": "0.1.7",
        "watch": "0.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "ff2edb1fedcfcab1e601c60aab3554982f1f6497",
        "tarball": "https://registry.npmjs.org/express-error-handler/-/express-error-handler-1.1.0.tgz"
    },
    "gitHead": "610999b2263fcffefe4cb4daa1099fcbf670ca02",
    "homepage": "https://github.com/dilvie/express-error-handler#readme",
    "keywords": [
        "error",
        "errors",
        "handling",
        "handler",
        "express",
        "connect"
    ],
    "license": "MIT",
    "main": "error-handler.js",
    "maintainers": [
        {
            "name": "ericelliott"
        }
    ],
    "name": "express-error-handler",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/dilvie/express-error-handler.git"
    },
    "scripts": {
        "latest": "updtr",
        "lint": "grunt hint",
        "pretest": "npm run -s lint",
        "start-example": "node examples/app.js | bunyan",
        "test": "node ./test/runtests.js",
        "watch": "watch 'clear && npm run -s test' ."
    },
    "version": "1.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

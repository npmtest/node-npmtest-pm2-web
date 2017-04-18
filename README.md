# npmtest-pm2-web

#### test coverage for  [pm2-web (v2.1.3)](https://github.com/achingbrain/pm2-web)  [![npm package](https://img.shields.io/npm/v/npmtest-pm2-web.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pm2-web) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pm2-web.svg)](https://travis-ci.org/npmtest/node-npmtest-pm2-web)

#### A web based monitor for PM2

[![NPM](https://nodei.co/npm/pm2-web.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pm2-web)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pm2-web/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pm2-web/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pm2-web/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pm2-web/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pm2-web/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pm2-web/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pm2-web/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pm2-web/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pm2-web/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pm2-web/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pm2-web/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pm2-web/build/test-report.html](https://npmtest.github.io/node-npmtest-pm2-web/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pm2-web/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pm2-web/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pm2-web/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pm2-web/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pm2-web/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pm2-web/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pm2-web/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pm2-web/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "pm2-web": "bin/pm2-web.sh"
    },
    "bugs": {
        "url": "https://github.com/achingbrain/pm2-web/issues"
    },
    "dependencies": {
        "ansi-html": "~0.0.4",
        "cjson": "^0.3",
        "express": "^3.4",
        "html-entities": "^1.0",
        "jade": "^1.1",
        "mdns2": "^2.1.0",
        "method-override": "^2.1.2",
        "minimist": "^1.0",
        "moment": "^2.5",
        "mustache": "^0.8",
        "pm2-interface": "^2.0",
        "pwuid": "^1.0",
        "semver": "^3.0",
        "underscore.string": "^2.3",
        "wantsit": "^1.0",
        "wildemitter": "^1.0",
        "winston": "^0.7",
        "ws": "^0.4",
        "zepto-browserify": "^1.0"
    },
    "description": "A web based monitor for PM2",
    "devDependencies": {
        "coveralls": "^2.8",
        "grunt-browserify": "^2.0",
        "grunt-contrib-less": "^0.11",
        "grunt-contrib-watch": "^0.6",
        "istanbul": "^0.3",
        "nodeunit": "^0.9",
        "protractor": "^1.0",
        "proxyquire": "^1.0",
        "should": "^4.0",
        "sinon": "^1.8",
        "testsuite": "^1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9a5f5a0194f6f2a0cab2a83566c2ffa553fced6a",
        "tarball": "https://registry.npmjs.org/pm2-web/-/pm2-web-2.1.3.tgz"
    },
    "gitHead": "3150abd3374b2ff92e7cce3e11e2e07d34c88336",
    "homepage": "https://github.com/achingbrain/pm2-web",
    "keywords": [
        "pm2",
        "monitor",
        "web",
        "ui",
        "process"
    ],
    "main": "pm2-web.js",
    "maintainers": [
        {
            "name": "achingbrain"
        }
    ],
    "name": "pm2-web",
    "optionalDependencies": {
        "mdns2": "^2.1.0"
    },
    "preferGlobal": "true",
    "repository": {
        "type": "git",
        "url": "git://github.com/achingbrain/pm2-web.git"
    },
    "scripts": {
        "coveralls": "istanbul cover nodeunit test/unit && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js",
        "integration": "istanbul cover nodeunit test/integration",
        "test": "istanbul cover nodeunit test/unit"
    },
    "version": "2.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

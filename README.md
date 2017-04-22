# npmtest-strong-agent

#### basic test coverage for  [strong-agent (v2.1.2)](http://strongloop.com)  [![npm package](https://img.shields.io/npm/v/npmtest-strong-agent.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-strong-agent) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-strong-agent.svg)](https://travis-ci.org/npmtest/node-npmtest-strong-agent)

#### StrongOps Application Performance Monitoring Agent

[![NPM](https://nodei.co/npm/strong-agent.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/strong-agent)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-strong-agent/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-strong-agent/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-strong-agent/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-strong-agent/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-strong-agent/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-strong-agent/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-strong-agent/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-strong-agent/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-strong-agent/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-strong-agent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-strong-agent/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-strong-agent/build/test-report.html](https://npmtest.github.io/node-npmtest-strong-agent/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-strong-agent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-strong-agent/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-strong-agent/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-strong-agent/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-strong-agent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-strong-agent/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-strong-agent/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-strong-agent/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "StrongLoop"
    },
    "bugs": {
        "url": "https://github.com/strongloop/strong-agent/issues"
    },
    "contributors": [],
    "dependencies": {
        "debug": "^2.0.0",
        "promise-polyfill": "^5.2.1",
        "semver": "~2.2.1",
        "strong-license": "^1.2.0"
    },
    "description": "StrongOps Application Performance Monitoring Agent",
    "devDependencies": {
        "async": "~0.9.0",
        "bluebird": "^2.10.0",
        "express": "~3.3.5",
        "loopback": "^2.21.0",
        "loopback-connector-postgresql": "^2.3.0",
        "loopback-datasource-juggler": "^2.36.0",
        "memcache": "latest",
        "memcached": "latest",
        "mongodb": "latest",
        "mysql": "^2.7.0",
        "optional-dev-dependency": "1.3.0",
        "pg": "latest",
        "redis": "^2",
        "strong-express-metrics": "^1.0.1",
        "tap": "^0.4.13"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "48b0e67536836ecd0b2fd51ccfc84d2bd870a242",
        "tarball": "https://registry.npmjs.org/strong-agent/-/strong-agent-2.1.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "4b9dde08b79bd4c5a99fb9a00ade93c280981f41",
    "homepage": "http://strongloop.com",
    "keywords": [
        "apm",
        "monitoring",
        "performance",
        "profiling",
        "heap",
        "event loop",
        "analytics",
        "metrics",
        "alerts",
        "profiler",
        "response",
        "time",
        "memory",
        "slowest functions"
    ],
    "license": "SEE LICENSE IN LICENSE.md",
    "main": "lib/main",
    "maintainers": [
        {
            "name": "bajtos"
        },
        {
            "name": "bnoordhuis"
        },
        {
            "name": "chandadharap"
        },
        {
            "name": "ibmcloud-admin"
        },
        {
            "name": "kraman"
        },
        {
            "name": "nodefly"
        },
        {
            "name": "octet"
        },
        {
            "name": "rfeng"
        },
        {
            "name": "ritch"
        },
        {
            "name": "rmg"
        },
        {
            "name": "setogit"
        },
        {
            "name": "strongloop"
        },
        {
            "name": "superkhau"
        }
    ],
    "name": "strong-agent",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/strongloop/strong-agent.git"
    },
    "scripts": {
        "clang-format": "make clang-format",
        "install": "node-gyp rebuild || exit 0",
        "lint": "make -C src lint",
        "pretest": "optional-dev-dependency oracledb strong-oracle",
        "tap": "tap --tap --gc --stderr --timeout 30 test/test-*.js",
        "test": "npm run-script tap"
    },
    "version": "2.1.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

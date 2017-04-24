# npmtest-follow

#### basic test coverage for  [follow (v0.12.1)](http://github.com/iriscouch/follow)  [![npm package](https://img.shields.io/npm/v/npmtest-follow.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-follow) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-follow.svg)](https://travis-ci.org/npmtest/node-npmtest-follow)

#### Extremely robust, fault-tolerant CouchDB changes follower

[![NPM](https://nodei.co/npm/follow.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/follow)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-follow/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-follow/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-follow/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-follow/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-follow/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-follow/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-follow/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-follow/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-follow/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-follow/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-follow/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-follow/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-follow/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-follow/build/test-report.html](https://npmtest.github.io/node-npmtest-follow/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-follow/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-follow/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-follow/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-follow/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-follow/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-follow/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-follow/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-follow/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason Smith"
    },
    "bin": {
        "follow": "./cli.js"
    },
    "browser": {
        "request": "browser-request"
    },
    "bugs": {
        "url": "https://github.com/iriscouch/follow/issues"
    },
    "contributors": [
        {
            "name": "Jarrett Cruger"
        }
    ],
    "dependencies": {
        "browser-request": "~0.3.0",
        "debug": "^2.1.0",
        "request": "~2.55.0"
    },
    "description": "Extremely robust, fault-tolerant CouchDB changes follower",
    "devDependencies": {
        "tap": "~0.4.0",
        "traceback": "~0.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2c0efabbcd91613b0bb7382640f390ede8cab958",
        "tarball": "https://registry.npmjs.org/follow/-/follow-0.12.1.tgz"
    },
    "engines": {
        "node": "0.12.x || 0.10.x || 0.8.x"
    },
    "gitHead": "1d6a237fe6d8ce898b2242bba3e07f0d48076699",
    "homepage": "http://github.com/iriscouch/follow",
    "keywords": [
        "couchdb",
        "changes",
        "sleep",
        "sleepy"
    ],
    "license": "Apache 2.0",
    "main": "./api.js",
    "maintainers": [
        {
            "name": "jhs"
        },
        {
            "name": "jhs"
        },
        {
            "name": "jcrugzz"
        }
    ],
    "name": "follow",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/iriscouch/follow.git"
    },
    "scripts": {
        "test": "tap test/*.js"
    },
    "version": "0.12.1",
    "warnings": [
        {
            "code": "ENOTSUP",
            "required": {
                "node": "0.12.x || 0.10.x || 0.8.x"
            },
            "pkgid": "follow@0.12.1"
        },
        {
            "code": "ENOTSUP",
            "required": {
                "node": "0.12.x || 0.10.x || 0.8.x"
            },
            "pkgid": "follow@0.12.1"
        }
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

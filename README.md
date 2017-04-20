# npmtest-wechat-api

#### basic test coverage for  wechat-api (v1.32.1)  [![npm package](https://img.shields.io/npm/v/npmtest-wechat-api.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-wechat-api) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-wechat-api.svg)](https://travis-ci.org/npmtest/node-npmtest-wechat-api)

#### 微信公共平台Node库 API

[![NPM](https://nodei.co/npm/wechat-api.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wechat-api)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-wechat-api/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-wechat-api/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-wechat-api/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-wechat-api/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-wechat-api/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-wechat-api/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-wechat-api/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-wechat-api/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-wechat-api/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-wechat-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-wechat-api/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-wechat-api/build/test-report.html](https://npmtest.github.io/node-npmtest-wechat-api/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-wechat-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-wechat-api/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-wechat-api/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wechat-api/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wechat-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wechat-api/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-wechat-api/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-wechat-api/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "wechat-api",
    "version": "1.32.1",
    "description": "微信公共平台Node库 API",
    "main": "index.js",
    "scripts": {
        "test": "make test-all"
    },
    "config": {
        "travis-cov": {
            "threshold": 98
        }
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/node-webot/wechat-api.git"
    },
    "keywords": [
        "weixin",
        "wechat"
    ],
    "dependencies": {
        "formstream": ">=1.0.0",
        "urllib": "2.21.0"
    },
    "devDependencies": {
        "mocha": "*",
        "expect.js": "*",
        "travis-cov": "*",
        "coveralls": "*",
        "mocha-lcov-reporter": "*",
        "muk": "*",
        "rewire": "*",
        "istanbul": "*"
    },
    "author": "Jackson Tian",
    "license": "MIT",
    "readmeFilename": "README.md",
    "directories": {
        "test": "test"
    },
    "files": [
        "lib",
        "index.js"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

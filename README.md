# npmtest-twit

#### basic test coverage for  [twit (v2.2.5)](https://github.com/ttezel/twit)  [![npm package](https://img.shields.io/npm/v/npmtest-twit.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-twit) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-twit.svg)](https://travis-ci.org/npmtest/node-npmtest-twit)

#### Twitter API client for node (REST & Streaming)

[![NPM](https://nodei.co/npm/twit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/twit)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-twit/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-twit/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-twit/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-twit/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-twit/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-twit/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-twit/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-twit/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-twit/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-twit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-twit/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-twit/build/test-report.html](https://npmtest.github.io/node-npmtest-twit/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-twit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-twit/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-twit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-twit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-twit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-twit/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-twit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-twit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tolga Tezel"
    },
    "bugs": {
        "url": "https://github.com/ttezel/twit/issues"
    },
    "dependencies": {
        "bluebird": "^3.1.5",
        "mime": "^1.3.4",
        "request": "^2.68.0"
    },
    "description": "Twitter API client for node (REST & Streaming)",
    "devDependencies": {
        "async": "0.2.9",
        "colors": "0.6.x",
        "commander": "2.6.0",
        "mocha": "2.1.0",
        "rewire": "2.3.4",
        "sinon": "1.15.4"
    },
    "directories": {},
    "dist": {
        "shasum": "241480bab71731162d2a87b27450e4aa3bb5be5f",
        "tarball": "https://registry.npmjs.org/twit/-/twit-2.2.5.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "fa4d346fd564220e5dc41e8866fad3abb74b6479",
    "homepage": "https://github.com/ttezel/twit",
    "keywords": [
        "twitter",
        "api",
        "rest",
        "stream",
        "streaming",
        "oauth"
    ],
    "license": "MIT",
    "main": "./lib/twitter",
    "maintainers": [
        {
            "name": "ttezel"
        }
    ],
    "name": "twit",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/ttezel/twit.git"
    },
    "scripts": {
        "test": "mocha tests/* -t 70000 -R spec --bail --globals domain,_events,_maxListeners"
    },
    "version": "2.2.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

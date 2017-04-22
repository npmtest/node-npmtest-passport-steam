# npmtest-passport-steam

#### basic test coverage for  [passport-steam (v1.0.8)](https://github.com/liamcurry/passport-steam#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-passport-steam.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-passport-steam) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-passport-steam.svg)](https://travis-ci.org/npmtest/node-npmtest-passport-steam)

#### Steam (OpenID) authentication strategy for Passport.

[![NPM](https://nodei.co/npm/passport-steam.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/passport-steam)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-passport-steam/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-steam/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-passport-steam/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-passport-steam/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-passport-steam/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-passport-steam/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-passport-steam/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-passport-steam/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-passport-steam/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-steam/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-passport-steam/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-passport-steam/build/test-report.html](https://npmtest.github.io/node-npmtest-passport-steam/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-passport-steam/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-passport-steam/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-passport-steam/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-passport-steam/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-passport-steam/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-passport-steam/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-passport-steam/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-passport-steam/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Liam Curry",
        "url": "http://www.liamcurry.com/"
    },
    "ava": {
        "failFast": true,
        "verbose": true
    },
    "bugs": {
        "url": "http://github.com/liamcurry/passport-steam/issues"
    },
    "contributors": [
        {
            "name": "Toby Archer",
            "url": "http://github.com/mnzt"
        },
        {
            "name": "Welps",
            "url": "https://github.com/welps"
        }
    ],
    "dependencies": {
        "passport-openid": "^0.4.0",
        "steam-web": "0.4.0"
    },
    "description": "Steam (OpenID) authentication strategy for Passport.",
    "devDependencies": {
        "ava": "^0.10.0",
        "ejs": "^2.4.2",
        "express": "^4.14.0",
        "express-session": "^1.13.0",
        "passport": "^0.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "e30836b8215a62b1bb8c660ea2055e49c810edaa",
        "tarball": "https://registry.npmjs.org/passport-steam/-/passport-steam-1.0.8.tgz"
    },
    "engines": {
        "node": ">= 0.4.0"
    },
    "gitHead": "559ea32230ffc1bf7c8ec9563691a21622fecf2b",
    "homepage": "https://github.com/liamcurry/passport-steam#readme",
    "keywords": [
        "passport",
        "steam",
        "auth",
        "authn",
        "authentication",
        "identity"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://www.opensource.org/licenses/MIT"
        }
    ],
    "main": "./lib/passport-steam",
    "maintainers": [
        {
            "name": "liamcurry"
        },
        {
            "name": "mnzt"
        },
        {
            "name": "welps"
        }
    ],
    "name": "passport-steam",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/liamcurry/passport-steam.git"
    },
    "scripts": {
        "example": "node examples/signon/app.js",
        "example-router": "node examples/signon/app-router.js",
        "test": "ava test/*.test.js"
    },
    "version": "1.0.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

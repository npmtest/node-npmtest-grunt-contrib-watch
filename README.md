# test coverage for  [grunt-contrib-watch (v1.0.0)](https://github.com/gruntjs/grunt-contrib-watch)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-contrib-watch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-contrib-watch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-contrib-watch.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-contrib-watch)
#### Run predefined tasks whenever watched file patterns are added, changed or deleted

[![NPM](https://nodei.co/npm/grunt-contrib-watch.png?downloads=true)](https://www.npmjs.com/package/grunt-contrib-watch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-contrib-watch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-contrib-watch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-contrib-watch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-contrib-watch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-contrib-watch/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-contrib-watch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-contrib-watch/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-contrib-watch/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-grunt-contrib-watch/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-contrib-watch/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-grunt-contrib-watch%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-contrib-watch/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-contrib-watch/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-grunt-contrib-watch%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-contrib-watch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-contrib-watch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-contrib-watch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Grunt Team",
        "url": "http://gruntjs.com/"
    },
    "bugs": {
        "url": "https://github.com/gruntjs/grunt-contrib-watch/issues"
    },
    "contributors": [
        {
            "name": "Kyle Robinson Young",
            "url": "http://dontkry.com"
        },
        {
            "name": "\"Cowboy\" Ben Alman",
            "url": "http://benalman.com"
        },
        {
            "name": "Tyler Kellen",
            "url": "http://goingslowly.com"
        },
        {
            "name": "Gong Hao"
        },
        {
            "name": "Jaime Pillora"
        },
        {
            "name": "Chris Danford"
        },
        {
            "name": "Jason San Jose"
        },
        {
            "name": "Oleg Seletsky"
        },
        {
            "name": "Jamie Stackhouse"
        },
        {
            "name": "Chris Talkington"
        },
        {
            "name": "Oliver Joseph Ash"
        },
        {
            "name": "Iskren Chernev"
        },
        {
            "name": "Joey Baker"
        },
        {
            "name": "John K. Paul"
        },
        {
            "name": "Jurie-Jan Botha"
        },
        {
            "name": "Michał Gołębiowski"
        },
        {
            "name": "Willie V"
        },
        {
            "name": "cfddream"
        },
        {
            "name": "Chris Wren"
        },
        {
            "name": "Daniel Steigerwald"
        },
        {
            "name": "Rich Trott"
        }
    ],
    "dependencies": {
        "async": "^1.5.0",
        "gaze": "^1.0.0",
        "lodash": "^3.10.1",
        "tiny-lr": "^0.2.1"
    },
    "description": "Run predefined tasks whenever watched file patterns are added, changed or deleted",
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-internal": "^0.4.14",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-nodeunit": "^1.0.0",
        "grunt-jscs": "^2.8.0",
        "underscore.string": "^3.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "84a1a7a1d6abd26ed568413496c73133e990018f",
        "tarball": "https://registry.npmjs.org/grunt-contrib-watch/-/grunt-contrib-watch-1.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "tasks"
    ],
    "gitHead": "d3d8c01b25e0c759d76b236313cf49963983cb77",
    "homepage": "https://github.com/gruntjs/grunt-contrib-watch",
    "keywords": [
        "gruntplugin",
        "watch",
        "livereload"
    ],
    "license": "MIT",
    "main": "tasks/watch.js",
    "maintainers": [
        {
            "name": "tkellen",
            "email": "tyler@sleekcode.net"
        },
        {
            "name": "cowboy",
            "email": "cowboy@rj3.net"
        },
        {
            "name": "shama",
            "email": "kyle@dontkry.com"
        },
        {
            "name": "vladikoff",
            "email": "vlad@vladikoff.com"
        },
        {
            "name": "sindresorhus",
            "email": "sindresorhus@gmail.com"
        },
        {
            "name": "jmeas",
            "email": "jellyes2@gmail.com"
        }
    ],
    "name": "grunt-contrib-watch",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gruntjs/grunt-contrib-watch.git"
    },
    "scripts": {
        "test": "grunt test -v"
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

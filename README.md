# npmtest-youtube-dl

#### basic test coverage for  [youtube-dl (v1.11.1)](https://github.com/fent/node-youtube-dl)  [![npm package](https://img.shields.io/npm/v/npmtest-youtube-dl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-youtube-dl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-youtube-dl.svg)](https://travis-ci.org/npmtest/node-npmtest-youtube-dl)

#### youtube-dl driver for node

[![NPM](https://nodei.co/npm/youtube-dl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/youtube-dl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-youtube-dl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-youtube-dl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-youtube-dl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-youtube-dl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-youtube-dl/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-youtube-dl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-youtube-dl/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-youtube-dl/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-youtube-dl/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-youtube-dl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-youtube-dl/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-youtube-dl/build/test-report.html](https://npmtest.github.io/node-npmtest-youtube-dl/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-youtube-dl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-youtube-dl/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-youtube-dl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-youtube-dl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-youtube-dl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-youtube-dl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-youtube-dl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-youtube-dl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Roly Fentanes",
        "url": "https://github.com/fent"
    },
    "bugs": {
        "url": "https://github.com/fent/node-youtube-dl/issues"
    },
    "contributors": [
        {
            "name": "Przemyslaw Pluta",
            "url": "http://przemyslawpluta.com"
        }
    ],
    "dependencies": {
        "mkdirp": "^0.5.1",
        "request": "^2.69.0",
        "streamify": "~0.2.3"
    },
    "description": "youtube-dl driver for node",
    "devDependencies": {
        "vows": "*"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "c8e3b74951182dc5c58a0d1cd5be54b356271bd2",
        "tarball": "https://registry.npmjs.org/youtube-dl/-/youtube-dl-1.11.1.tgz"
    },
    "gitHead": "22abe259ffaf49849276ae008ba5786c68c4763c",
    "homepage": "https://github.com/fent/node-youtube-dl",
    "keywords": [
        "youtube",
        "video",
        "download"
    ],
    "license": "MIT",
    "main": "./lib/youtube-dl.js",
    "maintainers": [
        {
            "name": "fent"
        },
        {
            "name": "przemyslawpluta"
        }
    ],
    "name": "youtube-dl",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/fent/node-youtube-dl.git"
    },
    "scripts": {
        "postinstall": "node ./scripts/download.js",
        "test": "vows ./test/*.js --spec",
        "update": "node ./scripts/download.js"
    },
    "version": "1.11.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

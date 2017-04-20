# npmtest-gulp-electron

#### basic test coverage for  gulp-electron (v0.1.3)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-electron.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-electron) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-electron.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-electron)

#### A gulp plugin for Electron distribute applications.

[![NPM](https://nodei.co/npm/gulp-electron.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-electron)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-electron/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-electron/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-electron/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-electron/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-electron/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-electron/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-electron/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-electron/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-electron/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-electron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-electron/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-electron/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-electron/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-electron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-electron/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-electron/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-electron/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-electron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-electron/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-electron/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-electron/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-electron",
    "version": "0.1.3",
    "description": "A gulp plugin for Electron distribute applications.",
    "main": "index.js",
    "scripts": {
        "test": "gulp mocha && cd example && gulp"
    },
    "keywords": [
        "gulp",
        "gulplugin",
        "atom-shell",
        "electron"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/mainyaa/gulp-electron.git"
    },
    "author": "mainya@gmail.com",
    "license": "MIT",
    "devDependencies": {
        "gulp": "^3.9.1",
        "gulp-coffee": "^2.3.2",
        "gulp-coffeelint": "^0.6.0",
        "gulp-mocha": "^2.2.0",
        "should": "^8.3.0"
    },
    "dependencies": {
        "asar": "^0.10.0",
        "async": "^1.5.2",
        "bluebird": "^3.3.5",
        "chalk": "^1.1.3",
        "decompress-zip": "^0.3.0",
        "fs-extra": "^0.26.7",
        "grs": "^0.1.3",
        "gulp-coffeelint": "^0.6.0",
        "gulp-util": "^3.0.7",
        "mv": "^2.1.1",
        "plist": "^1.2.0",
        "progress": "^1.1.8",
        "rcedit": "^0.4.0",
        "rimraf": "^2.5.2",
        "should": "^8.3.1",
        "through2": "^2.0.1",
        "vinyl": "^1.1.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

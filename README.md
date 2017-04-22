# npmtest-electron-window-state

#### basic test coverage for  electron-window-state (v4.1.1)  [![npm package](https://img.shields.io/npm/v/npmtest-electron-window-state.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-electron-window-state) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-electron-window-state.svg)](https://travis-ci.org/npmtest/node-npmtest-electron-window-state)

#### Simple module that helps to save and restore size and position of Electron windows.

[![NPM](https://nodei.co/npm/electron-window-state.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-window-state)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-electron-window-state/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-window-state/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-electron-window-state/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-electron-window-state/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-electron-window-state/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-electron-window-state/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-electron-window-state/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-electron-window-state/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-electron-window-state/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-window-state/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-electron-window-state/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-electron-window-state/build/test-report.html](https://npmtest.github.io/node-npmtest-electron-window-state/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-electron-window-state/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-electron-window-state/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-electron-window-state/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-window-state/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-window-state/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-window-state/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-electron-window-state/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-electron-window-state/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "electron-window-state",
    "version": "4.1.1",
    "description": "Simple module that helps to save and restore size and position of Electron windows.",
    "license": "MIT",
    "repository": "mawie81/electron-window-state",
    "main": "index.js",
    "author": "Marcel Wiehle",
    "engines": {
        "node": ">=4.0.0"
    },
    "scripts": {
        "test": "xo && ava"
    },
    "keywords": [
        "electron"
    ],
    "files": [
        "index.js"
    ],
    "dependencies": {
        "deep-equal": "^1.0.1",
        "jsonfile": "^2.2.3",
        "mkdirp": "^0.5.1"
    },
    "devDependencies": {
        "ava": "^0.17.0",
        "mockery": "^1.4.0",
        "sinon": "^1.17.2",
        "xo": "^0.17.1"
    },
    "xo": {
        "space": true,
        "rules": {
            "brace-style": [
                2,
                "1tbs",
                {
                    "allowSingleLine": true
                }
            ]
        }
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

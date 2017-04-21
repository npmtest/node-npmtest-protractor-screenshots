# npmtest-protractor-screenshots

#### basic test coverage for  protractor-screenshots (v0.0.8)  [![npm package](https://img.shields.io/npm/v/npmtest-protractor-screenshots.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-protractor-screenshots) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-protractor-screenshots.svg)](https://travis-ci.org/npmtest/node-npmtest-protractor-screenshots)

#### Integrates protractor and webdriver to let tests take and compare screenshots at different sizes.

[![NPM](https://nodei.co/npm/protractor-screenshots.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/protractor-screenshots)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-protractor-screenshots/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-protractor-screenshots/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-protractor-screenshots/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-protractor-screenshots/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-protractor-screenshots/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-protractor-screenshots/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-protractor-screenshots/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-protractor-screenshots/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-protractor-screenshots/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-protractor-screenshots/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-protractor-screenshots/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-protractor-screenshots/build/test-report.html](https://npmtest.github.io/node-npmtest-protractor-screenshots/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-protractor-screenshots/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-protractor-screenshots/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-protractor-screenshots/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-protractor-screenshots/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-protractor-screenshots/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-protractor-screenshots/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-protractor-screenshots/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-protractor-screenshots/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "protractor-screenshots",
    "version": "0.0.8",
    "description": "Integrates protractor and webdriver to let tests take and compare screenshots at different sizes.",
    "main": "lib/screenshots.js",
    "scripts": {
        "test": "(cd test && bash test.sh)"
    },
    "author": "Michael Bertolacci",
    "repository": {
        "type": "git",
        "url": "git://github.com/burnsred/protractor-screenshots"
    },
    "license": "ISC",
    "dependencies": {
        "rimraf": "^2.2.6",
        "mkdirp": "^0.3.5",
        "resemble": "^1.0.3",
        "slug": "^0.4.2",
        "q": "^1.0.1",
        "lodash": "^2.4.1"
    },
    "devDependencies": {
        "express": "^3.5.1",
        "protractor": "^0.21.0",
        "phantomjs": "^1.9.7-3"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-katex

#### basic test coverage for  katex (v0.7.1)  [![npm package](https://img.shields.io/npm/v/npmtest-katex.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-katex) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-katex.svg)](https://travis-ci.org/npmtest/node-npmtest-katex)

#### Fast math typesetting for the web.

[![NPM](https://nodei.co/npm/katex.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/katex)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-katex/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-katex/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-katex/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-katex/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-katex/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-katex/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-katex/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-katex/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-katex/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-katex/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-katex/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-katex/build/test-report.html](https://npmtest.github.io/node-npmtest-katex/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-katex/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-katex/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-katex/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-katex/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-katex/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-katex/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-katex/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-katex/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "katex",
    "version": "0.7.1",
    "description": "Fast math typesetting for the web.",
    "main": "katex.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/Khan/KaTeX.git"
    },
    "files": [
        "katex.js",
        "cli.js",
        "src/",
        "dist/"
    ],
    "license": "MIT",
    "devDependencies": {
        "browserify": "^10.2.4",
        "clean-css": "~2.2.15",
        "eslint": "^1.10.3",
        "express": "~3.3.3",
        "glob": "^5.0.15",
        "jasmine": "^2.3.2",
        "jasmine-core": "^2.3.4",
        "js-yaml": "^3.3.1",
        "jspngopt": "^0.1.0",
        "less": "~2.7.1",
        "nomnom": "^1.8.1",
        "pako": "0.2.7",
        "selenium-webdriver": "^2.46.1",
        "sri-toolbox": "^0.2.0",
        "uglify-js": "~2.4.15"
    },
    "bin": "cli.js",
    "scripts": {
        "test": "make lint test",
        "prepublish": "make NIS= dist"
    },
    "dependencies": {
        "match-at": "^0.1.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

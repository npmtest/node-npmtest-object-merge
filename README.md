# npmtest-object-merge

#### basic test coverage for  [object-merge (v2.5.1)](https://github.com/matthewkastor/object-merge/)  [![npm package](https://img.shields.io/npm/v/npmtest-object-merge.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-object-merge) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-object-merge.svg)](https://travis-ci.org/npmtest/node-npmtest-object-merge)

#### Merges JavaScript objects recursively without altering the objects merged.

[![NPM](https://nodei.co/npm/object-merge.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/object-merge)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-object-merge/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-object-merge/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-object-merge/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-object-merge/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-object-merge/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-object-merge/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-object-merge/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-object-merge/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-object-merge/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-object-merge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-object-merge/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-object-merge/build/test-report.html](https://npmtest.github.io/node-npmtest-object-merge/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-object-merge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-object-merge/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-object-merge/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-object-merge/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-object-merge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-object-merge/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-object-merge/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-object-merge/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matthew Kastor",
        "url": "https://plus.google.com/100898583798552211130"
    },
    "bugs": {
        "url": "https://github.com/matthewkastor/object-merge/issues"
    },
    "dependencies": {
        "clone-function": ">=1.0.1",
        "object-foreach": ">=0.1.2"
    },
    "description": "Merges JavaScript objects recursively without altering the objects merged.",
    "devDependencies": {
        "atropa-jsformatter": ">=0.1.2",
        "atropa-jslint": ">=0.1.2",
        "browserify": ">=2.29.1",
        "jasmine-node": ">=1.11.0",
        "jsdoc-toolkit": "git+https://github.com/matthewkastor/node-jsdoc-toolkit.git#fix-tests"
    },
    "directories": {
        "lib": "src",
        "doc": "docs"
    },
    "dist": {
        "shasum": "077e8915ce38ea7294788448c5dd339e34df4227",
        "tarball": "https://registry.npmjs.org/object-merge/-/object-merge-2.5.1.tgz"
    },
    "homepage": "https://github.com/matthewkastor/object-merge/",
    "keywords": [
        "object-merge",
        "atropa"
    ],
    "licenses": [
        {
            "type": "gpl-3.0",
            "url": "http://www.gnu.org/licenses/gpl-3.0-standalone.html"
        }
    ],
    "main": "./src/object-merge.js",
    "maintainers": [
        {
            "name": "kastor"
        }
    ],
    "name": "object-merge",
    "optionalDependencies": {},
    "readmeFilename": "Readme.md",
    "repository": {
        "type": "git",
        "url": "git://github.com/matthewkastor/object-merge.git"
    },
    "scripts": {
        "buildBrowserModule": "node dev/browserify.js",
        "buildDocs": "jsdoc-toolkit -v -d=./docs/jsdoc/ -r -s src/",
        "lint": "atropa-jslint ./src/object-merge.js",
        "srcFormat": "atropa-jsformatter ./src/object-merge.js ./src/object-merge.js",
        "test": "jasmine-node specs/"
    },
    "version": "2.5.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

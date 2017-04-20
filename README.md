# npmtest-sortablejs

#### basic test coverage for  sortablejs (v1.5.1)  [![npm package](https://img.shields.io/npm/v/npmtest-sortablejs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sortablejs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sortablejs.svg)](https://travis-ci.org/npmtest/node-npmtest-sortablejs)

#### Minimalist JavaScript library for reorderable drag-and-drop lists on modern browsers and touch devices. No jQuery. Supports AngularJS and any CSS library, e.g. Bootstrap.

[![NPM](https://nodei.co/npm/sortablejs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sortablejs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sortablejs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sortablejs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sortablejs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sortablejs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sortablejs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sortablejs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sortablejs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sortablejs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sortablejs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sortablejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sortablejs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sortablejs/build/test-report.html](https://npmtest.github.io/node-npmtest-sortablejs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sortablejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sortablejs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sortablejs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sortablejs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sortablejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sortablejs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sortablejs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sortablejs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sortablejs",
    "exportName": "Sortable",
    "version": "1.5.1",
    "devDependencies": {
        "grunt": "*",
        "grunt-version": "*",
        "grunt-contrib-jshint": "*",
        "grunt-contrib-uglify": "*"
    },
    "description": "Minimalist JavaScript library for reorderable drag-and-drop lists on modern browsers and touch devices. No jQuery. Supports AngularJS and any CSS library, e.g. Bootstrap.",
    "main": "Sortable.js",
    "scripts": {
        "test": "./node_modules/grunt/bin/grunt",
        "prepublish": "./node_modules/grunt/bin/grunt"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/rubaxa/Sortable.git"
    },
    "files": [
        "Sortable.js",
        "Sortable.min.js"
    ],
    "keywords": [
        "sortable",
        "reorder",
        "drag",
        "meteor",
        "angular",
        "ng-sortable",
        "react",
        "mixin"
    ],
    "author": "Konstantin Lebedev <ibnRubaXa@gmail.com>",
    "license": "MIT",
    "spm": {
        "main": "Sortable.js",
        "ignore": [
            "meteor",
            "st"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

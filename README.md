# npmdoc-gulp-fixmyjs

#### api documentation for  gulp-fixmyjs (v1.0.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-fixmyjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-fixmyjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-fixmyjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-fixmyjs)

#### fixmyjs plugin for gulp

[![NPM](https://nodei.co/npm/gulp-fixmyjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-fixmyjs)

- [https://npmdoc.github.io/node-npmdoc-gulp-fixmyjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-fixmyjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-fixmyjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-fixmyjs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-fixmyjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-fixmyjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-fixmyjs",
    "version": "1.0.2",
    "description": "fixmyjs plugin for gulp",
    "keywords": [
        "fix",
        "gulpplugin",
        "fixmyjs",
        "jshint",
        "linting",
        "js",
        "lint"
    ],
    "author": {
        "name": "Kirill Cherkashin",
        "url": "https://github.com/kirjs"
    },
    "repository": "kirjs/gulp-fixmyjs",
    "files": [
        "index.js"
    ],
    "scripts": {
        "test": "istanbul test _mocha --report html -- test/*.js --reporter spec",
        "test-debug": "node --debug-brk istanbul test _mocha --report html -- test/*.js --reporter spec",
        "coveralls": "istanbul cover _mocha --report lcovonly -- -R spec && istanbul-coveralls"
    },
    "dependencies": {
        "fixmyjs": "*",
        "gulp-util": "^3.0.1",
        "jshint": "~2.6.3",
        "rcloader": "~0.1.4",
        "through2": "*"
    },
    "devDependencies": {
        "coveralls": "*",
        "event-stream": "*",
        "istanbul": "*",
        "istanbul-coveralls": "^1.0.1",
        "mocha": "*",
        "mocha-lcov-reporter": "*",
        "should": "^4.0.4"
    },
    "engines": {
        "node": ">=0.9.0",
        "npm": ">=1.2.10"
    },
    "license": "MIT",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmdoc-generator-polymer

#### basic api documentation for  [generator-polymer (v1.3.0)](https://github.com/yeoman/generator-polymer#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-generator-polymer.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-generator-polymer) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-generator-polymer.svg)](https://travis-ci.org/npmdoc/node-npmdoc-generator-polymer)

#### Scaffold out a Polymer project

[![NPM](https://nodei.co/npm/generator-polymer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-polymer)

- [https://npmdoc.github.io/node-npmdoc-generator-polymer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-polymer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-polymer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-polymer/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-generator-polymer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-generator-polymer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Chrome Developer Relations"
    },
    "bugs": {
        "url": "https://github.com/yeoman/generator-polymer/issues"
    },
    "dependencies": {
        "chalk": "^1.0.0",
        "html-wiring": "^1.2.0",
        "js-beautify": "^1.5.10",
        "lodash": "^4.0.0",
        "mkdirp": "^0.5.1",
        "ncp": "^2.0.0",
        "rimraf": "^2.2.8",
        "validate-element-name": "^1.0.0",
        "yeoman-generator": "^0.22.3",
        "yosay": "^1.0.0"
    },
    "description": "Scaffold out a Polymer project",
    "devDependencies": {
        "fs-extra": "*",
        "jshint": "*",
        "mocha": "*",
        "yeoman-assert": "^2.1.1",
        "yeoman-test": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "11827c6b2f9afc0649e05e17b57108b94a88d5d5",
        "tarball": "https://registry.npmjs.org/generator-polymer/-/generator-polymer-1.3.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "app",
        "el",
        "element",
        "gh",
        "seed",
        "script-base.js",
        "util.js"
    ],
    "gitHead": "56200aeac25bf59ef1888005bdac3274a2a963a5",
    "homepage": "https://github.com/yeoman/generator-polymer#readme",
    "keywords": [
        "yeoman-generator",
        "scaffold",
        "framework",
        "mvc",
        "polymer"
    ],
    "licenses": "BSD",
    "main": "app/index.js",
    "maintainers": [
        {
            "name": "sindresorhus"
        },
        {
            "name": "addyosmani"
        },
        {
            "name": "sboudrias"
        },
        {
            "name": "robdodson"
        },
        {
            "name": "eddiemonge"
        },
        {
            "name": "passy"
        },
        {
            "name": "arthurvr"
        }
    ],
    "name": "generator-polymer",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yeoman/generator-polymer.git"
    },
    "scripts": {
        "prepublish": "git submodule update --init --recursive",
        "test": "jshint {app,el,gh,seed,test}/*.js script-base.js util.js && mocha --reporter spec"
    },
    "version": "1.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmdoc-colorguard

#### basic api documentation for  [colorguard (v1.2.0)](https://github.com/SlexAxton/css-colorguard)  [![npm package](https://img.shields.io/npm/v/npmdoc-colorguard.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-colorguard) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-colorguard.svg)](https://travis-ci.org/npmdoc/node-npmdoc-colorguard)

#### Keep a watchful eye on your css colors

[![NPM](https://nodei.co/npm/colorguard.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/colorguard)

- [https://npmdoc.github.io/node-npmdoc-colorguard/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-colorguard/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-colorguard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-colorguard/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-colorguard/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-colorguard/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alex Sexton"
    },
    "bin": {
        "colorguard": "./bin/colorguard"
    },
    "bugs": {
        "url": "https://github.com/SlexAxton/css-colorguard/issues"
    },
    "dependencies": {
        "chalk": "^1.1.1",
        "color-diff": "^0.1.3",
        "log-symbols": "^1.0.2",
        "object-assign": "^4.0.1",
        "pipetteur": "^2.0.0",
        "plur": "^2.0.0",
        "postcss": "^5.0.4",
        "postcss-reporter": "^1.2.1",
        "text-table": "^0.2.0",
        "yargs": "^1.2.6"
    },
    "description": "Keep a watchful eye on your css colors",
    "devDependencies": {
        "jshint": "^2.9.1",
        "tap-spec": "^4.1.0",
        "tape": "^4.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f3facaf5caaeba4ef54653d9fb25bb73177c0d84",
        "tarball": "https://registry.npmjs.org/colorguard/-/colorguard-1.2.0.tgz"
    },
    "files": [
        "bin",
        "lib",
        "index.js"
    ],
    "gitHead": "12c5920fdfab140fd13f58df58422ddb9c35e42c",
    "homepage": "https://github.com/SlexAxton/css-colorguard",
    "keywords": [
        "css",
        "colors",
        "lint",
        "csslint",
        "postcss",
        "postcss-plugin"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "beneb"
        },
        {
            "name": "slexaxton"
        }
    ],
    "name": "colorguard",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/SlexAxton/css-colorguard.git"
    },
    "scripts": {
        "lint": "jshint .",
        "test": "npm run lint && tape test/*.js | tap-spec"
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

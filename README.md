# npmdoc-vantage

#### api documentation for  [vantage (v1.7.0)](https://github.com/dthree/vantage#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-vantage.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-vantage) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-vantage.svg)](https://travis-ci.org/npmdoc/node-npmdoc-vantage)

#### CLI + SSH + REPL for Node

[![NPM](https://nodei.co/npm/vantage.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vantage)

- [https://npmdoc.github.io/node-npmdoc-vantage/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vantage/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vantage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vantage/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-vantage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-vantage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "dthree"
    },
    "bin": {
        "vantage": "./bin/vantage.js",
        "vtg": "./bin/vantage.js",
        "nsh": "./bin/vantage.js"
    },
    "bugs": {
        "url": "https://github.com/dthree/vantage/issues"
    },
    "dependencies": {
        "chalk": "^1.1.0",
        "commander": "2.8.1",
        "insubnet": "0.0.8",
        "lodash": "3.10.0",
        "native-promise-only": "0.8.0-a",
        "socket.io": "1.4.5",
        "socket.io-client": "1.4.5",
        "strip-ansi": "^3.0.0",
        "vantage-auth-basic": "latest",
        "vorpal": "1.0.5",
        "vorpal-repl": "1.1.8"
    },
    "description": "CLI + SSH + REPL for Node",
    "devDependencies": {
        "eslint": "^1.2.1",
        "express": "^4.12.4",
        "gulp": "^3.9.0",
        "gulp-eslint": "^1.0.0",
        "hapi": "^8.8.1",
        "koa": "^0.21.0",
        "mocha": "^2.2.5",
        "moment": "^2.10.3",
        "request": "^2.58.0",
        "should": "^6.0.3",
        "vorpal-use": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "d6f7b8a42ff263dabd5380bb3727b752666139a0",
        "tarball": "https://registry.npmjs.org/vantage/-/vantage-1.7.0.tgz"
    },
    "engines": {
        "iojs": ">= 1.0.0",
        "node": ">= 0.10.0"
    },
    "eslintConfig": {
        "env": {
            "node": true,
            "browser": false
        },
        "rules": {
            "no-underscore-dangle": 0,
            "no-process-exit": 0,
            "no-undef": 0,
            "no-proto": 0,
            "no-use-before-define": 0,
            "new-cap": 0
        }
    },
    "files": [
        "lib",
        "bin",
        "examples"
    ],
    "gitHead": "1900f2f8a84d2a8dd0c172486e0c95d9b81ae1a8",
    "homepage": "https://github.com/dthree/vantage#readme",
    "keywords": [
        "api",
        "cli",
        "repl",
        "shell",
        "command",
        "commander",
        "distributed",
        "automated",
        "prompt",
        "inquirer"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "dthree"
        }
    ],
    "name": "vantage",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dthree/vantage.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "1.7.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

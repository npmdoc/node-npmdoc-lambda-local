# npmdoc-lambda-local

#### api documentation for  lambda-local (v1.4.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-lambda-local.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-lambda-local) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-lambda-local.svg)](https://travis-ci.org/npmdoc/node-npmdoc-lambda-local)

#### Commandline tool to run Lambda functions on your local machine.

[![NPM](https://nodei.co/npm/lambda-local.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lambda-local)

- [https://npmdoc.github.io/node-npmdoc-lambda-local/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lambda-local/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lambda-local/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lambda-local/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-lambda-local/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-lambda-local/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "lambda-local",
    "version": "1.4.2",
    "description": "Commandline tool to run Lambda functions on your local machine.",
    "keywords": [
        "lambda",
        "amazon",
        "aws",
        "AWS",
        "local",
        "run"
    ],
    "author": "ashiina",
    "engines": {
        "node": ">=0.10"
    },
    "dependencies": {
        "aws-sdk": "^2.1.6",
        "chai": "^3.5.0",
        "commander": "^2.6.0",
        "fs": "^0.0.2",
        "mute": "^2.0.6",
        "winston": "^2.2.0"
    },
    "devDependencies": {
        "mocha": "^2.4.5",
        "sinon": "^1.17.6"
    },
    "scripts": {
        "test": "mocha"
    },
    "preferGlobal": true,
    "bin": {
        "lambda-local": "./bin/lambda-local"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/ashiina/lambda-local.git"
    },
    "bugs": {
        "url": "https://github.com/ashiina/lambda-local/issues"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

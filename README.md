# npmdoc-connect

#### api documentation for  [connect (v3.6.0)](https://github.com/senchalabs/connect#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-connect.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-connect) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-connect.svg)](https://travis-ci.org/npmdoc/node-npmdoc-connect)

#### High performance middleware framework

[![NPM](https://nodei.co/npm/connect.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/connect)

- [https://npmdoc.github.io/node-npmdoc-connect/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-connect/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-connect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-connect/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-connect/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-connect/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk",
        "url": "http://tjholowaychuk.com"
    },
    "bugs": {
        "url": "https://github.com/senchalabs/connect/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Jonathan Ong"
        },
        {
            "name": "Tim Caswell"
        }
    ],
    "dependencies": {
        "debug": "2.6.1",
        "finalhandler": "1.0.0",
        "parseurl": "~1.3.1",
        "utils-merge": "1.0.0"
    },
    "description": "High performance middleware framework",
    "devDependencies": {
        "istanbul": "0.4.5",
        "mocha": "3.2.0",
        "supertest": "2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f09a4f7dcd17324b663b725c815bdb1c4158a46e",
        "tarball": "https://registry.npmjs.org/connect/-/connect-3.6.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "README.md",
        "index.js"
    ],
    "gitHead": "2fa751469f1298913d1f66ccf00b00b37be9f77b",
    "homepage": "https://github.com/senchalabs/connect#readme",
    "keywords": [
        "framework",
        "web",
        "middleware",
        "connect",
        "rack"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "tjholowaychuk"
        }
    ],
    "name": "connect",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/senchalabs/connect.git"
    },
    "scripts": {
        "test": "mocha --require test/support/env --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --require test/support/env --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --require test/support/env --reporter spec --check-leaks test/"
    },
    "version": "3.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# api documentation for  [connect (v3.6.0)](https://github.com/senchalabs/connect#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-connect.svg)](https://travis-ci.org/npmdoc/node-npmdoc-connect)
#### High performance middleware framework

[![NPM](https://nodei.co/npm/connect.png?downloads=true)](https://www.npmjs.com/package/connect)

[![apidoc](https://npmdoc.github.io/node-npmdoc-connect/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-connect_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-connect/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-connect/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk",
        "email": "tj@vision-media.ca",
        "url": "http://tjholowaychuk.com"
    },
    "bugs": {
        "url": "https://github.com/senchalabs/connect/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "Jonathan Ong",
            "email": "me@jongleberry.com"
        },
        {
            "name": "Tim Caswell",
            "email": "tim@creationix.com"
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
            "name": "dougwilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "jongleberry",
            "email": "jonathanrichardong@gmail.com"
        },
        {
            "name": "tjholowaychuk",
            "email": "tj@vision-media.ca"
        }
    ],
    "name": "connect",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module connect](#apidoc.module.connect)



# <a name="apidoc.module.connect"></a>[module connect](#apidoc.module.connect)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# api documentation for  [etag (v1.8.0)](https://github.com/jshttp/etag#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-etag.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-etag) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-etag.svg)](https://travis-ci.org/npmdoc/node-npmdoc-etag)
#### Create simple HTTP ETags

[![NPM](https://nodei.co/npm/etag.png?downloads=true)](https://www.npmjs.com/package/etag)

[![apidoc](https://npmdoc.github.io/node-npmdoc-etag/build/screenCapture.buildNpmdoc.browser.%2Fhome%2Ftravis%2Fbuild%2Fnpmdoc%2Fnode-npmdoc-etag%2Ftmp%2Fbuild%2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-etag/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-etag/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-etag/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/jshttp/etag/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "David Björklund",
            "email": "david.bjorklund@gmail.com"
        }
    ],
    "dependencies": {},
    "description": "Create simple HTTP ETags",
    "devDependencies": {
        "beautify-benchmark": "0.2.4",
        "benchmark": "2.1.3",
        "eslint": "3.15.0",
        "eslint-config-standard": "6.2.1",
        "eslint-plugin-markdown": "1.0.0-beta.3",
        "eslint-plugin-promise": "3.4.2",
        "eslint-plugin-standard": "2.0.1",
        "istanbul": "0.4.5",
        "mocha": "1.21.5",
        "seedrandom": "2.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "6f631aef336d6c46362b51764044ce216be3c051",
        "tarball": "https://registry.npmjs.org/etag/-/etag-1.8.0.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "README.md",
        "index.js"
    ],
    "gitHead": "16979f788efa8c793c8d07543b4d6aef3d2bfff8",
    "homepage": "https://github.com/jshttp/etag#readme",
    "keywords": [
        "etag",
        "http",
        "res"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson",
            "email": "doug@somethingdoug.com"
        }
    ],
    "name": "etag",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/etag.git"
    },
    "scripts": {
        "bench": "node benchmark/index.js",
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "1.8.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module etag](#apidoc.module.etag)



# <a name="apidoc.module.etag"></a>[module etag](#apidoc.module.etag)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

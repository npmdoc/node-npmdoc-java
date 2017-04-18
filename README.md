# npmdoc-java

#### api documentation for  [java (v0.8.0)](https://github.com/joeferner/node-java#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-java.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-java) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-java.svg)](https://travis-ci.org/npmdoc/node-npmdoc-java)

#### Bridge API to connect with existing Java APIs.

[![NPM](https://nodei.co/npm/java.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/java)

- [https://npmdoc.github.io/node-npmdoc-java/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-java/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-java/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-java/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-java/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-java/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Joe Ferner"
    },
    "bugs": {
        "url": "https://github.com/joeferner/node-java/issues"
    },
    "dependencies": {
        "async": "2.0.1",
        "find-java-home": "0.1.3",
        "glob": "7.1.1",
        "lodash": "4.16.4",
        "nan": "2.4.0"
    },
    "description": "Bridge API to connect with existing Java APIs.",
    "devDependencies": {
        "chalk": "1.1.3",
        "nodeunit": "0.10.2",
        "when": "3.7.7"
    },
    "directories": {},
    "dist": {
        "shasum": "23a6f7ac6a6f85d551c89f4fe49c47c481df4cab",
        "tarball": "https://registry.npmjs.org/java/-/java-0.8.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "738944eb41560d9a004c14db1749247cdd96b295",
    "gypfile": true,
    "homepage": "https://github.com/joeferner/node-java#readme",
    "keywords": [
        "java",
        "jvm",
        "bridge"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "joeferner"
        }
    ],
    "name": "java",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/joeferner/node-java.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "postinstall": "node postInstall.js",
        "test": "node testRunner.js"
    },
    "version": "0.8.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

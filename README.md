# api documentation for  [stylelint-config-standard (v16.0.0)](https://github.com/stylelint/stylelint-config-standard#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-stylelint-config-standard.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-stylelint-config-standard) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-stylelint-config-standard.svg)](https://travis-ci.org/npmdoc/node-npmdoc-stylelint-config-standard)
#### Standard shareable config for stylelint

[![NPM](https://nodei.co/npm/stylelint-config-standard.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/stylelint-config-standard)

- [https://npmdoc.github.io/node-npmdoc-stylelint-config-standard/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-stylelint-config-standard/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stylelint-config-standard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stylelint-config-standard/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-stylelint-config-standard/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-stylelint-config-standard/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "stylelint"
    },
    "bugs": {
        "url": "https://github.com/stylelint/stylelint-config-standard/issues"
    },
    "dependencies": {},
    "description": "Standard shareable config for stylelint",
    "devDependencies": {
        "eslint": "^3.1.1",
        "eslint-config-stylelint": "^6.0.0",
        "jest": "^18.1.0",
        "npm-run-all": "^4.0.0",
        "npmpub": "^3.0.1",
        "remark-cli": "^2.0.0",
        "remark-preset-lint-consistent": "^1.0.0",
        "remark-preset-lint-recommended": "^1.0.0",
        "stylelint": "^7.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "bb7387bff1d7dd7186a52b3ebf885b2405d691bf",
        "tarball": "https://registry.npmjs.org/stylelint-config-standard/-/stylelint-config-standard-16.0.0.tgz"
    },
    "eslintConfig": {
        "extends": [
            "stylelint"
        ]
    },
    "files": [
        "index.js"
    ],
    "gitHead": "5d1c9beb2f49c8342a4aadbe627e9940b20bf9ce",
    "homepage": "https://github.com/stylelint/stylelint-config-standard#readme",
    "jest": {
        "testEnvironment": "node",
        "verbose": true
    },
    "keywords": [
        "stylelint",
        "stylelint-config",
        "standard"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jeddy3"
        }
    ],
    "name": "stylelint-config-standard",
    "optionalDependencies": {},
    "peerDependencies": {
        "stylelint": "^7.8.0"
    },
    "remarkConfig": {
        "presets": [
            "lint-recommended",
            "lint-consistent"
        ]
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/stylelint/stylelint-config-standard.git"
    },
    "scripts": {
        "lint": "npm-run-all --parallel lint:*",
        "lint:js": "eslint . --ignore-path .gitignore",
        "lint:md": "remark . --quiet --frail",
        "pretest": "npm run lint",
        "release": "npmpub",
        "test": "jest",
        "watch": "jest --watch"
    },
    "version": "16.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

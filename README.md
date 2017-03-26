# api documentation for  [npm-check (v5.4.0)](https://github.com/dylang/npm-check)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-npm-check.svg)](https://travis-ci.org/npmdoc/node-npmdoc-npm-check)
#### Check for outdated, incorrect, and unused dependencies.

[![NPM](https://nodei.co/npm/npm-check.png?downloads=true)](https://www.npmjs.com/package/npm-check)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-check/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-npm-check_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-check/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-npm-check/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Dylan Greene",
        "email": "dylang@gmail.com"
    },
    "bin": {
        "npm-check": "bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/dylang/npm-check/issues"
    },
    "dependencies": {
        "babel-runtime": "^6.6.1",
        "callsite-record": "^3.0.0",
        "chalk": "^1.1.3",
        "co": "^4.6.0",
        "depcheck": "^0.6.3",
        "execa": "^0.2.2",
        "giturl": "^1.0.0",
        "global-modules": "^0.2.0",
        "globby": "^4.0.0",
        "inquirer": "^0.12.0",
        "is-ci": "^1.0.8",
        "lodash": "^4.7.0",
        "meow": "^3.7.0",
        "merge-options": "0.0.64",
        "minimatch": "^3.0.2",
        "node-emoji": "^1.0.3",
        "ora": "^0.2.1",
        "package-json": "^2.0.1",
        "path-exists": "^2.1.0",
        "pkg-dir": "^1.0.0",
        "semver": "^5.0.1",
        "semver-diff": "^2.0.0",
        "text-table": "^0.2.0",
        "throat": "^2.0.2",
        "update-notifier": "^0.6.3"
    },
    "description": "Check for outdated, incorrect, and unused dependencies.",
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-plugin-transform-runtime": "^6.6.0",
        "babel-preset-es2015": "^6.6.0",
        "grunt": "^0.4.0",
        "grunt-cli": "^1.2.0",
        "grunt-release": "^0.13.0",
        "grunt-templates-dylang": "^1.0.9",
        "load-grunt-tasks": "^3.3.0",
        "xo": "^0.13.0"
    },
    "directories": {},
    "dist": {
        "shasum": "21f537e474616458beaccd6ecfc9f73f246ee7bd",
        "tarball": "https://registry.npmjs.org/npm-check/-/npm-check-5.4.0.tgz"
    },
    "engines": {
        "node": ">=0.11.0"
    },
    "files": [
        "bin",
        "lib",
        "lib-es5"
    ],
    "gitHead": "ee416b8a20742e81cd848aaace1ce328e070f8f2",
    "homepage": "https://github.com/dylang/npm-check",
    "keywords": [
        "npm",
        "outdated",
        "dependencies",
        "unused",
        "changelog",
        "check",
        "updates",
        "api",
        "interactive",
        "cli",
        "safe",
        "updating",
        "updater",
        "installer",
        "devDependencies"
    ],
    "license": "MIT",
    "main": "lib",
    "maintainers": [
        {
            "name": "dylang",
            "email": "dylang@gmail.com"
        },
        {
            "name": "linusu",
            "email": "linus@folkdatorn.se"
        }
    ],
    "name": "npm-check",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dylang/npm-check.git"
    },
    "scripts": {
        "lint": "xo ./lib/*.js",
        "prepublish": "npm run transpile",
        "readme": "grunt readme",
        "repos": "grunt repos # required for grunt readme to run",
        "test": "xo ./lib/*.js && ./bin/cli.js || echo Exit Status: $?.",
        "transpile": "babel lib --out-dir lib-es5",
        "watch": "babel lib --out-dir lib-es5 --watch"
    },
    "version": "5.4.0",
    "xo": {
        "space": 4,
        "rules": {
            "no-warning-comments": [
                0
            ],
            "global-require": [
                0
            ]
        }
    }
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module npm-check](#apidoc.module.npm-check)



# <a name="apidoc.module.npm-check"></a>[module npm-check](#apidoc.module.npm-check)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

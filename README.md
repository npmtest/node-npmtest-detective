# npmtest-detective

#### basic test coverage for  [detective (v4.5.0)](https://github.com/substack/node-detective#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-detective.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-detective) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-detective.svg)](https://travis-ci.org/npmtest/node-npmtest-detective)

#### find all require() calls by walking the AST

[![NPM](https://nodei.co/npm/detective.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/detective)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-detective/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-detective/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-detective/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-detective/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-detective/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-detective/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-detective/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-detective/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-detective/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-detective/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-detective/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-detective/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-detective/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-detective/build/test-report.html](https://npmtest.github.io/node-npmtest-detective/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-detective/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-detective/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-detective/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-detective/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-detective/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-detective/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-detective/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-detective/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bugs": {
        "url": "https://github.com/substack/node-detective/issues"
    },
    "dependencies": {
        "acorn": "^4.0.3",
        "defined": "^1.0.0"
    },
    "description": "find all require() calls by walking the AST",
    "devDependencies": {
        "tap": "^5.7.1"
    },
    "directories": {},
    "dist": {
        "shasum": "6e5a8c6b26e6c7a254b1c6b6d7490d98ec91edd1",
        "tarball": "https://registry.npmjs.org/detective/-/detective-4.5.0.tgz"
    },
    "gitHead": "4aa3713807feb699f18d83152e5475d0ec5345b6",
    "homepage": "https://github.com/substack/node-detective#readme",
    "keywords": [
        "require",
        "source",
        "analyze",
        "ast"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "substack"
        },
        {
            "name": "zertosh"
        }
    ],
    "name": "detective",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/node-detective.git"
    },
    "scripts": {
        "test": "tap test/*.js"
    },
    "version": "4.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

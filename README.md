# test coverage for  [nlp_compromise (v6.5.3)](https://github.com/nlp-compromise/nlp_compromise#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-nlp_compromise.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nlp_compromise) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nlp_compromise.svg)](https://travis-ci.org/npmtest/node-npmtest-nlp_compromise)
#### natural language processing in the browser

[![NPM](https://nodei.co/npm/nlp_compromise.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nlp_compromise)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nlp_compromise/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nlp_compromise/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nlp_compromise/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nlp_compromise/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nlp_compromise/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nlp_compromise/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nlp_compromise/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nlp_compromise/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nlp_compromise/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nlp_compromise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nlp_compromise/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nlp_compromise/build/test-report.html](https://npmtest.github.io/node-npmtest-nlp_compromise/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nlp_compromise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nlp_compromise/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nlp_compromise/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nlp_compromise/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nlp_compromise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nlp_compromise/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nlp_compromise/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nlp_compromise/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Spencer Kelly",
        "url": "http://spencermounta.in"
    },
    "bugs": {
        "url": "https://github.com/nlp-compromise/nlp_compromise/issues"
    },
    "dependencies": {},
    "description": "natural language processing in the browser",
    "devDependencies": {
        "babel-preset-es2015": "6.9.0",
        "babelify": "7.3.0",
        "browserify": "13.0.1",
        "derequire": "^2.0.3",
        "grunt-cli": "1.2.0",
        "grunt-contrib-watch": "1.0.0",
        "grunt-eslint": "19.0.0",
        "grunt-filesize": "0.0.7",
        "grunt-run": "0.6.0",
        "http-server": "0.9.0",
        "nlp-corpus": "latest",
        "tap-spec": "4.1.1",
        "tape": "4.6.0",
        "uglify-js": "2.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7720b67daab7b486509057ef1d5eff9a3db091bb",
        "tarball": "https://registry.npmjs.org/nlp_compromise/-/nlp_compromise-6.5.3.tgz"
    },
    "files": [
        "builds/",
        "src/",
        "nlp.d.ts"
    ],
    "gitHead": "994c61750b725eb8508b417472a422b17293ef10",
    "homepage": "https://github.com/nlp-compromise/nlp_compromise#readme",
    "license": "MIT",
    "main": "./builds/nlp_compromise.js",
    "maintainers": [
        {
            "name": "spencermountain"
        }
    ],
    "name": "nlp_compromise",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/nlp-compromise/nlp_compromise.git"
    },
    "scripts": {
        "build": "grunt build",
        "build_windows": "grunt build_windows",
        "coverage": "grunt coverage",
        "demo": "grunt demo",
        "demo_windows": "grunt demo_windows",
        "test": "./node_modules/tape/bin/tape ./test/unit_test/**/*_test.js | tap-spec",
        "watch": "grunt watch"
    },
    "typings": "./nlp.d.ts",
    "version": "6.5.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

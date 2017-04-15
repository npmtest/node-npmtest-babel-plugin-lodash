# test coverage for  [babel-plugin-lodash (v3.2.11)](https://github.com/lodash/babel-plugin-lodash#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-babel-plugin-lodash.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-babel-plugin-lodash) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-babel-plugin-lodash.svg)](https://travis-ci.org/npmtest/node-npmtest-babel-plugin-lodash)
#### Modular Lodash builds without the hassle.

[![NPM](https://nodei.co/npm/babel-plugin-lodash.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babel-plugin-lodash)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-babel-plugin-lodash/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-plugin-lodash/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-babel-plugin-lodash/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-babel-plugin-lodash/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-babel-plugin-lodash/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-babel-plugin-lodash/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-babel-plugin-lodash/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-plugin-lodash/build/screenCapture.buildCi.browser.coverage.example.html.png)](https://npmtest.github.io/node-npmtest-babel-plugin-lodash/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-babel-plugin-lodash/build/screenCapture.buildCi.browser.test-report.html.png)](https://npmtest.github.io/node-npmtest-babel-plugin-lodash/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-plugin-lodash/build/screenCapture.buildCi.browser.apidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-plugin-lodash/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-babel-plugin-lodash/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-babel-plugin-lodash/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Graeme Yeates",
        "url": "https://github.com/megawac"
    },
    "bugs": {
        "url": "https://github.com/lodash/babel-plugin-lodash/issues"
    },
    "contributors": [
        {
            "name": "Graeme Yeates",
            "url": "https://github.com/megawac"
        },
        {
            "name": "John-David Dalton",
            "url": "http://allyoucanleet.com/"
        }
    ],
    "dependencies": {
        "glob": "^7.1.1",
        "lodash": "^4.17.2"
    },
    "description": "Modular Lodash builds without the hassle.",
    "devDependencies": {
        "async": "^2.1.4",
        "babel-cli": "^6.18.0",
        "babel-core": "^6.20.0",
        "babel-plugin-add-module-exports": "~0.2.1",
        "babel-plugin-lodash": "3.2.10",
        "babel-plugin-syntax-flow": "^6.18.0",
        "babel-plugin-syntax-jsx": "^6.18.0",
        "babel-plugin-transform-object-rest-spread": "^6.20.2",
        "babel-plugin-transform-runtime": "^6.15.0",
        "babel-preset-env": "^1.1.1",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-react": "^6.16.0",
        "babel-preset-stage-0": "^6.16.0",
        "babel-register": "^6.18.0",
        "chai": "^3.5.0",
        "lodash-bound": "^1.1.2",
        "lodash-compat": "^3.10.2",
        "lodash-es": "^4.17.2",
        "mocha": "^3.2.0",
        "ramda": "^0.22.1",
        "react-bootstrap": "^0.30.7"
    },
    "directories": {},
    "dist": {
        "shasum": "21c8fdec9fe1835efaa737873e3902bdd66d5701",
        "tarball": "https://registry.npmjs.org/babel-plugin-lodash/-/babel-plugin-lodash-3.2.11.tgz"
    },
    "files": [
        "lib"
    ],
    "greenkeeper": {
        "ignore": [
            "babel-plugin-lodash"
        ]
    },
    "homepage": "https://github.com/lodash/babel-plugin-lodash#readme",
    "keywords": [
        "babel-plugin",
        "cherry-pick",
        "lodash",
        "modules"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "jdalton"
        },
        {
            "name": "mathias"
        }
    ],
    "name": "babel-plugin-lodash",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lodash/babel-plugin-lodash.git"
    },
    "scripts": {
        "build": "babel src --out-dir lib || true",
        "prepublish": "npm run build",
        "test": "mocha --check-leaks --compilers js:babel-register"
    },
    "version": "3.2.11"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
